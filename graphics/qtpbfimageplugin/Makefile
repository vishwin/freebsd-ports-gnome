# $FreeBSD$

PORTNAME=	qtpbfimageplugin
DISTVERSION=	1.1
CATEGORIES=	graphics

MAINTAINER=	sikmir@gmail.com
COMMENT=	Qt image plugin for displaying Mapbox vector tiles

LICENSE=	LGPL3
LICENSE_FILE=	${WRKSRC}/LICENSE

LIB_DEPENDS=	libprotobuf-lite.so:devel/protobuf

USES=		gl qmake qt:5
USE_QT=		core gui buildtools_build
USE_GL=		gl
USE_LDCONFIG=	${PREFIX}/${QT_LIBDIR_REL}

USE_GITHUB=	yes
GH_ACCOUNT=	tumic0
GH_PROJECT=	QtPBFImagePlugin

PLIST_FILES=	${QT_PLUGINDIR}/imageformats/libpbf.so

.include <bsd.port.mk>
