DESTDIR =
PREFIX  =/usr/local


all:
clean:
install:
update:
## -- install-sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/pass-del         $(DESTDIR)$(PREFIX)/bin
	cp bin/pass-dmenu       $(DESTDIR)$(PREFIX)/bin
	cp bin/pass-gen         $(DESTDIR)$(PREFIX)/bin
	cp bin/pass-ls          $(DESTDIR)$(PREFIX)/bin
## -- install-sh --
## -- license --
install: install-license
install-license: LICENSE
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/sh-pass-helpers
	cp LICENSE $(DESTDIR)$(PREFIX)/share/doc/sh-pass-helpers
## -- license --
