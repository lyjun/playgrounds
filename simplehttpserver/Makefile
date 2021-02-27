PKG_DIR		:= ${PWD}
BIN_DIR		:= ${DESTDIR}/usr/bin

all: 

install:
	mkdir -p ${BIN_DIR}
	install -m 644 *.py ${BIN_DIR}/
	install -m 644 simplehttpserver.service ./debian/

clean:
	rm -rf *.pyc || true
