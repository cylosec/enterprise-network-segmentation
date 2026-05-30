# VLAN Assessment

## Objective

As part of a network discovery and assessment engagement, the Engineering Department's network 
was reviewed to identify logical user groups, critical systems, and opportunities for improved 
segmentation.

The goal of this assessment is to evaluate how VLAN segmentation can improve security, reduce 
broadcast traffic, and support future network administration and security initiatives.

## Proposed VLAN Scope

| VLAN ID | VLAN Name      | Purpose                                      | Subnet        |
| ------- | -------------- | -------------------------------------------- | ------------- |
| 10      | Faculty        | Faculty and instructional staff workstations | 10.10.10.0/24 |
| 20      | Administration | Department administration and office staff   | 10.10.20.0/24 |
| 30      | Student Labs   | Student computer labs and classroom systems  | 10.10.30.0/24 |
| 40      | Research       | Research equipment and project workstations  | 10.10.40.0/24 |
| 50      | Servers        | Department servers and shared services       | 10.10.50.0/24 |
| 60      | Guest          | Visitor and contractor network access        | 10.10.60.0/24 |
| 99      | IT Management  | Network management and administrative access | 10.10.99.0/24 |

## Assessment Notes

The proposed segmentation model separates faculty, administrative staff, student lab systems, 
research resources, department servers, guest access, and IT management traffic into dedicated 
VLANs.

This approach provides:

* Improved network organization
* Reduced broadcast domains
* Enhanced security through traffic separation
* Simplified troubleshooting
* A foundation for future access control policies and security monitoring

