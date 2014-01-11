Notice: This fork is intended for people building the qt client on OSX utilizing homebrew

Build Instructions
---------------------
1. Install homebrew
2. brew install berkeley-db4 boost openssl miniupnpc qt qrencode
3. Clone this repo
4. Enter repo directory
5. "qmake"
6. "make"
7. Copy Securecoin-Qt.app into /Applications

Securecoin 1.0
====================

Copyright (c) 2009-2013 Bitcoin Developers 2013-2014 SecureCoin Developers

Distributed under the MIT/X11 software license, see the accompanying
file COPYING or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](http://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), UPnP software written by Thomas Bernard and
sphlib 3.0 by Thomas Pornin.


Intro
---------------------
Securecoin is a free open source peer-to-peer electronic cash system that is
completely decentralized, without the need for a central server or trusted
parties.  Users hold the crypto keys to their own money and transact directly
with each other, with the help of a P2P network to check for double-spending. It is secured by six different algorithms and its CPU only mining is another security strength. 


Setup
---------------------
You need the Qt4 run-time libraries to run Bitcoin-Qt. On Debian or Ubuntu:
	`sudo apt-get install libqtgui4`


Other Pages
---------------------
- [Unix Build Notes](build-unix.md)
- [OSX Build Notes](build-osx.md)
- [Windows Build Notes](build-msw.md)
- [Coding Guidelines](coding.md)
- [Release Process](release-process.md)
- [Release Notes](release-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Unit Tests](unit-tests.md)
- [Translation Process](translation_process.md)
