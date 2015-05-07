AUTOMAKE_OPTIONS = foreign subdir-objects

CFLAGS=-Wall -I/usr/local/include -DVERSION=\"$(VERSION)\" -DPROG="\"$(PACKAGE)\""
LDFLAGS=-L/usr/local/lib -lSDL

bin_PROGRAMS = nanopond
nanopond_SOURCES = src/main.c
