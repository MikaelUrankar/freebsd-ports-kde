PORTNAME=	kalm
DISTVERSION=	${KDE_APPLICATIONS_VERSION}
CATEGORIES=	misc kde kde-applications

MAINTAINER=	kde@FreeBSD.org
COMMENT=	Kalm can teach you different breathing techniques
WWW=		https://invent.kde.org/utilities/kalm

LICENSE=	LGPL21

BUILD_DEPENDS=	kf6-kcrash>0:devel/kf6-kcrash \
		kf6-qqc2-desktop-style>0:x11-themes/kf6-qqc2-desktop-style

USES=		cmake gettext kde:6 qt:6 tar:xz
USE_KDE=	config coreaddons dbusaddons i18n kirigami-addons \
		ecm:build
USE_QT=		base declarative svg
USE_GL=		gl opengl

.include <bsd.port.mk>
