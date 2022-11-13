# RHCE Practice Environment

This is the practice environment I used to study for the RHCE exam for RHEL 8.
It should still be useful for other releases of RHEL, but YMMV.

## Requirements


## Usage


## Environment Architecture

The practice environment contains several worker nodes and a single control
node.

### Host: control.rhce.lab
OS: RHEL 8.6 - Workstation
vCPUs: 2
RAM: 4.29 GB
Disk: 40GB (thin)
Net: lab-net

### Host: node1.rhce.lab
OS: RHEL 8.6 - Server
vCPUs: 2
RAM: 4.29 GB
Disk: 40 GB (thin)
Net: lab-net

### Host: node2.rhce.lab
OS: RHEL 8.6 - Server
vCPUs: 2
RAM: 4.29 GB
Disk: 40 GB (thin)
Net: lab-net

### Host: node3.rhce.lab
OS: RHEL 8.6 - Server
vCPUs: 2
RAM: 4.29 GB
Disk: 40 GB (thin)
Net: lab-net

### Host: node4.rhce.lab
OS: RHEL 8.6 - Server
vCPUs: 2
RAM: 4.29 GB
Disk:
  - 40 GB (thin)
  - 1 GB
Net: lab-net

### Network: lab-net
Gateway: 192.168.100.1/24
DHCP Range: 192.168.100.10/192.168.100.20
