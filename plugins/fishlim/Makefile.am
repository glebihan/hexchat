EXTRA_DIST = INSTALL LICENSE README

libdir = $(hexchatlibdir)/plugins

lib_LTLIBRARIES = fishlim.la
fishlim_la_SOURCES = fish.c irc.c keystore.c misc.c plugin_xchat.c
fishlim_la_LDFLAGS = -avoid-version -module 
fishlim_la_LIBADD = 
INCLUDES = $(COMMON_CFLAGS) -I$(srcdir)/..
