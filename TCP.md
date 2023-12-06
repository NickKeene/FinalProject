# Ten Key Points of TCP

### Connection-Oriented Protocol:
* TCP is a connection-oriented protocol that creates a trustworthy and dedicated communication link between two devices.

### Three-Way Handshake:
* A three-way handshake happens before data exchange: SYN (synchronize), SYN-ACK (synchronize-acknowledge), and ACK (acknowledge). This guarantees that both parties are prepared to communicate.

### Reliable Data Transfer:
* TCP ensures reliable delivery of data by using acknowledgments. The sender receives acknowledgments from the receiver, and if a packet is not acknowledged, it is retransmitted.

### Flow Control:
* TCP uses flow control mechanisms to manage the rate of data transmission between sender and receiver, preventing overwhelming the receiving end.

### Windowing:
* Windowing enables the sender to send numerous packets before getting notifications, improving data transfer efficiency.

### Segmentation:
* For transmission, data is divided into smaller chunks. Each segment is assigned a sequence number, which allows the receiver to reassemble the data in the proper order.

### Checksum:
* To detect mistakes during transmission, TCP adds a checksum in each segment. If an error is identified, the segment is discarded and retransmitted.

### Port Numbers:
* TCP uses port numbers to differentiate between different services on a device. Source and destination port numbers aid in the routing of data to the appropriate application.

### Full Duplex Communication:
* TCP supports full-duplex communication, which means that data can be delivered and received by both communicating devices at the same time.

### Connection Termination:
* To end a TCP connection, a four-way handshake is performed. It uses FIN (finish) and ACK (acknowledge) signals to gracefully close the connection.


### Return Back To Introduction
Use this [link](README.md) to return back
