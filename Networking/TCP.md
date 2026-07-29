# TCP

Transmission Control Protocol (TCP) provides reliable communication between devices.

TCP guarantees:

- Ordered delivery
- Error checking
- Reliable transmission

---

## Three-Way Handshake

Step 1

Client

SYN

↓

Step 2

Server

SYN-ACK

↓

Step 3

Client

ACK

Connection Established

---

## TCP Header

- Source Port
- Destination Port
- Sequence Number
- Acknowledgement Number
- Flags
- Checksum
- Window Size

---

## Common Flags

SYN

Start connection.

ACK

Acknowledges received packets.

FIN

Gracefully closes a connection.

RST

Immediately resets a connection.
