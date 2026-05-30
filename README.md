## Enterprise Network Segmentation Lab

## Overview

In a real-world IT or security role, you're rarely handed a blank slate and told to design a network from scratch. 
More often, you have to step into an existing environment, figure out how it actually works, and identify where 
the risks are hiding.

That is exactly how I approached this project.

This lab is a simulated network discovery and segmentation assessment of a university engineering department. 
Instead of just jumping into a tutorial, I wanted to treat this like a true infrastructure audit. My goal was 
to map out the department's existing assets, find the critical boundaries where traffic needs to be locked down, 
and build out a rock-solid VLAN and subnetting strategy based on real industry standards.

## Why This Matters to Me

I built this project to bridge the gap between basic networking concepts and hands-on infrastructure security. For me, 
it’s about understanding the *why* behind network architecture. By documenting requirements, defining logical network 
boundaries, and validating traffic flow, I’m sharpening practical skills in network administration and security 
analysis—ensuring that an environment is not only manageable but secure from the ground up.

---

## Assessment Scope

The following network segments were identified during the assessment:

| VLAN | Department     |
| ---- | -------------- |
| 10   | Faculty        |
| 20   | Administration |
| 30   | Student Labs   |
| 40   | Research       |
| 50   | Servers        |
| 60   | Guest          |
| 99   | IT Management  |

---

## Technologies

* Cisco Packet Tracer
* VLAN Segmentation
* IPv4 Subnetting
* Inter-VLAN Routing
* 802.1Q Trunking
* Access Control Planning
* Network Documentation

---

## Project Objectives

* Document network resources and user groups
* Evaluate segmentation requirements
* Develop a VLAN strategy
* Create subnetting plans
* Validate connectivity between segments
* Assess opportunities for future security controls

---

## Repository Structure

```text
docs/            Project documentation
packet-tracer/   Packet Tracer topology files
diagrams/        Network diagrams and VLAN maps
configs/         Router and switch configurations
screenshots/     Configuration and testing evidence
reports/         Assessment findings and recommendations
```

---

## Future Enhancements

* Access Control Lists (ACLs)
* DHCP Services
* Redundant Switching
* pfSense Firewall Integration
* Active Directory Services
* Security Monitoring and Logging
* Wazuh Integration
