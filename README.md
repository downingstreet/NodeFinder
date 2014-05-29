Network Discovery
=================

Machines discovery/mapping (over Wifi) and port scan (over 3G/Wifi) utility for Android devices.

Features
--------

-  Discover Machines on a LAN (connect/ping discovery, dns discovery)
-  TCP Port Scanner (connect() scan)
-  NIC vendor database
-  Export results to your sdcard in XML
-  Fast access to Wifi Settings
-  Adaptive scanning rate (slow start, then adaptive to network latency)


Todo
----

- Save all scan in DB, open previous scan, export previous scan, etc
- Settings: prevent phone from sleeping
- NMAP build script (ARM and other arch (using AOSP?))
- Add new info such as Hops (using MTR?)
- Support of other protocol: UDP, SCTP
- Send custom packets (shell codes, exploits, probes, ...)
- Nat Traversal
- Proxy (auto)support


