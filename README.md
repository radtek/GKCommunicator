# GKCommunicator

[![Build Status](https://travis-ci.org/Serg-Norseman/GKCommunicator.svg?branch=master)](https://travis-ci.org/Serg-Norseman/GKCommunicator)
[![Build status](https://ci.appveyor.com/api/projects/status/h0u8iwr3kvy6o9x1?svg=true)](https://ci.appveyor.com/project/serg-norseman/gkcommunicator)
[![codecov.io](https://codecov.io/github/serg-norseman/gkcommunicator/coverage.svg?branch=master)](https://codecov.io/github/serg-norseman/gkcommunicator?branch=master)
[![BCH compliance](https://bettercodehub.com/edge/badge/Serg-Norseman/GKCommunicator?branch=master)](https://bettercodehub.com/)
[![CodeFactor](https://www.codefactor.io/repository/github/serg-norseman/gkcommunicator/badge)](https://www.codefactor.io/repository/github/serg-norseman/gkcommunicator)

This communication application is a sub-project of GEDKeeper (two part: application and plugin).
This is a distributed, decentralized, serverless, peer-to-peer (P2P) chat client. 
The distributed P2P core is based on the Kademlia DHT. Supported: IPv4 / IPv6, Mainline DHT, UDP / TCP. The network message protocol is Bencode.

Roadmap

- [x] DHT
- [x] STUN detection of public IP and NAT's type
- [x] UDP hole-punching and UPnP port's mapping
- [x] IPv4 and IPv6
- [x] Simple UDP chat
- [x] Database support (SQLite, LiteDB)
- [x] Formatting of history
- [x] Stabilize the chat and discovery of peers

- [ ] TCP
- [ ] Simple user�s profile
- [ ] Simple storage
- [ ] A simple bulletin board of investigations and search of kins (only in the implementation of the plugin)
- [ ] Mutual identity and signing of user profiles (trusted collocutors and unchecked network members)
- [ ] "Web of Trust" elements with PGP certificates
- [ ] Proxy
