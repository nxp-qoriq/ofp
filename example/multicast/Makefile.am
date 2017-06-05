include $(top_srcdir)/example/Makefile.inc

inst_PROGRAMS = mcast
instdir=${exec_prefix}/ofp/bin

mcast_LDFLAGS = $(AM_LDFLAGS) -static

dist_mcast_SOURCES = app_main.c mcast.c

noinst_HEADERS = ${srcdir}/mcast.h
