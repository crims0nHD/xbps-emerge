#xbps-emerge USAGE
-------------------
NOTE: this section uses emerge as a symlink to /usr/bin/xbps-emerge

```
emerge -h

NOTE: flags can NOT be combined when they are from seperate categories except for GENERAL and Flags: "-S"
      You can however, combine flags like this "-Pu" + "-Pr" = "-Pur"

GENERAL
--------
-y: Say yes to all asked questions by default
-v: Verbose output


REPOSITORY MANAGEMENT
----------------------
-Rs: pull changes from remote
-S: alias to -Rs

PACKAGE MANAGEMENT
-------------------
-u: update all packages (this runs xbps-install -u) in the background
-r: remove package
-Pu: alias to -u
-Pr: alias to -r

INFORMATION QUERYING
---------------------
-Q

```
