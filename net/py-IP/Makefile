# $OpenBSD: Makefile,v 1.37 2019/11/30 23:48:26 kmos Exp $

COMMENT =	Python module to handle IPv4 and IPv6 address

MODPY_EGG_VERSION =	1.00
DISTNAME =		IPy-${MODPY_EGG_VERSION}
PKGNAME =		py-IP-${MODPY_EGG_VERSION}
CATEGORIES =		net

HOMEPAGE =		https://github.com/autocracy/python-ipy/wiki

MAINTAINER =		Benoit Lecocq <benoit@openbsd.org>

# BSD
PERMIT_PACKAGE =	Yes

MODPY_PI =		Yes

MODULES =		lang/python

FLAVORS =		python3
FLAVOR ?=

MODPY_DISTUTILS_INSTALLARGS =	-O2
MODPY_PYOEXTENSION =		opt-2.pyc
MODPY_PYTEST =			Yes

WRKDIST =		${WRKDIR}/${DISTNAME}

.include <bsd.port.mk>
