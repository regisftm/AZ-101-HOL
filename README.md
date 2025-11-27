# AZ-101: FortiGate as Azure Cloud Firewall

## Fortinet Security Hands On Workshop | Azure Series

### Welcome

Organizations are rapidly adopting Microsoft Azure to accelerate digital transformation, but this cloud migration introduces new security challenges. Extending consistent security policies from on-premises to the cloud while maintaining operational efficiency is critical. Many organizations struggle with fragmented security tools, rising costs from native cloud security services, and the complexity of securing hybrid environments. Without a unified approach, security teams face visibility gaps, manual processes, and difficulty maintaining compliance across their expanding attack surface.

In this workshop, participants will learn how to deploy FortiGate in Microsoft Azure to protect their first cloud workloads. Using a realistic customer scenario, participants will build complete Azure networking infrastructure, deploy and license a FortiGate VM, configure security policies for north-south traffic inspection, and establish site-to-site IPsec VPN connectivity between Azure and on-premises environments.

At the heart of this solution is FortiGate as a Next-Generation Firewall (NGFW) in Azure, providing the same security capabilities and operational consistency that organizations rely on in their on-premises deployments. Participants will discover how to leverage Azure User Defined Routes (UDRs) to force traffic inspection, configure NAT for internet access, and use FortiGate's VPN capabilities to eliminate the need for separate Azure VPN Gateway—delivering 60-70% cost savings compared to Azure Firewall solutions.

### Time Requirements

The estimated time to complete this workshop is 3 hours.

### Target Audience

- Cloud security engineers and architects
- Network security professionals transitioning to cloud
- Fortinet administrators expanding to Azure
- IT professionals implementing enterprise security solutions
- Security consultants and presales engineers
- System administrators responsible for firewall management

**Experience Level**: Intermediate to advanced professionals with networking fundamentals and basic Azure knowledge.

### What You'll Learn

- Deploy complete Azure networking infrastructure (VNets, subnets, route tables)
- Configure FortiGate VM in Azure with BYOL licensing
- Implement User Defined Routes to force traffic through FortiGate for inspection
- Create firewall policies with NAT for secure internet access
- Establish site-to-site IPsec VPN for hybrid connectivity
- Use FortiGate logs and FortiView for traffic visibility and troubleshooting
- Demonstrate cost savings and business value vs. Azure native solutions

### Reference Architecture

After completing this bootcamp, you will have deployed the following architecture.

![reference-architecture](az-101-lab4/images/final_architecture.png)

## Laboratories

This workshop is organized in sequential laboratories. One lab will build up on top of the previous module, so please, follow the order as proposed below.

Lab 1 - [Azure Infrastructure Foundation](/az-101-lab1/README.md)  
Lab 2 - [FortiGate VM Deployment & Traffic Steering](/az-101-lab2/README.md)  
Lab 3 - [Security Policies & Traffic Testing](/az-101-lab3/README.md)  
Lab 4 - [Site-to-Site VPN Configuration](/az-101-lab4/README.md)

---

> [!NOTE]
> The workshop provides examples and sample code as instructional content for you to consume. These examples will help you understand how to configure Fortinet Security Fabric and build a functional solution. **Please note that these examples are not suitable for use in production environments**.  

---

> [!CAUTION]
> If you are using an Azure subscription in your production environment, it would be more prudent not to use your "Global Admin" account. Although the lab is designed to function in "isolated" mode, a "human" error when creating certain resources such as peering and routing table could impact your production environment. **We recommend using your standard account on an isolated subscription**.

---

> [!WARNING]
> This lab uses several virtual machines. The entire lab should stay under **15**. At the end of the day, it will be important to delete everything or at least stop the VMs if you don't want any unpleasant surprises.
