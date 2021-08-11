# Rhizom Networking Specification

## Table of Contents

- Network Interaction Types
    - Broadcast (network-oriented)
    - Unicast (peer-oriented)

## Network Interaction Types

### Broadcast

Broadcast is a messaging, pub/sub-like API which allows for sending and receiving 
messages in a more loosely coupled way, where senders, also called **publishers**, 
publish messages without targeting specific receivers, but rather some category or 
_topic_. Receivers, also called **subscribers**, will subscribe to these categories
or topics in order to receive the messages.

### Unicast


