PORTNAME=	koko
DISTVERSION=	${KDE_APPLICATIONS_VERSION}
CATEGORIES=	graphics kde kde-applications

MAINTAINER=	kde@FreeBSD.org
COMMENT=	Image gallery application
WWW=		https://apps.kde.org/koko

LICENSE=	LGPL21

USES=		cmake desktop-file-utils gettext-tools kde:6 qt:6 tar:xz
USE_KDE=	bookmarks colorscheme completion config configwidgets coreaddons dbusaddons ecm:build filemetadata guiaddons i18n itemviews jobwidgets kdeclarative kio kirigami-addons notifications service solid widgetsaddons windowsystem
USE_QT=		base declarative positioning svg
USE_GL=		gl opengl
USE_XORG=	x11

BUILD_DEPENDS=	kquickimageeditor-qt6>0:graphics/kquickimageeditor@qt6
RUN_DEPENDS=	kquickimageeditor-qt6>0:graphics/kquickimageeditor@qt6

.include <bsd.port.mk>
