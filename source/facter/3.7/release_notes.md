---
layout: default
title: "Facter 3.6 Release notes"
---

This page documents the history of the Facter 3.7 series.


## Facter 3.7.0

Released June 26, 2017.

This version of Facter is included in the Puppet agent 5.0.0 release.

### Bug fixes

* [FACT-1579](https://tickets.puppetlabs.com/browse/FACT-1579): Running on Devuan, the `operatingsystem` fact would return `Linux`. It now properly returns `Devuan`. 

* [FACT-1268](https://tickets.puppetlabs.com/browse/FACT-1268): Timeout for retrieving EC2 facts has been increased from 200ms to 600ms.

* [FACT-1544](https://tickets.puppetlabs.com/browse/FACT-1544): Cache files are now deleted once their associated entry in the TTL list in the config file is removed.

* [FACT-1455](https://tickets.puppetlabs.com/browse/FACT-1455): Facter now correctly returns the `id` fact when a group file entry is larger than 1KiB.
