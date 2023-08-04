PROJECT=sh-pass-helpers
VERSION=1.0.0
PREFIX=/usr/local
all:
clean:
install:

## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/pass-del         $(DESTDIR)$(PREFIX)/bin
	cp bin/pass-dmenu       $(DESTDIR)$(PREFIX)/bin
	cp bin/pass-x           $(DESTDIR)$(PREFIX)/bin
	cp bin/pass-gen         $(DESTDIR)$(PREFIX)/bin
	cp bin/pass-ls          $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
## -- BLOCK:license --
install: install-license
install-license: 
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
	cp LICENSE README.md $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
update: update-license
update-license:
	ssnip README.md
## -- BLOCK:license --
