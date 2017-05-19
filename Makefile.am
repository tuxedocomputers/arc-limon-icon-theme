EXTRA_DIST = \
	$(srcdir)/ArcLimon \
	$(srcdir)/COPYING \
	$(srcdir)/CREDITS \
	$(srcdir)/README.md

themedir = $(datadir)/icons

install-data-hook:
	test -d $(DESTDIR)$(themedir) || $(MKDIR_P) $(DESTDIR)$(themedir)
	cp -Rv $(srcdir)/ArcLimon $(DESTDIR)$(themedir)/.

uninstall-hook:
	test -d $(DESTDIR)$(themedir)/Arc && rm -rf $(DESTDIR)$(themedir)/ArcLimon
