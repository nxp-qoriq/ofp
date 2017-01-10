include $(top_srcdir)/example/Makefile.inc

inst_PROGRAMS = sysctl
instdir=${exec_prefix}/ofp/bin

sysctl_LDFLAGS = $(AM_LDFLAGS) -static

dist_sysctl_SOURCES = app_main.c sysctl.c

noinst_HEADERS = ${srcdir}/sysctl.h
