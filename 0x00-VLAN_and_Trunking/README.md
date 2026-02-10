*

This lab covers creating VLANs, assigning access ports, configuring trunk ports, and basic verification.

* Verification Commands
    show vlan brief                     see if ports are in correct VLAN
    show interfaces trunk                trunk up? allowed VLANs correct? active VLAN list?
    show interfaces Gi0/2 switchport    operational mode trunk? trunking VLANs?
    show mac address-table              see PC MACs learned in correct VLAN column

Performed packet capture to verify.
no iner-vlan routing done hence PC1 not reaching PC2 eventhough gateway is set.