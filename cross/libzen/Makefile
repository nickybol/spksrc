PKG_NAME = libzen
PKG_VERS = 0.4.29
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_NAME)_$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://downloads.sourceforge.net/project/zenlib/ZenLib%20-%20Sources/$(PKG_VERS)
PKG_DIR = ZenLib/Project/GNU/Library

DEPENDS = 

HOMEPAGE = http://sourceforge.net/projects/zenlib/
COMMENT  = Small C++ derivate class to have a simpler life.
LICENSE  = 

PRE_CONFIGURE_TARGET = myPreConfigure
GNU_CONFIGURE = 1

CONFIGURE_ARGS = --enable-shared

include ../../mk/spksrc.cross-cc.mk

myPreConfigure:
	$(RUN) ; ./autogen
