# Changelog

This file lists notable changes that have been made to the application on each release.
Releases are tracked and referred to using git tags.

## v0.29 - (next release)
- set target SDK to 28

## v0.28 - 2019-09-15
- fix daemon startup on Android 10
- notify user of missing VPN permission
- update Kotlin to 1.3.50

## v0.27 - 2019-06-14
- fix R8 optimisation that made the app unable to load its libraries

## v0.26 - 2019-06-13
- make tinc automatic reconnection on network change optional with new configuration key (`ReconnectOnNetworkChange`)
- update LibreSSL to 2.9.2
- update Kotlin to 1.3.31
- update Gradle to 3.4.1

## v0.25 - 2019-03-25
- implement a workaround for broken file permissions on Android-x86
- kill any remnant tinc daemon when starting a new connection
- minor UI improvements

## v0.24 - 2019-02-18
- update tinc to latest snapshot (1.1-017a7fb), fixing UDP spam
- update LibreSSL to 2.8.3
- new app icon

## v0.23 - 2018-10-08
- update tinc to 1.1pre17 (security update: CVE-2018-16737, CVE-2018-16738, CVE-2018-16758)

## v0.22 - 2018-09-27
- improve stability

## v0.21 - 2018-09-26
- force re-connection on network change
- improve stability

## v0.20 - 2018-09-09
- update existing translations
- improve assisted error reporting
- minor UI improvements

## v0.19 - 2018-08-22
- add a subnet list view
- show node reachability status
- other minor UI improvements
- embed a QR-code scanner

## v0.18 - 2018-08-07
- add support for always-on VPN
- error handling and stability improvements
- minor UI and branding improvements

## v0.17 - 2018-06-25
- update tinc to 1.1pre16
- update LibreSSL to 2.7.4
- update BCPKIX lib to 1.59

## v0.16 - 2018-06-11
- better QR-code integration
- update LibreSSL to 2.7.3
- reduce APK size

## v0.15 - 2018-05-26
- drop support for the deprecated armeabi architecture
- better error handling and reporting
- minor UI improvements

## v0.14 - 2018-04-23
- update LibreSSL to 2.7.2
- minor UI improvements

## v0.13 - 2018-03-31
- add assisted bug report feature
- minor UI improvements

## v0.12 - 2018-03-14
- better error handling
- minor UI improvements

## v0.11 - 2018-03-04
- generate a sub network configuration file when bootstrapping
- add a log viewer screen
- fix private key encryption on release versions

## v0.10 - 2018-02-24
- better error reporting
- minor UI improvements

## v0.9 - 2018-02-16
- better daemon state handling and reporting
- minor UI improvements

## v0.8 - 2018-02-10
- add Chinese translation
- update tinc to latest pre-release (1.1pre15)
- update LibreSSL to 2.6.4
- minor UI improvements
- handle unavailable external storage

## v0.7 - 2017-09-07
- add support for private key encryption using a password
- minor UI improvements
- error handling and stability improvements

## v0.6 - 2017-08-24
- update tinc to latest snapshot (1.1-92fdabc)
- add an option to join a tinc network by scanning a QR-code
- minor UI improvements

## v0.5 - 2017-08-22
- improve stability
- do not request useless permissions

## v0.4 - 2017-08-18
- update tinc to latest snapshot (1.1-7c22391)
- expose intents to allow connection and disconnection from other apps
- minor UI improvements

## v0.3 - 2017-08-03
- update tinc to latest snapshot (1.1-acefa66)
- update LibreSSL to 2.5.5
- add a connection status screen
- add an option to join a tinc network via the UI
- make external calls asynchronous

## v0.2 - 2017-07-03
- add Norwegian Bokmål and Japanese translations
- add a list of confgured tinc networks in the UI
- remove support for the MIPS architecture
- remove support for alternate configuration path
- port to Kotlin

## v0.1-preview - 2017-05-05
- basic working proof-of-concept using a patched tinc 1.1pre15
