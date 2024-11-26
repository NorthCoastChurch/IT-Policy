# **Definitions**

**Virtualization:** The creation of a virtual (rather than actual) version of something, such as an operating system, a server, a storage device, or network resources.

# **Overview**

This policy encompasses all new and existing workloads.

**Purpose**

The purpose of this policy is to establish server virtualization requirements that define the acquisition, use, and management of server virtualization technologies. This policy provides controls that ensure that Enterprise issues are considered, along with business objectives, when making server virtualization related decisions.

Platform Architecture policies, standards, and guidelines will be used to acquire, design, implement, and manage all server virtualization technologies.

## **Policy Detail**

{COMPANY-NAME}’s VP of IT has the overall responsibility for ensuring that policies are followed in order to establish contracts and the confidentiality, integrity, and availability of {COMPANY-NAME} data.

Other IT staff members, under the direction of the Director of IT, are responsible for following the procedures and policies within IT.

{COMPANY-NAME}’s legacy IT practice was to dedicate one physical server to a single workload. The result of this practice was excessive server underutilization, an ever- expanding data center footprint, and excessive data center power consumption.

Server virtualization software allows the consolidation of new and existing workloads onto high capacity x86 servers. Consolidating workloads onto high capacity x86 servers allows {COMPANY-NAME} to reduce the x86 server inventory, which in turn decreases the data center footprint and data center power consumption.

{COMPANY-NAME} will migrate all new and existing workloads from physical servers to virtual machines. Hardware will be retired at such time as planned by IT management or required by incompatibility with Operating Systems (OS) and/or workload specific software updates.

**Server Virtualization Requirements:**

- Support industry-wide open-standards
- Embedded security technology, such as, Trusted Platform Module (TPM) or other technologies
- Single centralized management console
- Support industry standard management tools
- Support industry standard backup and recovery tools
- Interoperate with other platform technologies
- Support industry standard x86 hardware
- Support industry standard storage
- Support unmodified guest operating systems
- Functionality to support virtual server management network isolation
- Migrate running guests without interruption
- Add disks to a running guest
- Automatically detect a hardware failure and restart guests on another physical server
- Functionality to configure role based access for the administrative console
- Support Lightweight Directory Access Protocol (LDAP) for authentication and authorization for administrative console
- Encrypt all intra host and administrative console traffic
- Integrated graphical Central Processing Unit (CPU), memory, disk, and network performance monitoring, alerting, and historical reporting for hosts and guests
- Other industry standard or best in class features as required