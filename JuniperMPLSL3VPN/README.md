## MPLS L3 VPN Configurations

This set of configurations will get you going in your lab for a basic L3-VPN setup with 3x Juniper vMXs and 2x Juniper vSRXs.

Configurations consist of:
- ISIS for the IGP (running L2 only)
- BGP fully meshed within the provider core in AS64500
- CEs also using private ASNs (64501 - 64502) 
- LDP in use for label transfer
- LLDP also in use for neighbor discovery

__Versions__
```bash
vMX:  18.3R1.9
vSRX: 15.1X49-D150.2
```

The configurations also contain slightly more than is required for the most basic L3 VPN lab. MQTT, gRPC and v6 tunneling are most definitely not required to get the topology up and online.

__Credentials__

```bash
Username: root
Password: Passw0rd
```
