include $(top_srcdir)/example/Makefile.inc

inst_PROGRAMS = ioctl_test
instdir=${exec_prefix}/ofp/bin

ioctl_test_LDFLAGS = $(AM_LDFLAGS) -static

dist_ioctl_test_SOURCES = app_main.c ioctl_test.c

noinst_HEADERS = ${srcdir}/ioctl_test.h
