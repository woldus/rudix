include ../../Library/GNU.mk

Title=		GNU Libtool
Name=		libtool
Version=	2.4.6
Site=		https://www.gnu.org/software/libtool/
Source=		https://ftp.gnu.org/gnu/libtool/$(Name)-$(Version).tar.gz
License=	GPLv2

define test_hook
$(BinDir)/libtool --version | grep $(Version)
endef
