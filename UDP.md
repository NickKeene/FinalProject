# Ten Key Points of UDP

### Connectionless Protocol:
* UDP is a connectionless protocol, which means it does not require a dedicated connection to transfer data. Each packet is handled separately.

### No Handshake:

* UDP, unlike TCP, does not require a three-way handshake. There is no connection establishment or termination; data is transferred without prior discussion.

### Unreliable Delivery:
* UDP does not ensure packet delivery. It's a "best-effort" protocol, which means it sends packets without checking to see if they arrive at their destination.

### No Flow Control:
* TCP's flow control techniques are absent from UDP. This indicates there is no system in place to govern the rate of data transmission, which may result in packet loss.

### No Segmentation:
* Without segmentation, data is delivered as datagrams. If a message is too large to fit in a single packet, the application layer must handle it.

### No Acknowledgments:
* UDP does not employ any acknowledgment or retransmission techniques. If a packet is dropped during transmission, it is not resent.

### Low Overhead:
* UDP has less overhead compared to TCP since it lacks the additional mechanisms for reliability and ordering. This makes it faster but less reliable.

### Broadcasts and Multicasts:
* UDP provides broadcasting and multicasting, allowing a single packet to be transmitted to several destinations concurrently.

### Simple Header Structure:
* UDP headers are simple, having only the source and destination port numbers as well as a length field. This ease of use decreases processing overhead.

### Used for Real-Time Applications:
* UDP is widely used in real-time applications requiring minimal latency, such as online gaming, voice over IP (VoIP), and streaming media.

### Return Back To Introduction
Use this [link](README.md) to return back
