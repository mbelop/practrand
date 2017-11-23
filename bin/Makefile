PROG=	practrand
BINDIR?=/usr/local/bin

NOMAN=

.PATH:	${.CURDIR}/../tools

SRCS+=	RNG_test.cpp

.if exists(${.CURDIR}/../lib/${__objdir})
LDADD+=	-L${.CURDIR}/../lib/${__objdir} -lpractrand
DPADD+=	${.CURDIR}/../lib/${__objdir}/libpractrand.a
.else
LDADD+=	-L${.CURDIR}/../lib -lpractrand
DPADD+=	${.CURDIR}/../lib/libpractrand.a
.endif

.include <bsd.prog.mk>
