# $OpenBSD: Makefile,v 1.16 2020/06/13 08:23:35 ajacoutot Exp $

# !!! do not update blindly: sysutils/awscli requires a specific version

COMMENT=		Python RSA implementation

MODPY_EGG_VERSION=	4.6
DISTNAME=		rsa-${MODPY_EGG_VERSION}
PKGNAME=		py-${DISTNAME}

CATEGORIES=		security

MAINTAINER=		Antoine Jacoutot <ajacoutot@openbsd.org>

# Apache 2.0
PERMIT_PACKAGE=	Yes

MODULES=		lang/python

MODPY_PI=		Yes
MODPY_SETUPTOOLS=	Yes
MODPY_PYTEST =		Yes

RUN_DEPENDS=		devel/py-asn1${MODPY_FLAVOR}

FLAVORS=		python3
FLAVOR ?=		python3

.include <bsd.port.mk>
