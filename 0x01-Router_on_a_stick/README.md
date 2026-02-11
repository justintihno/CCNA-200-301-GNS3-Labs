** Router On A Stick

This lab covers setting up a router connected to a switch to handle inter VLAN routing.

Ping request is used to verify correct configuration.

Wireshark capture shows traffic destined to a different VLAN (outside its subnet) is directed to gateway ip.
ARP protocol is used to identify next hop IP addresses via a broadcast message

traffic destined to same VLAN doesn't go through the router.