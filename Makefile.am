

AM_CPPFLAGS	= -include autoconf.h
AM_CFLAGS	= $(MCWM_CFLAGS)

bin_PROGRAMS	= mcwm hidden
dist_pkglibexec_SCRIPTS	= scripts/9icon scripts/mcicon scripts/mcmenu

mcwm_SOURCES	= mcwm.c events.h list.c list.h config.h
mcwm_LDADD	= $(MCWM_LIBS)

hidden_SOURCES	= hidden.c
hidden_LDADD	= $(MCWM_LIBS)

dist_man1_MANS	= mcwm.man hidden.man

EXTRA_DIST	= LICENSE TODO WISHLIST
