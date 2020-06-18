## Keylime debian packager

A first cut at building a debian packager for keylime. It's based on
dh-python, and therefore in turn relies on pip3.

# TODOs

* Have the copyright file checked and approved.
* Get basic buy-in on the dh-python approach.
* Have the dependencies tested by as many people as can be.
* Python nose tests are currently disabled. They need to be enabled so
  unit tests can run before packaging.
* No services other than keylime-agent have been tested yet.
