SUBDIRS = doc man src

# to prevent compile errors on some systems
AM_CXXFLAGS = -pedantic

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = gig.pc

docs: Doxyfile
	@echo '*** Running doxygen ***'
	doxygen Doxyfile
