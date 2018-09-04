# $Id$

AUTOMAKE_OPTIONS = foreign
PYTHON = python

all:
	$(PYTHON) setup.py build

install: all
	$(PYTHON) setup.py install --prefix=$(DESTDIR)$(prefix)

clean:
	$(PYTHON) setup.py clean

dist-clean: clean


EXTRA_DIST = setup.py libemu_module.c


