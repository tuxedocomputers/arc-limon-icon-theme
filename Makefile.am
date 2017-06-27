EXTRA_DIST = \
	$(srcdir)/TUXEDO-One \
	$(srcdir)/COPYING \
	$(srcdir)/CREDITS \
	$(srcdir)/README.md

themedir = $(datadir)/icons

install-data-hook:
	test -d $(DESTDIR)$(themedir) || $(MKDIR_P) $(DESTDIR)$(themedir)
	cp -Rv $(srcdir)/TUXEDO-One $(DESTDIR)$(themedir)/.

uninstall-hook:
	test -d $(DESTDIR)$(themedir)/TUXEDO-One && rm -rf $(DESTDIR)$(themedir)/TUXEDO-One
