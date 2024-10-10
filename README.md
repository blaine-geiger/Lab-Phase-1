# Home Lab Phase 1

## Define use and expectations of network
The design of the home lab will serve the purpose of providing an environment for experimentation, analysis, reinforcing knowledge, and learning new skills. The main areas of focus will be networking, data communications, and cybersecurity. Exploring these areas in depth in a controlled environment will provide a better understanding of these topics and hands-on experience with different hardware and software. This provides a setting where testing, performing simulated attacks, and exploring vulnerabilities can be done safely and ethically.

## Research network designs and configurations
There are many different home lab network designs and configurations that can be considered. However, with this being my first purpose-built lab for learning experiences, lower cost components will be desired. A dedicated firewall device, a router, and a managed switch were devices that I knew I wanted to include in my home lab. Regardless of other design considerations, these devices were essential.
My computing and processing needs could be fulfilled using various methods, each with their own benefits and disadvantages. Details of the different methods are listed in the table below.

<p align="center">
  <br/>
  <img src="https://imgur.com/pPOIJ4l.png" height="80%" width="80%" alt="Table"/><br /><br />
</p>

## Determine final physical network design and network device types
Based on my research of these possible designs, while considering cost, performance, flexibility, scalability, power consumption, and physical space, I have decided to use a single, but powerful, NUCbox for my computing and processing requirements. This will provide enough performance to meet my goals, while maintaining the opportunity to expand and increase scale if needed. This design may also be shifted into a hybrid design by adding and clustering additional NUCboxes later.

The final physical design of the home lab network will consist of a firewall, a managed switch, and a single PC with a virtualization environment, capable of running multiple simultaneous virtual machine (VM) instances. Virtualization software can optimize performance by dynamically allocating resources such as CPU, RAM, and storage. It will provide high flexibility with the ability to build and run custom VMs that meet the needs for exploring and testing specific scenarios.
  
The final physical network design is diagrammed in the figure below:

<p align="center">
  <br/>
  <img src="https://imgur.com/ck9dgGX.png" height="80%" width="80%" alt="Figure"/><br /><br />
</p>


## Research specific device manufacturers and models for purchasing
The physical components that will make up the final physical network design are a firewall, managed switch, and Mini PC. The following will provide insight into the specific manufacturers and devices that our home lab network will utilize.
### Firewall (Netgate SG – 1100) Cost: $210
<ul>
    <li><strong>Purpose-built pfSense firewall device</strong></li>
    <li><strong>Reputable manufacturer</strong></li>
    <li><strong>Compact form factor</strong></li>
    <li><strong>Powerful performance for size</strong></li>
    <li><strong>PfSense Plus software pre-installed</strong></li>
    <li><strong>Strong support and user community</strong></li>
    <li><strong>IP-Sec VPN</strong></li>
    <li><strong>VLAN</strong></li>
</ul>

### Managed Switch (NETGEAR 8-Port Gigabit Ethernet Plus Switch (GS108Ev3)) Cost: $45
<ul>
    <li><strong>Segmentation and performance capabilities</strong></li>
    <li><strong>SNMP can help track network performance and troubleshoot</strong></li>
    <li><strong>Port security with MAC address filtering</strong></li>
    <li><strong>Remote management through web interface</strong></li>
    <li><strong>8 ports allow scalability</strong></li>
    <li><strong>Compact design and cost effective</strong></li>
</ul>

### Mini-PC or NUCbox (GMKtec M5) Cost: $330
<ul>
    <li><strong>Powerful and compact</strong></li>
    <li><strong>AMD Ryzen 7 5700U processor, 4 cores/16 threads, 4.3 GHz, 32 GB RAM, 1 TB SSD</strong></li>
    <li><strong>Much more affordable than Intel-based NUCbox with similar specifications</strong></li>
    <li><strong>Low power consumption</strong></li>
    <li><strong>Expandability to upgrade RAM and storage</strong></li>
    <li><strong>Flexibility to use as a virtualization environment, network appliance, host services</strong></li>
</ul>


## Final decision and purchase of network components
After extensive research and planning, I have decided that the specific devices listed above will best serve the purposes for the home lab design. This considers the proposed use and expectations of the lab. Cost, energy consumption, physical space, noise levels, performance, flexibility, and scalability are other factors that influenced the final decision-making process.




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
