![Maven Central](https://img.shields.io/maven-central/v/com.slytechs.jnet.protocol/protocol-pack-sdk)

# Protocol Pack SDK
Several Java modules containing network protocol specific APIs.

# Overview
Protocol packs are a collection of network protocol definitions and APIs, specific to a network protocol family. 

For example `protocol-pack-web` contains WEB traffic specific protocols, processors, dissectors, reassemblers, and many more services such as protocol constants, tables, lookup functions and so on.

You first need to include the `protocol-pack-api` module which contains numerous base API classes and interfaces for protocol management and packet dissection. It is a dependency for every other protocol pack in the protocol pack SDK.

# Protocol Packs
The following protocol packs are available now on Maven Central repository

* ![Maven Central](https://img.shields.io/maven-central/v/com.slytechs.jnet.protocol/protocol-pack-api?label=protocol-pack-api) - common protoocl API required by all other modules
* ![Maven Central](https://img.shields.io/maven-central/v/com.slytechs.jnet.protocol/protocol-pack-web?label=protocol-pack-web) - WEB related family of protocols including HTTP, HTML, QUIC and many more definitions

## Future Protocol Packs
These protocol packs are comming soon and are currently under active development.

* `protocol-pack-telco` - Telecommunication related protocols
* `protocol-pack-telco-lte` - LTE related protocols
* `protocol-pack-database` - Database related protocols such as MySQL, Oracle, etc...
* `protocol-pack-voice-video` - Various streaming protocols and numerous codes
* `protocol-pack-microsoft` - Microsoft related protocols such as IPX, SMB, etc..
