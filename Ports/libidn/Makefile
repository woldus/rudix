include ../../Library/GNU.mk

Title=		GNU IDN Library
Name=		libidn
Version=	1.33
Site=		http://www.gnu.org/software/libidn/
Source=		http://ftp.gnu.org/gnu/libidn/$(Name)-$(Version).tar.gz
License=	GPL+LGPL

define test_hook
$(BinDir)/idn --version | grep $(Version)
endef
