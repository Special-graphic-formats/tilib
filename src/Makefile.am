## Process this file with automake to produce Makefile.in

## Created by Anjuta - will be overwritten
## If you don't want it to overwrite it,
## 	Please disable it in the Anjuta project configuration

INCLUDES =

CFLAGS = -Wall -Wimplicit -Wunused -Wmissing-prototypes -O3

bin_PROGRAMS = ticodec

# the library search path.
lib_LTLIBRARIES = libtilib.la
libtilib_la_SOURCES = ari.c bitio.c butterworth.c color.c daub97.c extend.c nodelist.c spiht.c split.c tilib.c
libtilib_la_LDFLAGS = -version-info 1:0:0 -no-undefined
include_HEADERS =

ticodec_SOURCES = pbm.c ticodec.c
ticodec_LDFLAGS = 
ticodec_LDADD = libtilib.la

