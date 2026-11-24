# network-vision
Visualising networking in Google Cloud


Why is it so damn difficult to understand networking?

## The simulation

Interactive simulation of Google Cloud networking. Open `index.html` in a browser. It is a single file; the only external request is the Roboto web font, which falls back to the system font offline.

Views:
1. **Backbone**: regions/zones, edge PoPs, GFE, Cloud CDN, GGC, subsea cables, Premium vs Standard tier, zonal vs regional replication.
2. **Hybrid connectivity**: Dedicated/Partner/Cross-Cloud Interconnect, HA VPN, Direct/Carrier Peering, failover.
3. **VPC overlay**: global VPC, regional subnets, route table (LPM), NAT, PGA, IAP, routing mode, physical lens.
4. **Addressing**: CIDR bits, GCP's 4 reserved addresses, overlap check, special ranges.
5. **Firewalls**: hierarchical → VPC → network policies → implied, evaluated packet by packet.
6. **Projects & Shared VPC**: host/service projects, networkUser IAM.
7. **Peering & beyond**: non-transitive peering, NCC, PSA (Cloud SQL), PSC.

Click anything for an explanation, Tanenbaum reference, and corrections to the compiled notes. Each view lists its sources.
