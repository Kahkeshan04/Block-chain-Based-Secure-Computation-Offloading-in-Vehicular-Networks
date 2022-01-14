# Block-chain-Based-Secure-Computation-Offloading-in-Vehicular-Networks

## Introduction

- Vehicle Ad Hoc Network (VANET) is used for communication among vehicles & between vehicles and roadside infrastructure.
- VANET is a mobile ad hoc network (MANET) for vehicle environments in smart cities.
- Mobile applications that do not require latency will be offloaded to a resource-rich cloud server, while other time-sensitive applications will perform on edge servers to meet the rapid response service.
- Attackers can receive mobile data by threatening computing resources on cloud servers, which can cause privacy issues for VANET applications.
- To ensure the safety of mobile offloading, blockchain can be considered as a third-party system that does not require centralized trust management.
- The design of a peer-to-peer network is the core of the blockchain, where transaction information exists between multiple nodes and is not controlled by any single centralized entity.

## Existing System

- Mobile edge-cloud computation offloading (MECCO) has been regarded as a promising means to support delay-sensitive IoT applications.
- Offloading mobile tasks to the cloud is vulnerable to security risks due to malicious mobile devices (MDs).
- Unauthorized RBUs may achieve malicious access to utilize cloud services without central authorization.

  - ### Disadvantages

    - In the existing work, the system is not computation offloading, edge-cloud computing.
    - This system is less performance in which the system focuses on the ECCO system with the concept of access control and offloading on the blockchain network.

## Proposed System

- This system combines blockchain and DRL for the ECCO system in the VANET network, and jointly investigate access control and computation offloading.
- The system has designed a hierarchical architecture of controllable programming derived from SDN, which implements the dynamic orchestration of VANET security to achieve the communication of connected vehicles.
- To improve offloading security, we propose a trustworthy access control using blockchain, which protects clouds against illegal offloading behaviours.
- The system has proposed a trusted access control mechanism that can use smart contracts on the blockchain to effectively detect and prevent illegal offloading of VANET devices.
- We develop a novel deep reinforcement learning (DRL) algorithm by using an advanced deep Q-network.
- The extended offloading algorithm is based on DRL to attain the best offloading strategy for all vehicles, which should obey QoS requirements such as energy consumption and processing delay.

  - ### Advantages
    - The mobile vehicle initializes the demand task as an offloading transaction, and performs computation offloading to the edge-cloud server.
    - The blockchain control end processes the demand information and sends it to the storage pool for smart contract verification.
    - The main controller collects demands for mobile vehicles in the storage pool on a first come first served basis.
    - The main controller verifies the demand through a smart contract with a control strategy. When the demand is received, the reaction is returned to the mobile vehicle to offload the data.

## System Requirements

### Hardware

```
➢    Processor                      -   Pentium –IV
➢   RAM                              - 4 GB (min)
➢   Hard Disk                      -   20 GB
➢   Key Board                     -    Standard Windows Keyboard
➢   Mouse                            -    Two or Three Button Mouse
➢   Monitor                          -   SVGA
```

### Software

```
➢   Operating System 		-	Windows XP
➢   Coding Language		- 	Java/J2EE(JSP,Servlet)
➢   Front End			-	J2EE
➢   Back End			-	MySQL
```

## System Architecture

![Alt text](/readme.md/SystemArchitecture.png)

### Implementation

- **Source**:-The Source browses the required file, initializes nodes with Power, and uploads to the destination via Vehicular Network Router.
- **Vehicular Network Router**:-The Vehicular Network Router is responsible for forwarding the data file in the shortest distance to the destination. This the system can assign the power for the node and can view the node details with their power status and attack status.
- **Destination** :-In this module, if a malicious or less power node is found in the Vehicular Network Router then it never forwards to the Destination to filter the content and adds to the attacker profile.
- **Attacker**:-In this module, the malicious node or the node details can be identified by a threshold-based classifier is employed in the Attack Detection module to distinguish DoS attacks from legitimate power of each node. The Attacker can inject the less power and generates the node to drop from the corresponding block node.
