#	@(#)Makefile	5.1 (Berkeley) 5/3/91

PROG=	dump
SRCS=	dumpitime.c dumpmain.c dumpoptr.c dumptape.c dumptraverse.c \
	unctime.c
CFLAGS+=-DLETS_GET_SMALL -I${.CURDIR}/../../../../sbin/dump
NOMAN=	noman
LDFLAGS=-N
.PATH:	${.CURDIR}/../../../../sbin/dump

.include <bsd.prog.mk>
