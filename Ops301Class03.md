# Readings: Network Segmentation

What is CIDR notation? a CIDR block?

Is a method used to represent ranges of IP addresses. It allows for more efficient allocation of IP addresses by specifying a network address and a suffix indicating the number of bits used for the network portion of the address.

A CIDR block is essentially a range of IP addresses represented in CIDR notation, consisting of a network address followed by a slash and a number representing the prefix length 

How many octets are found in an IPv4 address?

4 octets

Setting binary aside and using the decimal system, what is the range of numbers found in an octet?

0 to 255 

What does the final digit after the “/” represent in an IPv4 address?

It represents the prefix length or subnet mask.

How many IP addresses are in the CIDR block 10.0.0.0/24?

256

In your own words, describe network segmentation.

 Dividing a computer network into smaller, more manageable parts called segments.

Network segmentation isn’t important as long as the network is using a well configured firewall. Do you agree? Why or why not?

No, a firewall is necessary but not enough. We need additional layers to prevent threat actors from compromising an entire network, this is where segmentation comes in by diversifying the assets and adding aditional layers that can act as roadblocks for bad actors.

What is a screened subnet?

 Is a network segment that acts as an intermediary zone between the internal secure network and the untrusted external network, typically the internet.

Cameras, ID card scanners, locked doors and biometrics are just a few examples of what type of security?

Physical security

## Things I want to know more about
N/A

### Sources

https://medium.com/@ethicalentrepreneur/cidr-block-notation-explained-in-2-minutes-1010ec0dbc15
https://www.comptia.org/blog/security-awareness-training-network-segmentation
