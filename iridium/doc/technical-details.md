Iridium [IRI] Technical Details
===================================

This document outlines the technical implementation details for Iridium. It should be of use to advanced users and developers.

Specifications
--------------

* 42 million coins in total
* 2 minute average block time
* 100 coins per block
* Block reward halves 
* Retargets difficulty using DarkGravityWave
* x11 ASIC-resistant Proof-of-Work algorithm

Port numbers
------------

The following port numbers are used by Iridium.

* P2P uses port 9816
* RPC uses port 9817 

Message start string
--------------------

The message start string used by Iridium is:

```
0xfe, 0xc2, 0xb3, 0xee
```
