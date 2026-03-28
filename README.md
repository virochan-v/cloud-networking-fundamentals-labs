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
│   ├── dns-web-browser-validation.png
│   ├── dns-connectivity-validation.png
│   ├── acl-network-topology.png
│   ├── acl-router-configuration.png
│   ├── acl-blocked-host-test.png
│   ├── acl-web-access-success.png
│   ├── dhcp-network-topology.png
│   ├── dhcp-router-configuration.png
│   ├── dhcp-ip-assignment.png
│   └── dhcp-connectivity-test.png
│
└── labs
    ├── routed-network-connectivity
    │   └── lab-overview.md
│
    ├── dns-and-web-service-simulation
    │   └── lab-overview.md
│
    ├── access-control-list-filtering
    │   └── lab-overview.md
│
    └── dhcp-dynamic-ip-assignment
        └── lab-overview.md
```

---

# Lab Experiments

## 1. Routed Network Connectivity

This experiment demonstrates how devices located in separate subnets communicate through a router acting as a gateway.

### Key Concepts Explored

- Subnet communication
- Default gateway configuration
- Router-based packet forwarding
- Connectivity verification using ICMP ping

Documentation:

```
labs/routed-network-connectivity/lab-overview.md
```

---

## 2. DNS and Web Service Simulation

This experiment demonstrates how users access a web service using a domain name instead of a numerical IP address.

### Key Concepts Explored

- DNS name resolution
- Domain-to-IP mapping using DNS records
- HTTP web service hosting
- End-to-end communication flow from DNS resolution to web service delivery

Documentation:

```
labs/dns-and-web-service-simulation/lab-overview.md
```

---

## 3. Access Control List (ACL) Traffic Filtering

This experiment demonstrates how routers enforce network security policies using Standard Access Control Lists.

The router is configured to:

- Allow access to the web server for authorized hosts
- Block access for unauthorized hosts

### Key Concepts Explored

- Standard Access Control Lists
- Source IP based traffic filtering
- Router interface security policies
- Controlled access to network services

Documentation:

```
labs/access-control-list-filtering/lab-overview.md
```

---

## 4. DHCP Dynamic IP Assignment

This experiment demonstrates how a router can act as a DHCP server to automatically assign IP addresses to client devices.

### Key Concepts Explored

- Dynamic Host Configuration Protocol (DHCP)
- Automatic IP address allocation
- Default gateway assignment
- DNS server configuration
- Network automation

Documentation:

```
labs/dhcp-dynamic-ip-assignment/lab-overview.md
```

---

# Tools Used

- Cisco Packet Tracer
- Networking protocols: ICMP, DNS, HTTP, DHCP

---

# Learning Outcomes

Through these labs, the following networking concepts were reinforced:

- Inter-network communication across subnets
- Routing and gateway configuration
- Domain name resolution using DNS
- Web service access using HTTP
- Network traffic filtering using Access Control Lists
- Dynamic IP allocation using DHCP
- Interaction between networking and application layers

---

# Relevance to Cloud Computing

Networking fundamentals are critical when working with modern cloud platforms such as Microsoft Azure.

Concepts demonstrated in these labs relate directly to cloud networking components such as:

- Virtual Networks
- Subnet segmentation
- Network Security Groups
- Application access control
- Managed DNS services
- Dynamic IP allocation (DHCP in cloud environments)
- Service connectivity across network boundaries

Understanding these foundational principles helps build a strong base for designing, deploying, and operating cloud-based systems.