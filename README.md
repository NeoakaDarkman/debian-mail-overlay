## neoakadarkman/debian-mail-overlay

This overlay base image based on [hardware/debian-mail-overlay](https://github.com/hardware/debian-mail-overlay) image and contains Debian slim (Debian 11 "Bullseye", remove some extra files that are normally not necessary within containers, such as man pages and documentation), compile skarnet.org's small & secure supervision software suite (skalibs, execline, s6) and build Rspamd, the fast, free and open-source spam filtering system.

Software built from source :

* Skalibs 2.12.0.1 : https://skarnet.org/software/skalibs/
* Execline 2.9.0.1 : https://skarnet.org/software/execline/
* s6 2.11.1.2 : https://skarnet.org/software/s6/
* Rspamd 3.3 : https://rspamd.com/
* Gucci 1.6.5 : https://github.com/noqcks/gucci/

Please see the [main repository](https://github.com/neoakadarkman/mailserver) for instructions.
