# Lab Phase 1: Design and equiment considerations

## Define use and expectations of network
The design of the home lab will serve the purpose of providing an environment for experimentation, analysis, reinforcing knowledge, and learning new skills. The main areas of focus will be networking, data communications, and cybersecurity. Exploring these areas in depth in a controlled environment will provide a better understanding of these topics and hands-on experience with different hardware and software. This provides a setting where testing, performing simulated attacks, and exploring vulnerabilities can be done safely and ethically.

## Research network designs and configurations
There are many different home lab network designs and configurations that can be considered. However, with this being my first purpose-built lab for learning experiences, lower cost components will be desired. A dedicated firewall device and a managed switch were devices that I knew I wanted to include in my home lab. Regardless of other design considerations, these devices were essential.
My computing and processing needs could be fulfilled using various methods, each with their own benefits and disadvantages. Details of the different methods are listed in the table below.

<div align="center">
  
  ![Description of Image](https://raw.githubusercontent.com/blaine-geiger/Lab-Phase-1/6bfecc0fc48da30e27182460003f3453a4d5d018/design_options.png)
  
</div>

## Determine final physical network design and network device types
Based on my research of these possible designs, while considering cost, performance, flexibility, scalability, power consumption, and physical space, I have decided to use a single, but powerful, NUCbox for my computing and processing requirements. This will provide enough performance to meet my goals, while maintaining the opportunity to expand and increase scale if needed. This design may also be shifted into a hybrid design by adding and clustering additional NUCboxes later.

The final physical design of the home lab network will consist of a firewall, a managed switch, and a single PC with a virtualization environment, capable of running multiple simultaneous virtual machine (VM) instances. Virtualization software can optimize performance by dynamically allocating resources such as CPU, RAM, and storage. It will provide high flexibility with the ability to build and run custom VMs that meet the needs for exploring and testing specific scenarios.
  
The final physical network design is diagrammed in the figure below:

<div align="center">
  
  ![Description of Image](https://raw.githubusercontent.com/blaine-geiger/Lab-Phase-1/e99b645256e8269a782d7f73529de67e51c40a14/network_final.png)
  
</div>


## Research specific device manufacturers and models for purchasing
The physical components that will make up the final physical network design are a firewall, managed switch, and Mini PC. The following will provide insight into the rationale for these devices.
### General Purpose SOHO Firewall
- Reputable manufacturer
- Compact form factor
- Powerful performance for size
- Strong support and user community
- Advanced features


### Managed Switch
- Segmentation and performance capabilities
- Advanced features VPN, VLANs, port mirroring
- 8 ports allow scalability
- Compact design and cost effective


### Medium Spec Mini-PC
- Powerful and compact
- AMD processor, 4 cores/16 threads, 4.3 GHz, 32 GB RAM, 1 TB SSD
- Much more affordable than Intel-based options with similar specifications
- Low power consumption
- Expandability to upgrade RAM and storage
- Flexibility to be reconfigured as a network appliance or host services in the future if needed


## Final decision and purchase of network components
After extensive research and planning, I have decided that the devices listed above will best serve the purposes for the home lab design. This considers the proposed use and expectations of the lab. Cost, energy consumption, physical space, noise levels, performance, flexibility, and scalability are other factors that influenced the final decision-making process.




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
