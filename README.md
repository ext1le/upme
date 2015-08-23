# upme
Linux software updating system with command-line interface (ncurses/qt/gtk).
Downloads tarball, builds it and makes a package.

REQUIREMENTS

  bash
  wget
  unzip, tar, gzip, xz or what type of compression the tarball has.

INSTALL & USE

  There are three variants:
    1. As an overlay of existing package manager. 
    2. As a script
       Download in any directory and run upme.sh.
    3. File by file.
       Use .sh files separately, only for a needed software.

It don't breaks an existing package management. It just makes the package for it.
