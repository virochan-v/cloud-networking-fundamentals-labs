# Cloud Networking Fundamentals Labs

This repository contains hands-on networking experiments designed to explore core networking concepts that form the foundation of modern cloud infrastructure platforms such as Microsoft Azure.

The objective of these labs is to understand how networking components interact across different layers to enable communication between systems and services.

---

## Repository Structure

The repository is organized into individual lab experiments, each focusing on a specific networking concept.

```
cloud-networking-fundamentals-labs
│
├── README.md
│
├── assets
│   ├── routed-network-topology.png
│   ├── routed-network-ping-validation.png
│   ├── dns-web-topology.png
│   └── dns-web-browser-validation.png
│
└── labs
    ├── routed-network-connectivity
    │   └── lab-overview.md
    │
    └── dns-and-web-service-simulation
        └── lab-overview.md
```

---

## Lab Experiments

### 1. Routed Network Connectivity

This experiment demonstrates how devices located in separate subnets communicate through a router acting as a gateway.

Key concepts explored:

- Subnet communication
- Default gateway configuration
- Router-based packet forwarding
- Connectivity verification using ICMP ping

Documentation:

`labs/routed-network-connectivity/lab-overview.md`

---

### 2. DNS and Web Service Simulation

This experiment demonstrates how users access a web service using a domain name instead of a numerical IP address.

Key concepts explored:

- DNS name resolution
- Domain-to-IP mapping using DNS records
- HTTP web service hosting
- End-to-end communication flow from DNS resolution to web service delivery

Documentation:

`labs/dns-and-web-service-simulation/lab-overview.md`

---

## Tools Used

- Cisco Packet Tracer
- Networking protocols: ICMP, DNS, HTTP

---

## Learning Outcomes

Through these labs, the following networking concepts were reinforced:

- Inter-network communication across subnets
- Routing and gateway configuration
- Domain name resolution using DNS
- Web service access using HTTP
- Interaction between networking and application layers

---

## Relevance to Cloud Computing

Networking fundamentals are critical when working with modern cloud platforms such as Microsoft Azure. Concepts such as routing, DNS resolution, and service access directly relate to cloud networking components like virtual networks, gateways, load balancers, and managed DNS services.

Understanding these foundational principles helps build a strong base for designing and operating cloud-based systems.