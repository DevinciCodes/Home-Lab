# Home Lab - Network Isolation & Virtualiation

## Overview
This project demonstrates the configuration of a secure and isolated virtualized network using UTM (or VirtualBox) on a macOS host. The lab includes two virtual machines (Windows and Linux) connected via a Host-Only Network, allowing controlled communication between the VMs while ensuring isolation from the host system. This setup simulates real-world network segmentation practices and provides a foundational environment for exploring network security and penetration testing concepts.

The project showcases my ability to configure virtualized environments, manage network settings, and implement isolation techniques essential for secure system design and testing.

<br>


## Tools & Technologies
- Virtualization Software: UTM (or VirtualBox)
- Operating Systems:
  - Windows VM
  - Linux VM (Ubuntu, Kali Linux, or other distributions)
- Networking Configuration: Host-Only Network with static IP addresses

<br>

## Key Features & Processes

### 1. Virtualized Network Configuration
- Set up two virtual machines:
  - Windows VM: Simulates a target or client machine.
  - Linux VM: Acts as a testing or monitoring system for cybersecurity activities.
- Assigned static IP addresses to both VMs for consistent communication within the virtual network.
  - Example IP addresses:
    - Windows VM: 192.168.1.101
    - Linux VM: 192.168.1.102
  <br>

### 2. Host-Only Network Mode
- Configured the VMs to communicate via a Host-Only Network:
  - Ensured that the VMs could communicate directly with each other.
  - Prevented the host machine (Mac) from accessing the VMs or vice versa, mimicking network segmentation used in secure environments.
 
  <br>

### 3. Validation of Network Isolation
- Tested network connectivity between the VMs using basic tools:
  - Ping command: Verified communication between the Windows and Linux VMs
  - Confirmed that the host machine (Mac) was unable to ping or interact with either VM, ensuring complete isolation.
 
  <br>

### 4. Practical Applications and Learning Outcomes
*System Administration*: 
- Learned to configure and manage virtual machines, assign static IPs, and troubleshoot network settings.

*Network Segmentation*:
- Gained hands-on experience in isolating virtual machines, replicating real-world practices for improving security and minimizing attack surfaces.
  
*Cybersecurity Fundamentals*:
- Built a foundational understanding of network isolation techniques, laying the groundwork for advanced labs involving penetration testing and network security assessments.


<br>

## Value to Organizations
*Secure System Design*: 
- Demonstrates an understanding of network segmentation and isolation, critical components of secure IT infrastructure.
  
*Hands-On Virtualization Skills*: 
- Highlights proficiency in setting up and managing virtualized environments, which are widely used in modern DevOps and cybersecurity workflows.
  
*Foundational Cybersecurity Knowledge*: 
- Establishes a solid base for further exploration of penetration testing, incident response, and secure network design.

<br>


## Conclusion
This home lab serves as a practical demonstration of my ability to design and implement secure, isolated virtual environments. It provides a platform for further exploration into advanced cybersecurity concepts while showcasing a solid understanding of system administration, networking, and virtualization.
