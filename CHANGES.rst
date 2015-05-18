List of changes
===============

This file contains the running log of changes applied to each released hitch
version.


hitch 1.0.0-beta1 (2015-05-xx)
------------------------------

Hitch 1.0.0-beta1 is based on stud 0.3.2. A selected set of public patches from
github forks were applied.

Notable changes:

* TLS v1.0, TLS v1.1 and TLS v1.2 support.
* Support for SNI added.
* Support PROXYv1 and PROXYv2 protocol to origin.
* Multiple listening sockets with possibly different default key/certificate.
* Wildcard certificates are supported. (with and without SNI.)
* SSL3.0 must now be enabled explicitly.


Various minor and stylistic fixed issues:

* Properly clean SSL error queue.
* Do not segfault if backend is not ready.
* Logging now knows about IPv6.
* IPv6 adresses should now use bracketed notation.
* Additional timeouts for backend connect and SSL handshake added.
* autoconf/automake is now used for building hitch.
