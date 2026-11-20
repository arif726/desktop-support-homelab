# 🖥️ Desktop Support Home Lab

Hands-on labs covering the **Microsoft end-user computing stack** used in Australian desktop support and service desk roles: Windows Server, Active Directory, Microsoft 365, Entra ID and Intune.

Every lab is built from scratch in my own virtual environment and documented step by step, including the errors I hit and how I fixed them.

---

## 👤 About Me

**Md Nasim Uddin Arif** · Sydney, Australia

- Master of Research (MRes) student at CQUniversity Australia, Sydney
- 2+ years in ISP network operations at Summit Communications Ltd. (Bangladesh): NMS monitoring, fault triage and escalation, fibre installation and device deployment
- Cisco Networking Academy CCNA (200-301) course completed
- ACS Associate Member
- Customer-facing experience in Australian hospitality and service roles

🔗 [LinkedIn](https://www.linkedin.com/in/nasimuddinarif) · 📁 See my other repositories for networking labs (GNS3, BGP, MPLS, OSPF)

---

## 🧪 Lab Environment

| Component | Details |
|---|---|
| Host | Beelink SER8 mini PC (32 GB RAM, 1 TB SSD) |
| Hypervisor | VMware Workstation |
| Server | Windows Server 2025 (Evaluation, Desktop Experience) |
| Clients | Windows 11 Enterprise (Evaluation) × 2 |
| Domain | `arif.lab` |
| Network | 192.168.50.0/24 |

### Topology

| Hostname | Role | IP Address |
|---|---|---|
| DC01 | Domain Controller: AD DS, DNS, DHCP | 192.168.50.10 (static) |
| PC01 | Windows 11 domain client | DHCP |
| PC02 | Windows 11 domain client | DHCP |

---

## 📚 Labs

| # | Lab | Skills | Status |
|---|---|---|---|
| 01 | [Active Directory Domain Setup](./lab01-active-directory) | AD DS, DNS, DHCP, domain join | 🔄 In progress |
| 02 | [Users, Groups & Group Policy](./lab02-users-groups-gpo) | ADUC, password resets, account unlocks, GPO, PowerShell | ⏳ Planned |
| 03 | [Microsoft 365 & Entra ID](./lab03-m365-entra) | User and licence management, MFA, Exchange Online, Teams, OneDrive | ⏳ Planned |
| 04 | [Microsoft Intune](./lab04-intune) | Device enrolment, compliance and configuration policies, app deployment, BitLocker | ⏳ Planned |
| 05 | [Troubleshooting & Ticketing](./lab05-troubleshooting-tickets) | Windows and Outlook issues, printers, network diagnostics, ServiceNow tickets | ⏳ Planned |

---

## 🛠️ Skills Demonstrated

- **Windows Server:** AD DS, DNS, DHCP, Group Policy
- **Identity:** Active Directory, Microsoft Entra ID, MFA
- **Endpoint management:** Microsoft Intune, Windows 11 deployment and configuration
- **Microsoft 365:** Exchange Online, Teams, OneDrive, SharePoint
- **Networking:** TCP/IP, DNS and DHCP troubleshooting, `ipconfig`, `nslookup`, `ping`, `tracert`
- **Scripting:** PowerShell for AD administration
- **ITSM:** incident logging, triage and escalation (ServiceNow)

---

## 📝 How Each Lab Is Documented

Each lab folder contains:

1. **Objective:** what the lab sets out to achieve
2. **Steps:** a step-by-step build with screenshots
3. **Verification:** how I confirmed it works
4. **Issues & fixes:** real problems I hit and how I resolved them
5. **Interview notes:** how the skill applies in a real desktop support role

---

> ⚠️ All labs use Microsoft evaluation software in an isolated lab environment. No production systems or real user data are involved.
