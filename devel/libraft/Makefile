PORTNAME=    raft
DISTVERSION= v0.16.0
CATEGORIES=  net devel

MAINTAINER=  freebsd@dhke.de
COMMENT=     Canonical's implementation of the RAFT protocol

LICENSE=     LGPL3

LIB_DEPENDS= libuv.so:devel/libuv \
			 liblz4.so:archivers/liblz4

USES=        autoreconf
GNU_CONFIGURE= yes
CONFIGURE_ARGS= --disable-uv
USE_GITHUB=  yes
GH_ACCOUNT=  canonical

.include <bsd.port.mk>
