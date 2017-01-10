include $(top_srcdir)/example/Makefile.inc

inst_PROGRAMS = udpecho
instdir=${exec_prefix}/ofp/bin

udpecho_LDFLAGS = $(AM_LDFLAGS) -static

dist_udpecho_SOURCES = app_main.c udp_server.c

noinst_HEADERS = ${srcdir}/udp_server.h
