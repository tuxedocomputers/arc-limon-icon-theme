EXTRA_DIST = \
	$(srcdir)/TUXEDOOne \
	$(srcdir)/COPYING \
	$(srcdir)/CREDITS \
	$(srcdir)/README.md

themedir = $(datadir)/icons

install-data-hook:
	test -d $(DESTDIR)$(themedir) || $(MKDIR_P) $(DESTDIR)$(themedir)
	cp -Rv $(srcdir)/TUXEDOOne $(DESTDIR)$(themedir)/.

uninstall-hook:
	test -d $(DESTDIR)$(themedir)/TUXEDOOne && rm -rf $(DESTDIR)$(themedir)/TUXEDOOne
