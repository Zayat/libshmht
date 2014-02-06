# 
# Makefile.am for Makefile.in automatic construction.
# 

SUBDIRS = src

.PHONY: docs 

include_HEADERS = include/shmht.h

docs:
	rm -Rf docs/html docs/latex;
	doxygen docs/Doxyfile

