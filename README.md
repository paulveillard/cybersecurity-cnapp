# Cloud Native Application Protection Platform (CNAPP): Theory, Techniques, and Tools


An ongoing & curated collection of awesome software best practices and techniques, libraries and frameworks, E-books and videos, websites, blog posts, links to github Repositories, technical guidelines and important resources about Cloud Native Application Protection Platform (CNAPP) in Cybersecurity.
> Thanks to all contributors, you're awesome and wouldn't be possible without you! Our goal is to build a categorized community-driven collection of very well-known resources.


## `What is Cloud-Native Application Protection Platforms?`

**Cloud-native application protection platforms (CNAPPs)** are a unified and tightly integrated set of security and compliance capabilities, designed to protect cloud-native infrastructure and applications. 
- According to [Gartner](https://www.gartner.com/reviews/market/cloud-native-application-protection-platforms), CNAPP is a security platform that provides consistent visibility and control over all cloud-native applications.

> CNAPPs incorporate an integrated set of proactive and reactive security capabilities, including artifact scanning, security guardrails, configuration and compliance management, risk detection and prioritization, and behavioral analytics, providing visibility, governance and control from code creation to production runtime. CNAPP solutions use a combination of API integrations with leading cloud platform providers, continuous integration/continuous development (CI/CD) pipeline integrations, and agent and agentless workload integration to offer combined development and runtime security coverage




<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-cnapp/blob/main/img/cnapp.jpg?raw=true" alt="Sublime's custom image"/>
</p>

## `Table of Contents`
 - [What is Cloud-Native Application Protection Platforms](#)
 - [The Importance of a CNAPP](#)
 - [CNAPP & DevSecOps](#)
 - [An Array of CNAPP Benefits](#)
 - [Explore the future of CNAPP and cloud security](#)
 - [Considerations When Choosing a CNAPP Tool](#)


## `The Importance of a CNAPP`
Without a CNAPP, your enterprise may miss critical software package upgrades or overlook a system misconfiguration in your application’s critical path. As a result, your organization could lose certifications or suffer a security breach. CNAPPs bring significant benefits:

- Unified cloud security that includes cloud workload protection (CWP), cloud security posture management (CSPM), cloud infrastructure entitlement management (CIEM), and infrastructure as code (IaC)
- Single pane of glass to visualize security threats/alerts and respond quickly
- A standardized security monitoring tool that can be applied to bespoke deployment strategies (such as serverless, Kubernetes, or multi-cloud)
- A centralized source of truth for team compliance that helps organizations move toward a more robust security posture



## `CNAPP & DevSecOps`
Lack of visibility is a major driver of CNAPP adoption and security responsibility has expanded beyond infosec teams to include additional personas. Gartner shares the following insight:  

> With operational responsibilities shifting toward developers and cloud architects, the need for advanced tools to address vulnerabilities, deploy infrastructure as code and manage production implementations has grown to accommodate this expanded scope. Proactively identifying and prioritizing risks during development, while providing developers with adequate context, is essential due to developers perceiving security as an obstacle.

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-cnapp/blob/main/img/cnapp-1.png?raw=true" alt="Sublime's custom image"/>
</p>

Meanwhile, as cloud security becomes democratized internally, attackers are also evolving their techniques and targets: 

- The **attack surface** of cloud-native applications and infrastructure is expanding, with attackers focusing on:
  - the runtime environment,
    - including network, compute, storage,
    -  identities and permissions,
    -  and the misconfiguration of cloud management and control features.
Additionally, APIs and the software supply chain itself have become targets for potential attacks.

## `An Array of CNAPP Benefits` 
### Broad Adoption of Centralized Platforms 

- By 2029, Gartner predicts that over 80% of enterprises will adopt a centralized platform engineering and operations approach to facilitate DevOps self-service and scaling, a significant increase from less than 30% in 2023. In our opinion, this shift not only emphasizes the need for streamlined DevOps practices but also highlights the necessity for a cohesive security strategy that encompasses the entire development lifecycle. With a centralized approach, organizations can foster self-service and scale while maintaining robust security throughout the development process.

  <p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-cnapp/blob/main/img/cnapp-2.png?raw=true" alt="Sublime's custom image"/>
</p>

### Facilitating a Shift Toward Containerization 
In the report Gartner projects that by 2029, 35% of all enterprise applications will run in containers, up from less than 15% in 2023.  

> The surge of containerization underscores the increasing reliance on cloud-native architectures and indicates a corresponding need for security solutions that can manage the complexities associated with container environments.  

As developers increasingly utilize container technology, CNAPPs will need to provide enhanced visibility and control over these dynamic workloads.  

### Cross-Team Collaboration 
- CNAPPs break siloes between application development, cloud architecture, and security operations teams. Having a centralized platform enhances communication and risk identification throughout the development lifecycle. With real-time visibility into workloads and effective vulnerability management, “CNAPPs aim to deliver a comprehensive analysis of various elements and characteristics of the application and cloud environment with a strong emphasis on empowering developers to take responsibility for application risk’’. 

### A Unified Approach to Risk Management  
One of the most significant advantages of CNAPPs is their ability to provide a unified view of risk across cloud environments. By connecting the dots across various layers of cloud infrastructure, CNAPPs help organizations prioritize risks effectively while consolidating siloed point products, reducing the burden on developers and security teams. 

> Furthermore, by balancing the need for product agility with security requirements, CNAPPs support innovation rather than inhibit it.
>
> 

## `Explore the future of CNAPP and cloud security`
- Building a secure-first organization is critical to counter the continual stream of cyberthreats and the increasingly sophisticated nature of them. 
> CNAPP combines several cybersecurity capabilities—cloud security posture management (CSPM), cloud infrastructure entitlement management (CIEM), and cloud workload protection (CWP), among others—into one platform. This platform protects your organization through every operation, from concept development to runtime use. And it’s tailored to applications native to a multicloud environment. As a result, you can both ensure management access and strengthen app-related defenses against potential vulnerabilities in multicloud setups.

  <p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-cnapp/blob/main/img/cnapp-3.png?raw=true" alt="Sublime's custom image"/>
</p>

## `Considerations When Choosing a CNAPP Tool`
When evaluating CNAPP solutions, consider your organization’s needs. Because the market for full-fledged CNAPP products is extensive, your decision-making process should include the use of a rubric for the following aspects. The ability to view threats and security vulnerabilities across an organization’s cloud landscape is essential for any CNAPP offering. A CNAPP that lets you see cloud-based, on-premises, and hybrid environments — all in one platform — ensures you’ll be alerted to any issues. A unified platform typically combines:

### ``A Unified Platform``
There is a wide range of solutions on the market that help to secure the way in which cloud services are used. These tools provide additional controls that are relevant to the security threats and risks that are relevant to the cloud. These tools include:

#### `CASB (Cloud Access Security Brokers):`
- It provides control over which SaaS services organizational users can access. CASB discovers shadow IT usage and prevents access to unsanctioned services that the organization considers to be too risky. They often integrate with the major SaaS services to implement fine-grained controls over how these sanctioned services can be used. They also include or integrate with DLP (Data Leakage Prevention) solutions to control which data can be moved to cloud services.

#### `SASE (Secure Access Service Edge):` 
- It provides network-based access controls to cloud services. They commonly provide capabilities that are a convergence of SD-WAN (Software Defined Wide Area Networking), SWG (Secure Web Gateways), VPN (Virtual Private Network) and Remote Browser Isolation (RBI) to implement Zero Trust access controls based on the combination of user and device identities.

#### `CIEM (Cloud Infrastructure Entitlement Management):`
- It provides controls over the entitlements possessed by virtual resources. In a software defined infrastructure, such as that provided by a cloud service, the software defined elements need
entitlements to operate and threat actors can exploit excessive entitlements.

####  `CSNS (Cloud Service Network Security):`
- It provides capabilities to help to secure the in-cloud network, combining tools such as web application firewalls, secure web gateways, and DDoS protection.


####  `CSPM (Cloud Security Posture Management):`
- It provides a way to continuously identify, visualize, and manage an overview of the risks associated with the use of IaaS cloud services.


####  `CWPP (Cloud Workload Protection Platform):`
- It provides controls at the microservices instance/container level. They typically include threat detection, intrusion prevention, anti-malware, application control, and vulnerability monitoring.


####  `DSPM (Data Security Posture Management):`
- It provides a way to discover, catalog and ensure protection and compliance of data held across multiple clouds, from databases to unstructured object storage services.





## `License`
MIT License & [cc](https://creativecommons.org/licenses/by/4.0/) license

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.


To the extent possible under law, [Paul Veillard](https://github.com/paulveillard/) has waived all copyright and related or neighboring rights to this work.

