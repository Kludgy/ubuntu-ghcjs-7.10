# ubuntu-ghcjs-7.10

Vagrant provisioning of GHCJS for the latest and greatest GHC-7.10 release, presently on top of a pristine precise64 box.


### What is GHCJS?

See: https://github.com/ghcjs/ghcjs/blob/master/README.markdown


### Why not follow the standard GHCJS installation?

GHCJS installation presently requires additional nontrivial steps due to pending upstream package changes. The `.vagrant_provisions/etc/bootstrap` bash script is my attempt to track the additional steps involved, and hopefully save others from repeating the same work.

Ultimately this repository should become obsolete once all upstream changes are published.
