Blackhole
======

Blackhole is a proof-of-stake cryptocurrency with a focus on high performance, longevity and adoption services.

Blackhole is one of the first cryptocurrencies to use the Blake2s hashing algorithm. Blake2s is a high speed optimized cryptographic hashing algorithm used for proof-of-work and proof-of-stake hashes in Blackhole for performance with low load. This makes Blackhole ideally suited for dedicated staking devices and low-power/low-spec systems.

Originally dependent on the "libb2" library version of the Blake2s reference distribution, the blake2s reference implementation has now been directly baked in for ease of compilation across platforms.  Users no longer need to download and install libb2 separately.

If you are technical and you wish to compile libb2 specifically for your platform you may still do so (the configure script will auto-detect and enable special CPU features), you can modify your .pro or daemon makefile.* to remove the blake2 source and object file references, add -lb2 to your LIBS and paths to the includes and library (refer to the old commits).

Blackhole will feature a number of innovative solutions devised to foster the growth of the ecosystem.

SPECIFICATIONS
--------------
Type:                   PoW/Pos2.0 hybrid

PoW algorithm:          Blake2s

Difficulty retarget:    Every block

Block time:             120 seconds

POW Block reward:       240 BHC
POS rewards:			10% yearly

Coinbase maturity:      15 blocks

PoS start:              from the first block

Minimum PoS age:        1 hour

Maximum PoS age:        no max (PoS 2.0)

Max coins:              2400000000 Blackhole

Network info:

P2P port: 14442
RPC port: 14443

Testnet P2P port: 24442
Testnet RPC port: 24443
