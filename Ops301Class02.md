# Readings: Network scanning with NMAP

What is a port? Describe it with an analogy that would help a family member understand.

A port is a virtual location where networking communication starts and ends (in a nutshell). For a more in-depth explanation, we need to establish a little background information. 

“Think of ports as hatches on a ship and each has leads to a different compartment where sailors go to work, but each sailor has a very specific and different job.”

What does a port scanner send to a port to check the status?

A port scanner sends a TCP or UDP network packet and asks the port about their current status.

When a port scanner sends a request to connect, what are the three possible responses? Describe them.

1.	Open, accepted.
2.	Closed, not listening.
3.	Filtered, Dropped, Blocked.

What is the difference between TCP and UDP?

TCP sends each packet in order, complete with error checking, verification, and a 3-way handshake to confirm each packet is successful. UDP doesn’t have any error checking but tends to be faster. Live streaming and online video games often use UDP for this reason. UDP is a connectionless protocol, so programs that use UDP just send the data – and if you miss a packet, you will never get it again.

List and describe the ports used for the following:

•	Telnet (Port 23): Telnet is a protocol used for remotely accessing and managing devices over a network. It provides a text-based interface, but it's not secure because it transmits data in plain text, including passwords.
•	SSH (Secure Shell) (Port 22): SSH is a secure network protocol used for secure remote access and control over a network. It provides encrypted communication between two devices, making it much more secure than Telnet.
•	DNS (Domain Name System) (Port 53): DNS is a protocol used for translating domain names into IP addresses and vice versa. It operates on both UDP (User Datagram Protocol) and TCP (Transmission Control Protocol), with port 53 being the default port for DNS queries.
•	SMTP (Simple Mail Transfer Protocol) (Port 25): SMTP is a protocol used for sending email messages between servers. It is responsible for the transmission of outgoing mail from a sender to a mail server.
•	HTTP (Hypertext Transfer Protocol) (Port 80): HTTP is a protocol used for transmitting and receiving hypertext documents on the World Wide Web. It is the foundation of data communication for the World Wide Web.
•	HTTPS (Hypertext Transfer Protocol Secure) (Port 443): HTTPS is a secure version of HTTP that uses encryption to secure the communication between a web browser and a web server. It's commonly used for secure online transactions, such as online banking and shopping.
•	RDP (Remote Desktop Protocol) (Port 3389): RDP is a protocol developed by Microsoft for remote access to Windows-based systems. It allows users to connect to and control a remote desktop or server over a network connection.
•	Ping : N/A

## Things I want to know more about
N/A

### Sources

https://www.varonis.com/blog/port-scanning-techniques/

https://www.professormesser.com/network-plus/n10-008/n10-008-video/common-ports-n10-008/
