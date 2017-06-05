include $(top_srcdir)/example/Makefile.inc

inst_PROGRAMS = udp_fwd_socket
instdir=${exec_prefix}/ofp/bin

udp_fwd_socket_LDFLAGS = $(AM_LDFLAGS) -static

dist_udp_fwd_socket_SOURCES = app_main.c udp_fwd_socket.c

noinst_HEADERS = ${srcdir}/udp_fwd_socket.h
