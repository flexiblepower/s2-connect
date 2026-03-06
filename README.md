# S2 Connect

S2 Connect is a protocol specification enabling communication between an Energy Management System (EMS) and an Energy Smart Appliance (ESA) based on the S2 (EN50491‑12‑2) standard. It defines how devices discover, pair, and unpair across local, cloud, and hybrid environments.

This repository contains the OpenAPI specification files for the pairing process and connection initiation process of S2 Connect. **These files merely support the S2 Connect specification. Anyone interested in developing an S2 Connect implementation should use the specification as starting point.**

## The S2 standard
S2 Connect is a solution that builds upon two other specification projects. Note that each of these projects could be used without 

* **S2 Standard**: The S2 standard, formally known as the European standard EN50491-12-2, defines the data models and interactions between a CEM and RM for energy management.
* **S2 JSON**: Translates the S2 standard into formal JSON schema's that can be exchanged between CEM and RM as messages.
* **S2 Connect**: Protocol specification for discovering, pairing and starting a communication channel for exchanging S2 JSON messages.

## Documentation
Documentation, for all S2 specification projects can be found on [docs.s2standard.org](https://docs.s2standard.org/).

# Status
The specification is still under development, and currently in beta.

## Discussion
You are welcome to join the discussion on the [S2 Discord server](https://discord.com/invite/NyFMEPmuDw)!

## License
This project is licensed under the Apache License 2.0.
See the LICENSE file for details.

