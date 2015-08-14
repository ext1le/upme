# upme
Linux software updating system with command-line interface (ncurses qt/gtk in plans). Downloads tarball, builds it and makes a package.

REQUIREMENTS

  bash
  wget
  TODO(file - to identify file type for auto decompression)
  unzip, tar, gzip, xz or what type of compression the tarball has.

INSTALL & USE

  There are three variants:
    1. As a package manager.
       TODO(Run with '-p' option and get a package for your system.)
    2. As script from any directory.
       Download in any directory and run upme.sh.
    3. File by file.
       Use .sh files separately, only for a needed software.

  chmod +x files you want or use TODO(or do it from ncurses interface).

It don't breaks an existing package management. It just makes the package for.
