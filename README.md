# SoftEther VPN

[![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/softethervpn/softethervpn?branch=master&svg=true)](https://ci.appveyor.com/project/softethervpn/softethervpn) [![Travis CI build status](https://travis-ci.org/SoftEtherVPN/SoftEtherVPN.svg?branch=master)](https://travis-ci.org/SoftEtherVPN/SoftEtherVPN)

SoftEther VPN (Developer Edition Master Repository)
- An Open-Source Cross-platform Multi-protocol VPN Program
http://www.softether.org/


This repository has experimental codes. Pull requests are welcome.

Stable Edition is available on
https://github.com/SoftEtherVPN/SoftEtherVPN_Stable
which the non-developer user can stable use.

Source code packages (.zip and .tar.gz) and binary files of Stable Edition are also available:
http://www.softether-download.com/

We accept your patches by the acceptance policy:
http://www.softether.org/5-download/src/9.patch

Copyright (c) SoftEther Project at University of Tsukuba, Japan.

The development of SoftEther VPN was supported by the MITOH Project,
a research and development project by Japanese Government,
subsidized by Ministry of Economy, Trade and Industry of Japan,
administrated by Information Promotion Agency.
https://www.ipa.go.jp/english/humandev/


This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License version 2
as published by the Free Software Foundation.

SoftEther VPN ("SoftEther" means "Software Ethernet") is one of the
world's most powerful and easy-to-use multi-protocol VPN software.

SoftEther VPN runs on Windows, Linux, Mac, FreeBSD and Solaris.

SoftEther VPN supports most of widely-used VPN protocols
including SSL-VPN, OpenVPN, IPsec, L2TP, MS-SSTP, L2TPv3 and EtherIP
by the single SoftEther VPN Server program.

More details on http://www.softether.org/.


# BOARD MEMBERS OF THIS REPOSITORY


Daiyuu Nobori (Since Jan 2, 2014)
https://github.com/dnobori

Moataz Elmasry (Since Nov 6, 2017)
https://github.com/moatazelmasry2

Zulyandri Zardi (Since Nov 6, 2017)
https://github.com/zulzardi

Alex Maslakov (Since Nov 6, 2017)
https://github.com/GildedHonour



# SOFTETHER VPN ADVANTAGES


- Supporting all popular VPN protocols by the single VPN server:
  SSL-VPN (HTTPS)
  OpenVPN
  IPsec
  L2TP
  MS-SSTP
  L2TPv3
  EtherIP
- Free and open-source software.
- Easy to establish both remote-access and site-to-site VPN.
- SSL-VPN Tunneling on HTTPS to pass through NATs and firewalls.
- Revolutionary VPN over ICMP and VPN over DNS features.
- Resistance to highly-restricted firewall.
- Ethernet-bridging (L2) and IP-routing (L3) over VPN.
- Embedded dynamic-DNS and NAT-traversal so that no static nor
  fixed IP address is required.
- AES 256-bit and RSA 4096-bit encryptions.
- Sufficient security features such as logging and firewall inner
  VPN tunnel.
- User authentication with RADIUS and NT domain controllers.
- User authentication with X.509 client certificate.
- Packet logging.
- 1Gbps-class high-speed throughput performance with low memory and
  CPU usage.
- Windows, Linux, Mac, Android, iPhone, iPad and Windows Phone are
  supported.
- The OpenVPN clone function supports legacy OpenVPN clients.
- IPv4 / IPv6 dual-stack.
- The VPN server runs on Windows, Linux, FreeBSD, Solaris and Mac OS X.
- Configure All settings on GUI.
- Multi-languages (English, Japanese and Simplified-Chinese).
- No memory leaks. High quality stable codes, intended for long-term runs.
  We always verify that there are no memory or resource leaks before
  releasing the build.
- More details at http://www.softether.org/.


# GETTING STARTED

Visit the SoftEther VPN Project official web site at first:
        http://www.softether.org/

If you are not a developer, it is recommended to download the binary
installers from:
        http://www.softether-download.com/

To build from the source,
see [BUILD_UNIX](src/BUILD_UNIX.md) or [BUILD_WINDOWS](src/BUILD_WINDOWS.md) files.

# PREBUILT BINARY PACKAGES

[Launchpad PPA](https://launchpad.net/~paskal-07/+archive/ubuntu/softethervpn/+packages) maintained by [Dmitry Verkhoturov](https://github.com/paskal)

# HOW TO DOWNLOAD THE LATEST SOURCE CODE PACKAGE

Go to http://www.softether-download.com/ and you can find the latest
source-code package file in both .ZIP and .TAR.GZ format.

This is the easiest way to obtain the source code of SoftEther VPN.

# HOW TO GET THE LATEST SOURCE CODE TREE FOR DEVELOPERS

If you are an open-source developer, visit our GitHub repository:
https://github.com/SoftEtherVPN/SoftEtherVPN/

You can download the up-to-date source-code tree of SoftEther VPN
from GitHub. You may make your own fork project from our project.



##  Requirements

### 1. Debian/Ubuntu

- gcc
- libncurses5-dev
- libreadline-dev
- make
- libssl-dev
- zlib1g-dev

### 2. Red Hat/CentOS
- gcc
- openssl-devel
- make
- ncurses-devel
- readline-devel
- zlib-devel

## Compile and install

The download and build instruction is following:
 
```sh
$ git clone https://github.com/SoftEtherVPN/SoftEtherVPN.git
$ cd SoftEtherVPN
$ ./configure
$ make
$ make install
```

Please see src/BUILD_UNIX.md for more build instructions.

# TO CIRCUMVENT YOUR GOVERNMENT'S FIREWALL RESTRICTION

Because SoftEther VPN is overly strong tool to build a VPN tunnel,
some censorship governments want to block your access to the source code
of SoftEther VPN, by abusing their censorship firewalls.

To circumvent your censor's unjust restriction,
SoftEther VPN Project distributes the up-to-date source-code
on all the following open-source repositories:

  - GitHub
    https://github.com/SoftEtherVPN/SoftEtherVPN/

To fetch the source code from GitHub:
```
$ git clone https://github.com/SoftEtherVPN/SoftEtherVPN.git
```
We hope that you can reach one of the above URLs at least!


# SOURCE CODE CONTRIBUTION

Your contribution to SoftEther VPN Project is much appreciated.
Please send patches to us through GitHub.
Read the SoftEther VPN Patch Acceptance Policy in advance:
http://www.softether.org/5-download/src/9.patch


# DEAR SECURITY EXPERTS

If you find a bug or a security vulnerability please kindly inform us
about the problem immediately so that we can fix the security problem
to protect a lot of users around the world as soon as possible.

Our e-mail address for security reports is:
softether-vpn-security [at] softether.org

Please note that the above e-mail address is not a technical support
inquiry address. If you need technical assistance, please visit
http://www.softether.org/ and ask your question on the users forum.
