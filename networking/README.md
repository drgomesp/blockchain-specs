# Rhizom Networking Specification

## Table of Contents

- Introduction
- Concepts
- Network Interaction Types
    - Broadcast (network-oriented)
    - Unicast (peer-oriented)
  
## Introduction

## Concepts

| Name              | Description                                                                                                                                                                             |
|-------------------|----------------------------------------------------------------------------------------------------
| **Node**          | A self-sufficient process that may store and process data as well as communicate with other nodes.  
| **Peer**          | Nodes that know each other and establish communication are _peers_ to each other.                    
| **Protocol**      | A set or system of rules that allows for communication and information exchange within a network.   
| **Broadcast**     | A type of network interaction that allows for loosely-coupled message based communication.          
| **Unicast**       | A type of peer interaction that allows for a request/response style of communication.               


## Network Interaction Types

### Broadcast

Broadcast is a messaging, pub/sub-like API which allows for sending and receiving 
messages in a more loosely-coupled way, where senders, also called **publishers**, 
publish messages without targeting specific receivers, but rather some category or 
_topic_. Receivers, also called **subscribers**, will subscribe to these categories
or topics in order to receive the messages.

### Unicast

Unicast is the direct peer-to-peer interaction API, which provides operations based on
the Request/Response model. Requests will typically be blocking and callers will be
expecting a response over the same channel, but those details are hidden from them.


