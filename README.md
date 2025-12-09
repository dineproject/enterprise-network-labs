# Enterprise Network Labs

Real-world network scenarios on Proxmox with Cisco IOS. Learn by solving business problems, not isolated exercises.

## Quick Start

```bash
git clone https://github.com/dineproject/enterprise-network-labs.git
cd enterprise-network-labs
./scripts/setup-proxmox.sh
./scripts/create-templates.sh
cd scenarios/01-startup-network && ./deploy.sh
```

See [Setup Guide](docs/setup.md) for details.

## Scenarios

| #   | Name              | What You'll Build                    |
| --- | ----------------- | ------------------------------------ |
| 01  | Startup Network   | VLANs, DHCP, NAT for growing company |
| 02  | Branch VPN        | Site-to-site IPSec tunnel            |
| 03  | E-commerce DMZ    | Secure web server with ACLs          |
| 04  | Dual ISP BGP      | Internet redundancy with failover    |
| 05  | Campus Redundancy | STP, EtherChannel, HSRP              |
| 06  | Company Merger    | Integrate networks with IP conflicts |
| 07  | Multi-Site OSPF   | OSPF multi-area design               |
| 08  | Guest WiFi        | Isolated guest network               |
| 09  | Monitoring        | SNMP, Syslog, NetFlow                |
| 10  | Full Enterprise   | Complete production infrastructure   |
