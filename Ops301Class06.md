#  Network Address Translation

What is the main purpose for implementing NAT on a network?

The main purpose of implementing NAT on a network is to conserve IPv4 addresses by allowing multiple devices within a private network to share a single public IP address. Additionally, NAT provides security by hiding internal IP addresses from external networks and enhances privacy by masking these addresses.

At what layer of the OSI model does NAT happen?

NAT operates at the network layer (Layer 3) of the OSI model. It modifies IP address information in the packet headers as packets traverse between the private network and the public internet.

What happens to packets when NAT runs out of addresses in the pool of available IPs?

When NAT runs out of addresses in the pool of available IPs, it cannot assign additional unique public IP addresses to new devices within the private network. This may result in devices being unable to access the internet until additional IP addresses are obtained.

What disadvantage does using NAT pose for routers?

One disadvantage of using NAT for routers is the complexity and overhead it introduces, particularly in larger networks. NAT requires maintaining translation tables to map internal private IP addresses to external public IP addresses, which consumes memory and processing resources on the router. Additionally, NAT can complicate certain networking tasks such as peer-to-peer applications or virtual private networks (VPNs) that rely on direct IP connectivity.

## Things I want to know more about

N/A

### Sources

https://www.geeksforgeeks.org/network-address-translation-nat/