# Azure notes
Azure exam preparation notes

## Azure Fundamentals (AZ-900)
- Microsoft Azure is a cloud computing platform with an ever-expaning set of services to help you build solutions to meet your business goals.
- Support everything from simple to complex.
- Remote storage, database hosting, centralized account managment, AI, IOT services, etc.,

### Describe cloud concepts
#### Describe cloud computing
- `cloud computing` - Delivery of computing services over the internet.
- VMs, storage, db and networking, IOT, ML, AI services. 
- Rapidly expand your IT footprint.
- Shared Responsibility Model
  - cloud provider - physical datacenter, network, hosts.
  - customer - information and data stored on cloud, devices that allowed to connect to cloud, accounts and indentities of people and services. 
  - Based on service model - OS, network controls, applications, Identity and Infrastructure.
 - Cloud Models
  - `Private cloud` - Cloud that used by a single entity.
  - `Public cloud` - Maintained by third party to provide cloud services to anyone. General public availability.
  - `Hybrid cloud` - Public and private clouds in inter-connected environment. Provides the most flexibility.
  - `Multi-cloud` - Using multiple public cloud providers. 
  - `Azure Arc` - Set of technologies to manage cloud environments (private, public, hybrid or multi-cloud)
  - `Azure VMware Solution` - VMWare private cloud --> public or hybrid. Run your VMWare workloads in Azure with seamless integration and scalability.
- Consumption based model - `pay-as-you-go` pricing model. Shifting CapEx to OpEx.

#### Describe the benefits of using cloud services
- High availability - Based on SLA of the service, Azure services highly available.
- Scalability - Ability to adjust resources to meet demand. 
  - Vertical scaling - Add/Reduce CPU, RAM. Scale up/down.
  - Horizontal scaling - Add/Remove VMs, Containers. Scale out/in.
- Reliability - Decentralized design supports reliable and resilient infra. Global scale, multi-region deployments.
- Predictability
  - Performance - Autoscaling, load balancing, and high availability supports performance predictability.
  - Cost - Total Cost of Ownership(TCO), Pricing calculator. Track cloud resource use in real time, apply analytics and find patterns and trends to plan for better resource deployments.
- Security and governance
  - `set templates` - ensure all resources meet corporate standards and government regulatory requirements.
  - Cloud based auditing helps to flag non compliant resources and provide mitigation strategies.
  - Cloud providers typically take care DDos kind of attacks and provide more robust and secure network.
- Manageability
  - Management of the cloud - Managing your cloud resources
    - Autoscaling.
    - Using preconfigured templates for resource deployment
    - Monitoring health of resources.
    - Alerts based on configured performance metrics.
  - Management in the cloud - How you're able to manage your cloud resources - Web portal, CLI, API, PowerShell.
#### Describe cloud service types
- Infrastructure as a Service (IaaS)
  - Most flexible. Provides maximum amount of control. 
  - Renting the hardware in a cloud datacenter, but what you do with that hardware is up to you.
  - Lift-and-shift-migration
  - Testing and development
- Platform as a Service (PaaS)
  - Middle ground between IaaS and SaaS.
  - Provides complete development environment.
  - Development framework
  - Analytics or business intelligence.
- Software as a Service (SaaS)
  - Renting fully developed application. Least flexible.
  - Email and messaging.
  - Business productivity applications.
  - Finance and expense tracking.

### Describe Azure architecture and services

### Describe Azure management and governance
