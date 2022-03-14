# cp-sublime-build-system
A sublime build system for compatitive programmers.

## How to use
- Open `cp-build`
- Edit the `CONFIG` section:
	- change `TERMINAL` variable to a terminal you are going to use.
	- change `INFILE` variable to the path of input file.
	- change `OUTFILE` variable to the path of output file.
- copy `cp-build` to `~/.local/bin/`
- give it executing permission (`chmod +x ~/.local/bin/cp-build`)
- copy `cp-build.sublime-build` to `~/.config/sublime-text/Packages/User`

## Features
- Interactive problem support
- GDB support
- IOI-like grader support (if there is a file named `grader.cpp` or `stub.cpp` (or both) in the same folder of your code, your code will be compiled with that grader or stub (or both))