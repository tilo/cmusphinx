# libsphinx2fe: Feature Extraction interface for Sphinx-II

lib_LTLIBRARIES = libsphinx2fe.la

libsphinx2fe_la_LDFLAGS = -version-info 0:6:0

libsphinx2fe_la_SOURCES = \
	fe_interface.c \
	fe_sigproc.c \
	fe_warp.c \
	fe_warp_affine.c \
	fe_warp_inverse_linear.c \
	fe_warp_piecewise_linear.c

noinst_HEADERS = fe_internal.h \
	fe_warp.h \
	fe_warp_affine.h \
	fe_warp_inverse_linear.h \
	fe_warp_piecewise_linear.h

INCLUDES = -I$(top_srcdir)/include -I$(top_builddir)/include
