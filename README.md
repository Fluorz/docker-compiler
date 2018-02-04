Script pour compiler un projet sur Fedora 26

Pour installer le script et docker :

./install.sh

Pour compiler un projet :

compile [FOLDER TO TEST] [ARGUMENTS] [OPTIONS]

ARGUMENTS :

		--help
		--make		[Require a Makefile]
		--gcc		[Require c files with main]
		--gcc-main	[Require c files without main]
		--g++		[Require c++ files]

OPTIONS:
		--exec		[binary name for make] + arguments
		--valgrind	[binary name for make] + arguments
