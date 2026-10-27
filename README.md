# EWB-AWS-VPC-Peering
# AWS VPC Peering Project

## EWB Courses — AWS Cloud Computing Internship

### Project Overview
This project demonstrates VPC peering between two Amazon Virtual Private Clouds (VPCs) in the AWS Mumbai region (`ap-south-1`).

### Architecture
- **VPC A:** `10.10.0.0/16`
- **VPC B:** `10.20.0.0/16`
- **VPC Peering:** `ewb-a-b-peer`
- **App-A Private IP:** `10.10.2.10`
- **App-B Private IP:** `10.20.1.10`
- **Bastion Host:** `10.10.1.10`

### Implementation
- Created two VPCs with non-overlapping CIDR blocks.
- Configured a VPC peering connection.
- Added routes between the VPCs.
- Associated private subnets with their route tables.
- Configured security group rules for SSH and ICMP traffic.
- Tested private connectivity between application instances.

### Connectivity Test
A successful ping test from App-A (`10.10.2.10`) to App-B (`10.20.1.10`) recorded **4 packets received with 0% packet loss**.

### Project Report
See the PDF report uploaded in this repository for configuration screenshots and supporting evidence.

### Technologies
Amazon VPC · EC2 · VPC Peering · Route Tables · Security Groups · Linux

**Region:** Asia Pacific (Mumbai) — `ap-south-1`
