# Network Security Management SOP
**Author:** Kevin Hoang

## Purpose:
To establish and maintain network security measures that protect the organization's data, systems, and assets from cybersecurity threats.

## Scope:
This SOP applies to all network security practices within the organization.

## Responsibilities:
- **IT Department:** Oversee network security management.
- **Network Administrators:** Implement and maintain security measures.
- **Employees:** Follow security policies and procedures.

## Prerequisites:
- pfSense 2.7.1 and Windows Server 2019 installed and configured.
- Access to necessary security tools and resources.

## Procedures:

### 1. Firewall Implementation using pfSense 2.7.1:
- Deploy pfSense 2.7.1 as the network firewall.
- Configure firewall rules using the pfSense web interface.
- Implement a default deny-all rule and allow only necessary incoming and outgoing traffic.
- Regularly review and update firewall rules to reflect changes in network requirements and emerging threats.

### 2. Endpoint Security using Windows Server 2019:
- Utilize Windows Server 2019 for endpoint security.
- Configure Windows Defender and other security features on Windows Server 2019.
- Implement real-time scanning and automatic updates on Windows Server 2019 to ensure endpoint security remains up-to-date.
- Educate employees about the importance of not disabling or circumventing endpoint security software on Windows Server 2019.

### 3. Data Encryption:
- Implement end-to-end encryption for sensitive data in transit using protocols such as HTTPS, TLS, and VPN on pfSense 2.7.1.
- Encrypt data at rest on Windows Server 2019 using strong encryption algorithms.
- Regularly audit and monitor encryption configurations on both platforms to prevent misconfigurations and ensure compliance.

### 4. Access Control and Identity Management:
- Enforce strong authentication methods on Windows Server 2019 (e.g., MFA, biometrics) for network access.
- Implement role-based access control (RBAC) on Windows Server 2019 to restrict access based on job roles.
- Conduct periodic access reviews on Windows Server 2019 and promptly remove unnecessary access privileges.

### 5. Network Segmentation using pfSense 2.7.1:
- Implement micro-segmentation using pfSense 2.7.2 to limit lateral movement within the network.
- Use VLAN segmentation on pfSense 2.7.1 to logically separate network traffic by the department.
- Apply access control lists (ACLs) on pfSense 2.7.1 to control communication between segments and enforce the principle of least privilege.

### 6. Regular Security Audits and Scans:
- Conduct regular vulnerability assessments and penetration tests using appropriate tools compatible with both Windows Server 2019 and pfSense 2.7.1.
- Perform automated and manual security audits of network configurations on both platforms.
- Continuously monitor for unauthorized or unusual activities through security information and event management (SIEM) tools compatible with both Windows Server 2019 and pfSense 2.7.1.

### 7. Patch Management on Windows Server 2019:
- Establish a centralized patch management system on Windows Server 2019 to deploy security patches and updates promptly.
- Segment and prioritize patches on Windows Server 2019 based on criticality, focusing on vulnerabilities that pose the highest risk.
- Test patches in a controlled environment before deploying them to production systems running Windows Server 2019.

### 8. Backup and Disaster Recovery on Windows Server 2019:
- Implement an automated backup solution on Windows Server 2019 that includes regular on-site and off-site backups.
- Store backups securely and encrypted on Windows Server 2019.
- Test backup and disaster recovery procedures on Windows Server 2019 regularly to verify data restoration capabilities.

### 9. Security Monitoring and Incident Response:
- Deploy intrusion detection and prevention systems (IDS/IPS) compatible with Windows Server 2019 and pfSense 2.7.1 to monitor network traffic for suspicious patterns.
- Establish an incident response plan with clear roles and responsibilities for addressing security incidents on both platforms.
- Conduct post-incident analysis to identify root causes and improve incident response processes.

### 10. Employee Training and Awareness:
- Provide ongoing cybersecurity training to all employees to reinforce security awareness.
- Conduct phishing simulations to test employees' ability to recognize and report phishing attempts.
- Encourage employees to report security concerns or incidents to the IT team promptly.

### 11. Policy Enforcement:
- Enforce security policies consistently and communicate them clearly to all employees.
- Use automated policy enforcement tools compatible with Windows Server 2019 and pfSense 2.7.1 to prevent policy violations.
- Regularly review and update security policies to align with changing threats and regulations.

### 12. Regular Updates and Auditing:
- Keep security policies and configurations up-to-date and review them regularly on both Windows Server 2019 and pfSense 2.7.1.
- Conduct internal and external security audits to assess compliance with policies and regulations on both platforms.
- Implement continuous security monitoring and alerting on both Windows Server 2019 and pfSense 2.7.1 to identify policy violations promptly.

Revision History:

    Version 1.0 (Author: Kevin Hoang, Date: 12.21.2023)


