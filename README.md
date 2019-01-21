# Free Ada (work on-going)

Extended version originally provided by:
Copyright (C) 2011-2017 Luke A. Guest with assistance from David Rees

To build toolchain:

  cp config-master.inc config.inc
  <modify config.inc as required>
  ./download.sh
  ./build-tools.sh -t 1

If you leave everything as default, you will have a bunch of archives in a packages directory and the toolchain installed
to ```$HOME/opt/free-ada-new

# Note

There's currently no libc (newlib) built.
