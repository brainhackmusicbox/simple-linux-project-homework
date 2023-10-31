AUTOMAKE_OPTIONS = foreign
bin_PROGRAMS = simpleLinuxProject
simpleLinuxProject_SOURCES = main.c func.c
include_HEADERS = header.h

clean-all:
	echo "Removing all files except *.c, *.h, *.ac, *.am"
	find . -not \( -name '*.c' \
		-or -name '*.h' \
		-or -name '*.ac' \
		-or -name '*.am' \
		-or -name 'README.md' \
		-or -name '.' \
		-or -name '..' \
		\) | xargs rm -rf

	echo "Removing simpleLinuxProject binary from /usr/local/bin/"
	$(RM) /usr/local/bin/simpleLinuxProject

	echo "Removing header from /usr/local/include/"
	$(RM) /usr/local/include/header.h
