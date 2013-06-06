# webinos-localConnection

Generic Peer/device discovery interfaces.  The aims at providing a generic interface that isolate differences of 
the low level discovery schemes. 

## Functionalities

It provides APIs for advertising device existence and finding local devices A set of APIs that enable device and service discovery over multiple discovery protocols. Supported discovery methods:

[1] Zeroconf using mdns for discovery across android, Linux, Windows and Mac OS.

[2] Placeholders for Bluetooth, UPnP and other discovery method.


## Prerequisites

### Ubuntu users -
Please check on ./patches/README and apply patches

### Mac OS -¶

Download and install mDNSResponder
http://opensource.apple.com/tarballs/mDNSResponder/

## TODO LIST

[1] Merge Bluetooth SDP code from Webinos mainstream over

[2] Modularize offline discovery-authentication-connection code in Webinos mainstream codebase and move over here
