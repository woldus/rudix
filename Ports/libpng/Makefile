include ../../Library/GNU.mk

Title=		PNG
Name=		libpng
Version=	1.6.14
Site=		http://www.libpng.org/pub/png/
Source=		http://downloads.sourceforge.net/libpng/$(Name)-$(Version).tar.xz
License=	BSD

LicenseFile=	$(SourceDir)/LICENSE

define test_hook
$(BinDir)/libpng-config --version | grep $(Version)
endef
