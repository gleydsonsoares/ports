# $OpenBSD: Makefile,v 1.15 2019/11/26 00:25:31 kmos Exp $

COMMENT =		US-ASCII transliterations of Unicode text

MODPY_EGG_VERSION =	1.1.1
DISTNAME =		Unidecode-${MODPY_EGG_VERSION}
PKGNAME =		py-${DISTNAME:L}

CATEGORIES =		textproc devel

HOMEPAGE =		https://pypi.python.org/pypi/Unidecode

# GPLv2+
PERMIT_PACKAGE =	Yes

MODULES =		lang/python

MODPY_PI = 		Yes
MODPY_SETUPTOOLS =	Yes
MODPY_PYTEST =		Yes

FLAVORS =		python3
FLAVOR ?=

post-install:
	mv ${PREFIX}/bin/unidecode{,${MODPY_BIN_SUFFIX}}

.include <bsd.port.mk>
