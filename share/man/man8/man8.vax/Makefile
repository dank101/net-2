#	@(#)Makefile	5.5 (Berkeley) 3/22/91

MAN8=	MAKEDEV.0 crash.0 drtest.0 format.0 installboot.0
MANSUBDIR=/vax

all: ${MAN8}

clean depend lint tags:

cleandir:
	rm -f ${MAN8}

install: maninstall

.include <bsd.prog.mk>
