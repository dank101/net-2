#	@(#)Makefile	5.1 (Berkeley) 5/3/91

PROG=	init
SRCS=	init.c
CFLAGS+=-DLETS_GET_SMALL
DPADD=	${LIBUTIL}
LDADD=	-lutil
BINMODE=500
NOMAN=	noman
LDFLAGS=-N
.PATH:	${.CURDIR}/../../../../sbin/init

.include <bsd.prog.mk>
