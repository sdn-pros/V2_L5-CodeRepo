
# Validate State Report

**Table of Contents:**

- [Validate State Report](validate-state-report)
  - [Test Results Summary](#test-results-summary)
  - [Failed Test Results Summary](#failed-test-results-summary)
  - [All Test Results](#all-test-results)

## Test Results Summary

### Summary Totals

| Total Tests | Total Tests Passed | Total Tests Failed |
| ----------- | ------------------ | ------------------ |
| 261 | 261 | 0 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| leaf1 |  49 | 49 | 0 | - |
| leaf2 |  49 | 49 | 0 | - |
| leaf3 |  47 | 47 | 0 | - |
| leaf4 |  47 | 47 | 0 | - |
| spine1 |  23 | 23 | 0 | - |
| spine2 |  23 | 23 | 0 | - |
| spine3 |  23 | 23 | 0 | - |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  7 | 7 | 0 |
| Interface State |  71 | 71 | 0 |
| LLDP Topology |  32 | 32 | 0 |
| MLAG |  4 | 4 | 0 |
| IP Reachability |  24 | 24 | 0 |
| BGP |  59 | 59 | 0 |
| Routing Table |  36 | 36 | 0 |
| Loopback0 Reachability |  28 | 28 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | leaf1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 2 | leaf2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 3 | leaf3 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 4 | leaf4 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 5 | spine1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 6 | spine2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 7 | spine3 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 8 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf2_Ethernet1 | PASS | - |
| 9 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf2_Ethernet2 | PASS | - |
| 10 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet3 | PASS | - |
| 11 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet3 | PASS | - |
| 12 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet3 | PASS | - |
| 13 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1_Ethernet1 | PASS | - |
| 14 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf1_Ethernet1 | PASS | - |
| 15 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf1_Ethernet2 | PASS | - |
| 16 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet4 | PASS | - |
| 17 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet4 | PASS | - |
| 18 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet4 | PASS | - |
| 19 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1_Ethernet2 | PASS | - |
| 20 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf4_Ethernet1 | PASS | - |
| 21 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf4_Ethernet2 | PASS | - |
| 22 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet5 | PASS | - |
| 23 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet5 | PASS | - |
| 24 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet5 | PASS | - |
| 25 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf3_Ethernet1 | PASS | - |
| 26 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf3_Ethernet2 | PASS | - |
| 27 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet6 | PASS | - |
| 28 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet6 | PASS | - |
| 29 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3_Ethernet6 | PASS | - |
| 30 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF1_Ethernet3 | PASS | - |
| 31 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF2_Ethernet3 | PASS | - |
| 32 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF3_Ethernet3 | PASS | - |
| 33 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_LEAF4_Ethernet3 | PASS | - |
| 34 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF1_Ethernet4 | PASS | - |
| 35 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF2_Ethernet4 | PASS | - |
| 36 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF3_Ethernet4 | PASS | - |
| 37 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_LEAF4_Ethernet4 | PASS | - |
| 38 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF1_Ethernet5 | PASS | - |
| 39 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF2_Ethernet5 | PASS | - |
| 40 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF3_Ethernet5 | PASS | - |
| 41 | spine3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_LEAF4_Ethernet5 | PASS | - |
| 42 | leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf2_Po1 | PASS | - |
| 43 | leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | PASS | - |
| 44 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf1_Po1 | PASS | - |
| 45 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel7 - host1_PortChannel host1 | PASS | - |
| 46 | leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf4_Po1 | PASS | - |
| 47 | leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf3_Po1 | PASS | - |
| 48 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 49 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 50 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 51 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 52 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 53 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 54 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 55 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 56 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 57 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 58 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 59 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 60 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 61 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 62 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 63 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 64 | leaf1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 65 | leaf2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 66 | leaf3 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 67 | leaf4 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 68 | leaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 69 | leaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 70 | leaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 71 | leaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 72 | leaf3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 73 | leaf3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 74 | leaf4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 75 | leaf4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 76 | spine1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 77 | spine2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 78 | spine3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 79 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf2_Ethernet1 | PASS | - |
| 80 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf2_Ethernet2 | PASS | - |
| 81 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet3 | PASS | - |
| 82 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet3 | PASS | - |
| 83 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet3 | PASS | - |
| 84 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf1_Ethernet1 | PASS | - |
| 85 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet2 | PASS | - |
| 86 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet4 | PASS | - |
| 87 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet4 | PASS | - |
| 88 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet4 | PASS | - |
| 89 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf4_Ethernet1 | PASS | - |
| 90 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf4_Ethernet2 | PASS | - |
| 91 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet5 | PASS | - |
| 92 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet5 | PASS | - |
| 93 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet5 | PASS | - |
| 94 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf3_Ethernet1 | PASS | - |
| 95 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf3_Ethernet2 | PASS | - |
| 96 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet6 | PASS | - |
| 97 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet6 | PASS | - |
| 98 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3_Ethernet6 | PASS | - |
| 99 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf1_Ethernet3 | PASS | - |
| 100 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf2_Ethernet3 | PASS | - |
| 101 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf3_Ethernet3 | PASS | - |
| 102 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: leaf4_Ethernet3 | PASS | - |
| 103 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf1_Ethernet4 | PASS | - |
| 104 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf2_Ethernet4 | PASS | - |
| 105 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf3_Ethernet4 | PASS | - |
| 106 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: leaf4_Ethernet4 | PASS | - |
| 107 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf1_Ethernet5 | PASS | - |
| 108 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf2_Ethernet5 | PASS | - |
| 109 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf3_Ethernet5 | PASS | - |
| 110 | spine3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: leaf4_Ethernet5 | PASS | - |
| 111 | leaf1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 112 | leaf2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 113 | leaf3 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 114 | leaf4 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 115 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet3 - Destination: spine1_Ethernet3 | PASS | - |
| 116 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet4 - Destination: spine2_Ethernet3 | PASS | - |
| 117 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet5 - Destination: spine3_Ethernet3 | PASS | - |
| 118 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet3 - Destination: spine1_Ethernet4 | PASS | - |
| 119 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet4 - Destination: spine2_Ethernet4 | PASS | - |
| 120 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet5 - Destination: spine3_Ethernet4 | PASS | - |
| 121 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet3 - Destination: spine1_Ethernet5 | PASS | - |
| 122 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet4 - Destination: spine2_Ethernet5 | PASS | - |
| 123 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet5 - Destination: spine3_Ethernet5 | PASS | - |
| 124 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet3 - Destination: spine1_Ethernet6 | PASS | - |
| 125 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet4 - Destination: spine2_Ethernet6 | PASS | - |
| 126 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet5 - Destination: spine3_Ethernet6 | PASS | - |
| 127 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet3 - Destination: leaf1_Ethernet3 | PASS | - |
| 128 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet4 - Destination: leaf2_Ethernet3 | PASS | - |
| 129 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet5 - Destination: leaf3_Ethernet3 | PASS | - |
| 130 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet6 - Destination: leaf4_Ethernet3 | PASS | - |
| 131 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet3 - Destination: leaf1_Ethernet4 | PASS | - |
| 132 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet4 - Destination: leaf2_Ethernet4 | PASS | - |
| 133 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet5 - Destination: leaf3_Ethernet4 | PASS | - |
| 134 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet6 - Destination: leaf4_Ethernet4 | PASS | - |
| 135 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet3 - Destination: leaf1_Ethernet5 | PASS | - |
| 136 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet4 - Destination: leaf2_Ethernet5 | PASS | - |
| 137 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet5 - Destination: leaf3_Ethernet5 | PASS | - |
| 138 | spine3 | IP Reachability | ip reachability test p2p links | Source: spine3_Ethernet6 - Destination: leaf4_Ethernet5 | PASS | - |
| 139 | leaf1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 140 | leaf2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 141 | leaf3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 142 | leaf4 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 143 | spine1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 144 | spine2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 145 | spine3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 146 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.1 | PASS | - |
| 147 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.0 | PASS | - |
| 148 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.2 | PASS | - |
| 149 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.4 | PASS | - |
| 150 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.0 | PASS | - |
| 151 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.6 | PASS | - |
| 152 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.8 | PASS | - |
| 153 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.10 | PASS | - |
| 154 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.5 | PASS | - |
| 155 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.12 | PASS | - |
| 156 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.14 | PASS | - |
| 157 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.16 | PASS | - |
| 158 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.4 | PASS | - |
| 159 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.18 | PASS | - |
| 160 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.20 | PASS | - |
| 161 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.22 | PASS | - |
| 162 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.1 | PASS | - |
| 163 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.7 | PASS | - |
| 164 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.13 | PASS | - |
| 165 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.19 | PASS | - |
| 166 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.3 | PASS | - |
| 167 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.9 | PASS | - |
| 168 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.15 | PASS | - |
| 169 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.21 | PASS | - |
| 170 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.5 | PASS | - |
| 171 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.11 | PASS | - |
| 172 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.17 | PASS | - |
| 173 | spine3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.23 | PASS | - |
| 174 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 175 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 176 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 177 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 178 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 179 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 180 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 181 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 182 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 183 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 184 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 185 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.13 | PASS | - |
| 186 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 187 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 188 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 189 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 190 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 191 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 192 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 193 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 194 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 195 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 196 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 197 | spine3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 198 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 199 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 200 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 201 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 202 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 203 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 204 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 205 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 206 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 207 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 208 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 209 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 210 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 211 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 212 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 213 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 214 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 215 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 216 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 217 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 218 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 219 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 220 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 221 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 222 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 223 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 224 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 225 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 226 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 227 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 228 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 229 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 230 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 231 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 232 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 233 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.13 | PASS | - |
| 234 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.1 | PASS | - |
| 235 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.2 | PASS | - |
| 236 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.3 | PASS | - |
| 237 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.4 | PASS | - |
| 238 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.11 | PASS | - |
| 239 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.12 | PASS | - |
| 240 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.13 | PASS | - |
| 241 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.1 | PASS | - |
| 242 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.2 | PASS | - |
| 243 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.3 | PASS | - |
| 244 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.4 | PASS | - |
| 245 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.11 | PASS | - |
| 246 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.12 | PASS | - |
| 247 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.13 | PASS | - |
| 248 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.1 | PASS | - |
| 249 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.2 | PASS | - |
| 250 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.3 | PASS | - |
| 251 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.4 | PASS | - |
| 252 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.11 | PASS | - |
| 253 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.12 | PASS | - |
| 254 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.13 | PASS | - |
| 255 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.1 | PASS | - |
| 256 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.2 | PASS | - |
| 257 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.3 | PASS | - |
| 258 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.4 | PASS | - |
| 259 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.11 | PASS | - |
| 260 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.12 | PASS | - |
| 261 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.13 | PASS | - |