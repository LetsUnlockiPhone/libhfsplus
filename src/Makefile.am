AM_CFLAGS = $(libcrippy_CFLAGS) $(libmacho_CFLAGS) -I$(top_srcdir)/include
AM_LDFLAGS = $(libcrippy_LIBS) $(libmacho_LIBS)

lib_LTLIBRARIES = libhfsplus-1.0.la
libhfsplus_1_0_la_CFLAGS = $(AM_CFLAGS)
libhfsplus_1_0_la_LDFLAGS = $(AM_LDFLAGS)
libhfsplus_1_0_la_SOURCES = \
								libhfsplus.c \
								xattr.c \
								volume.c \
								utility.c \
								rawfile.c \
								hfslib.c \
								hfscompress.c \
								flatfile.c \
								fastunicodecompare.c \
								extents.c \
								catalog.c \
								btree.c \
								abstractfile.c