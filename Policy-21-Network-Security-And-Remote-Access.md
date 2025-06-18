# **Definitions**

**Virtual Private Network (VPN)**: A private network that extends across a public network or internet. It enables users to send and receive data across shared or public networks as if their computing devices were directly connected to the private network. Some VPNs allow employees to securely access a corporate intranet while located outside the office.

**User Authentication**: A method by which the user of a system can be verified as a legitimate user independent of the computer or operating system being used.

**Multi-Factor Authentication**: A method of computer access control in which a user is granted access only after successfully presenting several separate pieces of evidence to an authentication mechanism – typically at least two of the following categories:

- Knowledge (something they know)
- Possession (something they have)
- Inherence (something they are)

**Dual Homing**: Having concurrent connectivity to more than one network from a computer or network device. Examples include:

- Being logged into the corporate network via a local Ethernet connection, and dialing into AOL or another Internet Service Provider (ISP)
- Being on a North Coast Church provided remote access home network, and connecting
- to another network, such as a spouse’s remote access
- Configuring an Integrated Services Digital Network (ISDN) router to dial into North Coast Church and an ISP, depending on packet destination

**DSL**: Digital Subscriber Line (DSL) is a form of high-speed Internet access competing with cable modems. DSL works over standard phone lines and supports data speeds of over 2 Mbps downstream (to the user) and slower speeds upstream (to the Internet).

**ISDN**: There are two flavors of ISDN: BRI and PRI. BRI is used for home/office/remote access. BRI has two “Bearer” channels at 64kb (aggregate 128kb) and 1 D channel for signaling information.

**Remote Access**: Any access to North Coast Church’s corporate network through a non- North Coast Church controlled network, device, or medium.

**Split-tunneling**: Simultaneous direct access to a non-North Coast Church network (such as the Internet, or a home network) from a remote device (PC, PDA, WAP phone, etc.) while connected into North Coast Church’s corporate network via a Virtual Private network (VPN) tunnel. VPN is a method for accessing a remote network via “tunneling: through the Internet.

**IPSec Concentrator**: A device in which VPN connections are terminated.

**Cable Modem**: Cable companies such as AT&T Broadband provide Internet access over Cable TV coaxial cable. A cable modem accepts this coaxial cable and can receive data from the Internet at over 1.5 Mbps.

**CHAP**: Challenge Handshake Authentication Protocol is an authentication method that uses a one-way hashing function. Data Link Connection Identifier (DLCI) is a unique number assigned to a Permanent Virtual Circuit (PVC) end point in a frame relay network. DLCI identifies a particular PVC endpoint within a user’s access channel in a frame relay network and has local significance only to that channel.

**Read More**: [How To Develop & Implement A Network Security Plan](https://purplesec.us/network-security-plan/)

# **Overview**

This policy is to protect North Coast Church’s electronic information from being inadvertently compromised by authorized personnel connecting to the North Coast Church network locally and remotely via VPN**.**

**Purpose**

The purpose of this policy is to define standards for connecting to North Coast Church’s network from any host. These standards are designed to minimize the potential exposure to North Coast Church from damages, which may result from unauthorized use of North Coast Church resources.

Damages include the loss of sensitive or company confidential data, intellectual property, damage to public image, damage to critical North Coast Church internal systems, etc.

Remote access implementations that are covered by this policy include, but are not limited to, dial-in modems, ISDN, DSL, VPN, SSH, and cable modems, etc.

**Audience**

This policy applies to all North Coast Church employees, volunteers/directors, contractors, vendors, and agents with a computer or workstation used to connect to the North Coast Church network. This policy applies to remote access connections used to do work on behalf of North Coast Church, including reading or sending email and viewing intranet resources.

## **Policy Detail**

**Network Security**

Users are permitted to use only those network addresses assigned to them by North Coast Church‘s IT Department.

All remote access to North Coast Church will either be through a secure VPN connection on a North Coast Church owned device that has up-to-date anti-virus software, or on approved mobile devices (see the North Coast Church Owned Mobile Device Acceptable Use and Security Policy and the Personal Device Acceptable Use and Security Policy).

Remote users may connect to North Coast Church Information Systems using only protocols approved by IT. Users inside the North Coast Church firewall may not be connected to the North Coast Church network at the same time a remote connection is used to an external network.

Users must not extend or re-transmit network services in any way. This means a user must not install a router, switch, hub, or wireless access point to the North Coast Church network without North Coast Church IT approval.

Users must not install network hardware or software that provides network services without North Coast Church IT approval. Non-North Coast Church computer systems that require network connectivity must be approved by North Coast Church IT.

Users must not download, install, or run security programs or utilities that reveal weaknesses in the security of a system. For example, North Coast Church users must not run password cracking programs, packet sniffers, network mapping tools, or port scanners while connected in any manner to the North Coast Church network infrastructure. Only the IT Department is permitted to perform these actions.

Users are not permitted to alter network hardware in any way.

**Remote Access**

It is the responsibility of North Coast Church employees, volunteers/directors, contractors, vendors, and agents, with remote access privileges to North Coast Church’s corporate network, to ensure that their remote access connection is given the same consideration as the user’s on-site connection to North Coast Church.

General access to the Internet, through the North Coast Church network is permitted for employees who have flat-rate services and only for business purposes. North Coast Church employees are responsible to ensure that they:

- Do not violate any North Coast Church policies
- Do not perform illegal activities
- Do not use the access for outside business interests

North Coast Church employees bear responsibility for the consequences should access be misused.

Employees are responsible for reviewing the following topics (listed elsewhere in this policy) for details of protecting information when accessing the corporate network via remote access methods and acceptable use of North Coast Church’s network:

- Virtual Private Network (VPN)
- Wireless Communications

Dial-in modem usage is not a supported or acceptable means of connecting to the North Coast Church network.

**Requirements**

Secure remote access must be strictly controlled. Control will be enforced with Multi- Factor Authentication (MFA).

North Coast Church employees, volunteers/directors, and contractors should never provide their login or email password to anyone, including family members.

North Coast Church employees, volunteers/directors, and contractors with remote access privileges:

- Must ensure that their computer, which is remotely connected to North Coast Church’s corporate network, is not connected to any other network at the same time, with the exception of personal networks that are under the complete control of the user.
- Must not use non-North Coast Church email accounts (i.e. Hotmail, Yahoo, AOL), or other external resources to conduct North Coast Church business, thereby ensuring that official business is never confused with personal business.

Reconfiguration of a home user’s equipment for split-tunneling or dual homing is not permitted at any time.

For remote access to North Coast Church hardware, all hardware configurations must be approved by IT.

All hosts that are connected to North Coast Church internal networks, via remote access technologies, must use up-to-date, anti-virus software applicable to that device or platform.

Organizations or individuals who wish to implement non-standard Remote Access solutions to the North Coast Church production network must obtain prior approval from IT.

**Virtual Private Network (VPN)**

The purpose of this section is to provide guidelines for Remote Access IPSec or L2TP Virtual Private Network (VPN) connections to the North Coast Church corporate network. This applies to implementations of VPN that are directed through an IPSec Concentrator.

This applies to all North Coast Church employees, volunteers/directors, contractors, consultants, temporaries, and other workers including all personnel affiliated with third parties utilizing VPN’s to access the North Coast Church network.

Approved North Coast Church employees, volunteers/directors, and authorized third parties (customers, vendors, etc.) may utilize the benefit of a VPN on a North Coast Church device, which is a “user managed” service. This means that the user is responsible for selecting an Internet Service Provider (ISP), coordinating installation, and paying associated fees. Further details may be found in the Remote Access section.

The following guidelines will also apply:

- It is the responsibility of employees or volunteer/directors, with VPN privileges, to ensure that unauthorized users are not allowed access to North Coast Church internal networks.
- VPN use is controlled using a multi-factor authentication paradigm.
- When actively connected to the corporate network, VPNs will force all traffic to and from the PC over the VPN tunnel; all other traffic will be dropped.
- VPN gateways will be set up and managed by North Coast Church IT.
- All computers connected to North Coast Church internal networks via VPN or any other technology must use up-to-date, anti-virus software applicable to that device or platform.
- VPN users will be automatically disconnected from North Coast Church’s network after thirty minutes of inactivity. The user must then logon again to reconnect to the network. Pings or other artificial network processes are not to be used to keep the connection open.
- The VPN concentrator is limited to an absolute connection time of 24 hours.
- To ensure protection from viruses, as well as protection of member data, only North Coast Church-owned equipment or non-North Coast Church devices in accordance with the Personal Device Acceptable Use and Security Policy (BYOD) will have VPN and Remote Access.
- Only IT approved VPN clients may be used.
- By using VPN technology, users must understand that their machines are an extension of North Coast Church’s network and as such are subject to the same rules and regulations, as well as monitoring for compliance with this policy.

**VPN Encryption and Authentication**

All computers with wireless LAN devices must utilize a North Coast Church approved VPN configured to drop all unauthenticated and unencrypted traffic and will be provisioned with split-tunneling disabled. As with all North Coast Church computers, Windows or other OS and/or browser Internet proxy settings will be enabled to effectively route Internet access to the device through North Coast Church firewalls and Internet filters.

To comply with this policy, wireless implementations must maintain point to point hardware encryption of at least 128 bits, support a hardware address that can be registered and tracked (i.e. a MAC address), and support and employ strong user authentication, which checks against an external

database such as TACACS+, iDiTJS, or something similar. Any deviation from this practice will be considered on a case-by-case basis.

**VPN Approval, Acceptable Use Review and Acceptance**

Approval from a staff director or higher authority is required for a user’s VPN access account creation. An acceptable use form is attached to the VPN procedure maintained by Information Technology and shall be reviewed and signed by each approved user to acknowledge having read and understood the policy (see Exhibit A). This form shall in turn be approved, collected, and retained by IT management prior to the user’s VPN account use.

**Wireless Communications**

Access to North Coast Church networks is permitted on wireless systems that have been granted an exclusive waiver by IT for connectivity to North Coast Church’s networks.

This section covers any form of wireless communication device capable of transmitting packet data. Wireless devices and/or networks without any connectivity to North Coast Church’s networks do not fall under the review of this policy.

**Register Access Points and Cards**

All wireless Access Points/Base Stations connected to the corporate network must be registered and approved by IT. If they are installed in corporate PCs, all wireless Network Interface Cards (i.e. PC cards) used in corporate laptop or desktop computers must be registered with IT.

**Approved Technology**

All wireless LAN access must use North Coast Church approved vendor products and security configurations.

**Setting the Service Set Identifier (SSID)**

The SSID shall be configured so that it does not contain any identifying information about the organization, such as the company name, division title, employee name, or product identifier.

**EXHIBIT A**

\[This exhibit is a copy of the Addendum A in the VPN Connectivity to North Coast Church Network Procedure.doc\]

**Virtual Private Network (VPN) Agreement**

This Virtual Private Network Agreement is entered into between the User and North Coast Church LLC (North Coast Church), effective the date this agreement is executed by North Coast Church’s Information Technology Department (IT). The parties agree as follows:

**ELIGIBILITY**

The use of a mobile device connecting to the North Coast Church network is a privilege granted to the User by management approval per the Network Security and VPN Acceptable Use Policy. If the User does not abide by the terms, IT Management reserves the right to revoke the privilege granted herein. The policies referenced herein are aimed to protect the integrity of data belonging to North Coast Church and to ensure the data remains secure.

In the event of a security breach or threat, North Coast Church reserves the right, without prior notice to the User, to disable or disconnect the VPN connection of the mobile device.

**SECURITY CONSIDERATIONS AND ACCEPTABLE USE**

Compliance by the User with the following North Coast Church policies, published elsewhere and made available, is mandatory: Acceptable Use of Information Systems, Anti-Virus, E-Mail, Password, Safeguarding Member Information, and Telecommuting.

User of the mobile device shall not remove sensitive information from the North Coast Church network, attack North Coast Church assets, or violate any of the security polices related to the subject matter of this agreement.

The User understands and agrees that his/her use of the VPN software is required as part of his/her employment at North Coast Church and is permitted to connect to internal information services in support of North Coast Church activities only. The User will safeguard the VPN access as well as its components (software/password) from any unauthorized use.

The VPN will be used on a company issued mobile device that is protected by a personal firewall. The company issued mobile device may be subject to scanning from the IT Department to check compliance with the contents of this Agreement.

**SUPPORT**

North Coast Church will offer support for connectivity to the North Coast Church network. North Coast Church is not responsible for ISP outages that result in a failure of connectivity to the North Coast Church network.

The User assumes full liability including, but not limited to, an outage or crash of any or all of the North Coast Church network.

The User certifies that this Agreement has been read and has an understanding of the above conditions under which the User may be provided access to North Coast Church computer/information systems and further that the User understands and agrees to abide by them. The User also understands that limitations on disclosure of any information covered under this Agreement shall survive the modification or elimination of the User access to North Coast Church computer/information systems.