AM_CFLAGS = -O2 -Wall
EXTRA_DIST = tetris.dat tetris.cfg

noinst_PROGRAMS = tetris

CFLAGS = `allegro-config --cflags`
LIBS = `allegro-config --libs`

tetris_SOURCES = \
tetris.h \
data.h \
timer.h \
tetris.c \
hiscore.c \
player.c \
piece.c
