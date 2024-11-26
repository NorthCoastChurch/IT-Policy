# **Definitions**

**Firewall**: Any hardware and/or software designed to examine network traffic using policy statements (ruleset) to block unauthorized access while permitting authorized communications to or from a network or electronic equipment.

**Firewall configuration**: The system setting affecting the operation of a firewall appliance.

**Firewall ruleset**: A set of policy statements or instructions used by a firewall to filter network traffic.

**Host firewall**: A firewall application that addresses a separate and distinct host, such as a personal computer.

**Internet Protocol (IP)**: Primary network protocol used on the Internet.

**Network firewall**: A firewall appliance attached to a network for the purpose of controlling traffic flows to and from single or multiple hosts or subnet(s).

**Network topology**: The layout of connections (links, nodes, etc.) of a computer network.

**Simple Mail Transfer Protocol (SMTP)**: An Internet standard for electronic mail (e- mail) transmission across Internet Protocol (IP) networks.

**Virtual private network (VPN)**: A network that uses a public telecommunication infrastructure, such as the Internet, to provide remote offices or individual users with private, secure access to their organization’s network.

# **Overview**

{COMPANY-NAME} operates network firewalls between the Internet and its private internal network to create a secure operating environment for {COMPANY-NAME}’s computer and network resources. A firewall is just one element of a layered approach to network security.

**Purpose**

This policy governs how the firewalls will filter Internet traffic to mitigate the risks and losses associated with security threats to {COMPANY-NAME}’s network and information systems.

The firewall will (at minimum) perform the following security services:

- Access control between the trusted internal network and untrusted external networks
- Block unwanted traffic as determined by the firewall ruleset
- Hide vulnerable internal systems from the Internet
- Hide information, such as system names, network topologies, and internal user IDs, from the Internet
- Log traffic to and from the internal network
- Provide robust authentication
- Provide virtual private network (VPN) connectivity

# **Policy Detail**

All network firewalls, installed and implemented, must conform to the current standards as determined by {COMPANY-NAME}’s IT Department. Unauthorized or non-standard equipment is subject to immediate removal, confiscation, and/or termination of network connectivity without notice.

The approach adopted to define firewall rulesets is that all services will be denied by the firewall unless expressly permitted in this policy.

- Outbound – allows all Internet traffic to authorized groups
- All traffic is authorized by Internet Protocol (IP) address and port The firewalls will provide:
- Packet filtering – selective passing or blocking of data packets as they pass through a network interface. The most often used criteria are source and destination address, source and destination port, and protocol.
- Application proxy – every packet is stopped at the proxy firewall and examined and compared to the rules configured into the firewall.
- Stateful Inspection – a firewall technology that monitors the state of active connections and uses this information to determine which network packets to allow through the firewall.

The firewalls will protect against:

- IP spoofing attacks – the creation of IP packets with a forged source IP address with the purpose of concealing the identity of the sender or impersonating another computing system.
- Denial-of-Service (DoS) attacks - the goal is to flood the victim with overwhelming amounts of traffic and the attacker does not care about receiving responses to the attack packets.
- Any network information utility that would reveal information about the {COMPANY-NAME} domain.

A change control process is required before any firewall rules are modified. Prior to implementation, the Third Party Vendor and {COMPANY-NAME} network administrators are required to have the modifications approved by the Director of IT or the VP of IT. All related documentation is to be retained for three (3) years.

All firewall implementations must adopt the position of “least privilege” and deny all inbound traffic by default. The ruleset should be opened incrementally to only allow permissible traffic.

Firewall rulesets and configurations require periodic review to ensure they afford the required levels of protection:

{COMPANY-NAME} must review all network firewall rulesets and configurations during the initial implementation process and periodically thereafter.

Firewall rulesets and configurations must be backed up frequently to alternate storage (not on the same device). Multiple generations must be captured and retained, to preserve the integrity of the data, should restoration be required.

Access to rulesets and configurations and backup media must be restricted to those responsible for administration and review.

**Responsibilities**

The IT Department is responsible for implementing and maintaining {COMPANY-NAME} firewalls, as well as for enforcing and updating this policy. Logon access to the firewall will be restricted to a primary firewall administrator and designees as assigned. Password construction for the firewall will be consistent with the strong password creation practices outlined in the {COMPANY-NAME} Password Policy.

The specific guidance and direction for information systems security is the responsibility of IT. Accordingly, IT will manage the configuration of the {COMPANY-NAME} firewalls.

{COMPANY-NAME} has contracted with a Third Party Vendor to manage the external firewalls. This vendor will be responsible for:

- Retention of the firewall rules
- Patch Management
- Review the firewall logs for:
- System errors
- Blocked web sites
- Attacks
- Sending alerts to the {COMPANY-NAME} network administrators in the event of attacks or system errors
- Backing up the firewalls