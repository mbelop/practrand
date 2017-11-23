LIB=	practrand
NOPROFILE=

.PATH:	${.CURDIR}/../src

SRCS=	math.cpp non_uniform.cpp platform_specifics.cpp rand.cpp sha2.cpp
SRCS+=	test_batteries.cpp tests.cpp

.PATH:	${.CURDIR}/../src/RNGs

SRCS+=	arbee.cpp chacha.cpp efiix.cpp hc256.cpp isaac.cpp jsf.cpp mt19937.cpp
SRCS+=	salsa.cpp sfc.cpp sha2_based_pool.cpp trivium.cpp xsm.cpp

.PATH:	${.CURDIR}/../src/RNGs/other

SRCS+=	fibonacci.cpp indirection.cpp mult.cpp simple.cpp transform.cpp

install:
	# Nothing to install

.include <bsd.lib.mk>
