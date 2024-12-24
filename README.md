# Network-Packet-Analysis using Wireshark

## IP Address Classes
### Class A 
- These are assigned to networks with very large number of hosts. The higher oder bit is always set to zero.
- The adddress ranges from 1.0.0.0 to 126.0.0.0/8 and allows 126 networks and 16,777,214 hosts per network.
- 0.0.0.1 to 0.255.255.255 are not valid host addresses. 127.0.0.0/8 is reserved as loopback address and 127.0.0.1 to 127.255.255.255 are not valid host addresses.
### Class B
- These are assigned to medium to large sized networks. The default subnet mask is /16.
- The address ranges from 128.0.0.0 to 191.255.0.0/16 and allows 16,384 networks and 65,534 hosts per network.
### Class C
- These are assigneed for small networks. The default subnet mask is /24.
- The address ranges from 192.0.0.0 to 223.255.255.0/24 and allows for 2,097,152 networks and 254 hosts per network.
### Class D
- The range is from 224.0.0.0 to 239.255.255.255 and are reserved only for IP multicast addresses.
- These are not allocated to hosts and there is no default subnet mask.
### Class E
- The range is from 240.0.0.0 to 255.255.255.255 and are classiifed as experimental and reserved for future use.
- Similarly to Class D, these are not allocated to hosts and no default subnet mask.
- 255.255.255.255 is the broadcast address.

## Subnetting
