# cFS: Housekeeping

[![GitHub release](https://img.shields.io/github/release/lassondesat/cfs-hk.svg)](https://github.com/lassondesat/cfs-hk/releases)
lassondesat
* [Original README](cfs-hk-app-OSS-readme.txt)

## Description

The Housekeeping application (HK) is a core Flight System (cFS) application that
is a plug in to the Core Flight Executive (cFE) component of the cFS.

The cFS is a platform and project independent reusable software framework and
set of reusable applications developed by NASA Goddard Space Flight Center. This
framework is used as the basis for the flight software for satellite data
systems and instruments, but can be used on other embedded systems. More
information on the cFS can be found at http://cfs.gsfc.nasa.gov

The HK application is used for building and sending combined telemetry messages
(from individual system applications) to the software bus for routing. Combining
messages is performed in order to minimize downlink telemetry bandwidth.
Combined messages are also useful for organizing certain types of data packets
together. HK provides the capability to generate multiple combined packets so
that data can be sent at different rates.

## Requirements

* [Operating System Abstraction Layer][osal] 4.1.1 or higher
* [core Flight Executive][cfe] 6.4.1 or higher

## Sources

* https://sourceforge.net/projects/cfs-hk/

[osal]: https://github.com/lassondesat/osal
[cfe]: https://github.com/lassondesat/coreflightexec
