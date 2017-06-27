# TUXEDO Icon Theme One

**Note:** This is still unfinished. It may not work as expected in some cases.

At the moment this theme mainly includes icons for folders and mimetypes.

### Requirements

This theme doesn't provide application icons, it needs another icon theme to inherit them.
By default this theme will look for the [Moka icon theme](https://snwh.org/moka) to get the missing icons. If Moka is not installed it will use the Gnome icon theme as fallback.
To change the application icons, edit `TUXEDO-One/index.theme` and replace `Moka` with the name of your preferred icon theme

For example, if you like the Faenza icon theme, change

    [Icon Theme]
    Name=TUXEDO-One
    Inherits=Moka,Adwaita,gnome,hicolor
    Comment=TUXEDO One Limon Icon theme

to

    [Icon Theme]
    Name=TUXEDO-One
    Inherits=Faenza,Adwaita,gnome,hicolor
    Comment=TUXEDO One Limon Icon theme

### Installation

Installation via autotools:

    git clone https://github.com/tuxedocomputers/tuxedo-icons-theme-one --depth 1 && cd tuxedo-icons-theme-one
    ./autogen.sh --prefix=/usr
    sudo make install

Alternatively you may copy the `TUXEDO-One` folder to `~/.icons` or to `/usr/share/icons` for system-wide use.

### Uninstall

Run

    sudo make uninstall

from the same directory as this README resides in, or

    sudo rm -rf /usr/share/icons/TUXEDO-One


License: GPLv3
