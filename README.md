# Hi, I'm Colin 👋

**Systems Administrator · Endpoint, Identity & Cloud Engineer · U.S. Army Veteran**
Denver, Colorado · Bilingual (English / Spanish) · CISSP · GIAC GSEC / GCIH

I like the problems that don't come with an error code: the app that hangs with no
log, the installer that fails on one machine and nowhere else. My approach is to
measure first (Process Monitor, debuggers, event logs, driver stacks), find the actual
cause, and then automate the fix so nobody has to do it by hand again.

About five years in IT, from enterprise help desk to hands-on systems administration
across hybrid **Active Directory / Entra ID**, **Intune**, **Microsoft 365**, **Azure**
and **AWS**. Before IT I served as an Army Military Police officer (Operation Iraqi
Freedom) and spent a decade investigating insurance claims, so root-causing problems
under pressure is a habit, not a buzzword.

## What I do now

IT Support Engineer / Systems Administrator at **BKV Corporation** (Denver HQ):

- Sole on-site IT for corporate HQ, supporting up to the C-suite in a hybrid
  AD / Entra ID, M365, Azure and AWS environment: **~1,100 Intune-managed Windows
  endpoints** and **430+ AWS WorkSpaces**
- Whole-tenant Azure administration, hybrid identity, Intune endpoint and app management,
  Exchange, SharePoint, Teams, licensing, security tooling rollouts, and Autopilot provisioning
- **Co-led the enterprise rollout of Claude and ChatGPT**: Entra SSO, AD-synced license
  groups, provisioning across the M365 tenant
- **Integrated AI agents with production systems** (ServiceNow SDK with OAuth, Microsoft
  Graph, Exchange Online, Entra ID, Intune, Azure, AWS SSO CLI) under approval-gated,
  audited workflows
- Built and version-controlled the IT team's AI workspace (playbooks, runbooks, agent
  instructions, onboarding/offboarding automation)
- ServiceNow administration, Change Advisory Board, asset and license management

## Certifications

| Area | Certifications |
|---|---|
| **Security** | ![CISSP](https://img.shields.io/badge/ISC2-CISSP-1f6f3f?style=flat) ![GCIH](https://img.shields.io/badge/GIAC-GCIH-b22222?style=flat) ![GSEC](https://img.shields.io/badge/GIAC-GSEC-1d4f91?style=flat) ![GFACT](https://img.shields.io/badge/GIAC-GFACT-6a2c91?style=flat) ![Security+](https://img.shields.io/badge/CompTIA-Security%2B-c8102e?style=flat) ![Palo Alto](https://img.shields.io/badge/Palo%20Alto-Network%20Security%20Professional-fa582d?style=flat) |
| **Microsoft** | ![AZ-104](https://img.shields.io/badge/AZ--104-Azure%20Administrator-0078D4?style=flat&logo=microsoftazure&logoColor=white) ![MD-102](https://img.shields.io/badge/MD--102-Endpoint%20Administrator-0078D4?style=flat&logo=windows&logoColor=white) ![AZ-900](https://img.shields.io/badge/AZ--900-Azure%20Fundamentals-0078D4?style=flat) ![MS-900](https://img.shields.io/badge/MS--900-M365%20Fundamentals-0078D4?style=flat) |
| **Cloud & Infrastructure** | ![AWS](https://img.shields.io/badge/AWS-Cloud%20Practitioner-232F3E?style=flat&logo=amazonwebservices&logoColor=white) ![Cloud+](https://img.shields.io/badge/CompTIA-Cloud%2B-c8102e?style=flat) ![Linux+](https://img.shields.io/badge/CompTIA-Linux%2B-c8102e?style=flat) ![Network+](https://img.shields.io/badge/CompTIA-Network%2B-c8102e?style=flat) |
| **ITSM** | ![ServiceNow CSA](https://img.shields.io/badge/ServiceNow-Certified%20System%20Administrator-62D84E?style=flat&logo=servicenow&logoColor=white) ![Advanced ITSM](https://img.shields.io/badge/ServiceNow-Advanced%20ITSM-62D84E?style=flat) |

Also: Responsible Generative AI Specialization (University of Michigan), SANS Foundations,
Google IT Support Professional Certificate, Cisco CCNA 1 & 2 (Networking Academy),
Windows Server 2019 Administration.

## What I work with

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat&logo=windows&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra%20ID-0078D4?style=flat&logo=microsoft&logoColor=white)
![Intune](https://img.shields.io/badge/Intune-0078D4?style=flat&logo=microsoft&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft%20365-D83B01?style=flat&logo=microsoftoffice&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![ServiceNow](https://img.shields.io/badge/ServiceNow-62D84E?style=flat&logo=servicenow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20Code-D97757?style=flat&logo=anthropic&logoColor=white)

- **Identity & endpoint:** hybrid AD / Entra ID, Intune, Autopilot, Defender for Endpoint, SCCM
- **Cloud:** Azure tenant administration, AWS (WorkSpaces, IAM, SSO CLI)
- **Collaboration:** Exchange Online, SharePoint, Teams, M365 licensing
- **Security:** incident handling, vulnerability remediation, CrowdStrike, Rapid7, Palo Alto Prisma, Netskope
- **Networking:** TCP/IP, firewalls and ACLs, VPN, wireless, UniFi, Cisco
- **Automation & AI:** PowerShell 5/7, Python, Microsoft Graph SDK, ServiceNow SDK (Fluent),
  MCP servers, Claude Code, Claude / ChatGPT Enterprise administration
- **Troubleshooting:** Sysinternals (Process Monitor), WinDbg, DISM, event logs

## Featured project

### [usb-builder](https://github.com/gitColinX/usb-builder)
PowerShell tooling that builds Windows 11 installer USB sticks with an unattended
answer file and per-model Dell drivers, without Rufus. It started as a Rufus format
failure I traced with Process Monitor and the tool's own logs to a partition-layout
bug, then designed around: a single GPT/FAT32 layout, a DISM-split image, and drivers
staged so the SSD and network work on first boot.

`PowerShell` · `DISM` · `Windows Setup / autounattend` · `Dell driver packs`

## Education

- **B.S. Cybersecurity Technology**, University of Maryland Global Campus (in progress, expected 2027)
- **SANS Institute**: undergraduate cybersecurity coursework (GFACT, GSEC, GCIH)
- **Network Support Specialist Program**, ACI Tech Academy (2022)

## Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-cdlundholm-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cdlundholm)
