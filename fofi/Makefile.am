noinst_LTLIBRARIES = libfofi.la

if ENABLE_XPDF_HEADERS
poppler_fofi_includedir = $(includedir)/poppler/fofi
poppler_fofi_include_HEADERS =	\
	FoFiBase.h		\
	FoFiEncodings.h		\
	FoFiTrueType.h		\
	FoFiType1.h		\
	FoFiIdentifier.h	\
	FoFiType1C.h
endif

libfofi_la_SOURCES =		\
	FoFiBase.cc		\
	FoFiBase.h		\
	FoFiEncodings.cc	\
	FoFiEncodings.h		\
	FoFiTrueType.cc		\
	FoFiTrueType.h		\
	FoFiType1.cc		\
	FoFiType1.h		\
	FoFiType1C.cc		\
	FoFiIdentifier.cc	\
	FoFiType1C.h

libfofi_la_CPPFLAGS =		\
	-I$(top_srcdir)
