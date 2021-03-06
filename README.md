**Current build status:** [![Build Status](https://travis-ci.org/anders-larsson/gentoo-overlay.svg)](https://travis-ci.org/anders-larsson/gentoo-overlay)

gentoo-overlay
==============

Overlay for Gentoo/Linux packages

The following packages are available in this overlay:

* 389-ds-base - https://directory.fedoraproject.org
* bind-adblock - https://github.com/Trellmor/bind-adblock
* certbot-dns-rfc2136 - https://github.com/certbot/certbot/tree/master/certbot-dns-rfc2136
* duo_unix - https://github.com/duosecurity/duo_unix
* dwarf-therapist - https://github.com/Dwarf-Therapist/Dwarf-Therapist
* FreshRSS - https://github.com/FreshRSS/FreshRSS
* systembus-notify - https://github.com/rfjakob/systembus-notify

## Warning

This overlay is not official but is available in layman's repository.

**Use ebuilds supplied in this repository on your own risk**. They've been tested on my own system setup (~amd64) and (most likely) tested on virtual systems (amd64 and x86).

## Installing

First time using layman? See https://wiki.gentoo.org/wiki/Layman

    layman -a anders-larsson
