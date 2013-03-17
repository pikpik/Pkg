Pkg
===

Pkgsrc, made simpler


Requires
--------

[IEEE Std 1003.1-2008](http://pubs.opengroup.org/onlinepubs/9699919799/utilities/sh.html) compliant /bin/sh.

Pkgsrc installed at /usr/pkgsrc.

Pkg_info installed.


Commands
--------

install    category or category/package

  When used, `pkg` will first attempt to install a compiled package from /usr/pkgsrc/packages.

  If none can be found, the online repository will searched and the package will be downloaded and installed from there.

  If a compiled package still isn't found, the source code will be downloaded and compiled and the compiled package will be installed.

installed

  This lists all packages installed.

uninstall  category or category/package

  This command uninstalls the entire "category" or the specific "category/package" specified.

update     category or category/package

  This command updates the entire "category" or the specific "category/package" specified.

available  empty, category, or category/package

  This command shows all categories, the packages in the given "category," or the specific package at "category/package."

about      category or category/package

  This command shows the entire "category" or the specific "category/package" specified.

help

  This command shows a condensed listing of commands.


License
-------

Copyright (c) 2013, pikpik

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
