# Telephony packages feed

## Description

This is an OpenWrt package feed containing community maintained telephony packages.

## Usage

To use these packages, add the following line to the feeds.conf
in the OpenWrt buildroot:

```
src-git xyt git@github.com:seven1240/telephony.git;xyt
```

This feed should be included and enabled by default in the OpenWrt buildroot. To install all its package definitions, run:

```
./scripts/feeds update xyt
./scripts/feeds install -a -p xyt
```

The telephony packages should now appear in menuconfig.
