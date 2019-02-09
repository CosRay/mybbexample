AUTOMAKE_OPTIONS = foreign

CFLAGS = -Wall -pedantic -O2
include_HEADERS = mybbexample.h

lib_LTLIBRARIES = libbbexample.la
libbbexample_la_SOURCES  = mybbexamplelib.c
libbbexample_la_LDFLAGS= -version-info 1:0:0

bin_PROGRAMS = mybbexample
mybbexample_SOURCES = mybbexample.c
mybbexample_LDADD = libbbexample.la
