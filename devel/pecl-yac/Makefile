# Created by: Oliver Lehmann <oliver@FreeBSD.org>
# $FreeBSD$

PORTNAME=	yac
PORTVERSION=	2.0.2
PORTEPOCH=	1
CATEGORIES=	devel

MAINTAINER=	oliver@FreeBSD.org
COMMENT=	Yac is a shared memory user data cache for PHP

LICENSE=	PHP301

USES=		php:pecl
IGNORE_WITH_PHP=	56 73

OPTIONS_DEFINE=	MSGPACK
MSGPACK_DESC=	Enable MSGPACK module
MSGPACK_BUILD_DEPENDS=	${LOCALBASE}/lib/php/${PHP_EXT_DIR}/msgpack.so:devel/pecl-msgpack@${PHP_FLAVOR}
MSGPACK_RUN_DEPENDS=	${LOCALBASE}/lib/php/${PHP_EXT_DIR}/msgpack.so:devel/pecl-msgpack@${PHP_FLAVOR}

.include <bsd.port.mk>
