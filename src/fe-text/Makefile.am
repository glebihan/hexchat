localedir = $(datadir)/locale

bin_PROGRAMS = hexchat-text

EXTRA_DIST = README 

INCLUDES = $(COMMON_CFLAGS) -DLOCALEDIR=\"$(localedir)\"

hexchat_text_LDADD = ../common/libxchatcommon.a $(COMMON_LIBS)
hexchat_text_SOURCES = fe-text.c fe-text.h

