AM_CPPFLAGS = -I$(srcdir) -I$(srcdir)/include -I$(srcdir)/include/libutp
AM_CXXFLAGS = -Wall -Wno-sign-compare -DPOSIX -fno-exceptions -fno-rtti -fpermissive
noinst_LIBRARIES = libutp.a
libutp_a_SOURCES = \
		   utp_internal.cpp \
		   utp_internal.h \
		   utp_utils.cpp \
		   utp_utils.h \
		   utp_hash.cpp \
		   utp_hash.h \
		   utp_callbacks.cpp \
		   utp_callbacks.h \
		   utp_api.cpp \
		   utp_packedsockaddr.cpp \
		   utp_packedsockaddr.h \
		   utp_templates.h \
		   libutp_inet_ntop.h \
		   include/libutp/utp.h \
		   include/libutp/utp_types.h
EXTRA_DIST = \
	     LICENSE \
	     README.md

