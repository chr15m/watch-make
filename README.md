A script that rebuilds your project only when `make` detects it needs a rebuild, for example when source files change.

 * Works with any existing Makefile based project.
 * No dependencies apart from `make`.
 * Passes any arguments to `make` (such as `-C mydir`).
 * Silent if there is nothing to build and does not swallow output when there is.

<http://stackoverflow.com/a/40970553/2131094>

## Run

	watch-make

# Install 

	curl -s https://raw.githubusercontent.com/chr15m/watch-make/master/watch-make > ~/bin/watch-make
	chmod 755 ~/bin/watch-make

