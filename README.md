Pkg
===

Pkgsrc, made simpler


Commands
--------

**pkg installed** or **pkg ind**

  Lists all packages installed.


**pkg available** or **pkg av**

  Shows all packages in all categories.


**pkg install** or **pkg in** *package*

  When used, `pkg` will attempt to install the compiled package from /usr/pkgsrc/packages.

  If one isn't found, the online repository will searched and the package will be downloaded and installed.

  If a compiled package isn't available, the package's source code will be downloaded, compiled, and installed.


**pkg uninstall** or **pkg un** *package*

  Uninstalls the *package* specified.


**pkg update** or **pkg up** *package*

  Updates the *package* specified.


**pkg search** or **pkg s** *package*

  Finds the full names of packages matching the *package* name specified.


**pkg about** or **pkg a** *package*

  Describes the *package* specified.


**pkg help** or **pkg h**

  Shows a condensed listing of commands.


Requires
--------

 * [IEEE Std 1003.1-2008](http://pubs.opengroup.org/onlinepubs/9699919799/utilities/sh.html) compliant `/bin/sh`

 * Pkgsrc installed at /usr/pkgsrc with `pkg_info` and `bmake`


License
-------

Copyright (c) 2013, pikpik

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.