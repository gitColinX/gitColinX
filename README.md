# Hi, I'm Colin 👋

**IT Support · Systems Engineering & Administration · Azure · ServiceNow · Cybersecurity research**
Based in Colorado. Currently at BKV Corp.

I like the problems that don't come with an error code: the app that hangs with no
log, the installer that fails on one machine and nowhere else. My approach is to
measure first (Process Monitor, debuggers, event logs, driver stacks), find the actual
cause, and then automate the fix so nobody has to do it by hand again.

## What I work with

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat&logo=windows&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![ServiceNow](https://img.shields.io/badge/ServiceNow-62D84E?style=flat&logo=servicenow&logoColor=white)
![Sysinternals](https://img.shields.io/badge/Sysinternals-333333?style=flat&logo=windows&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

- **Windows administration & deployment**: imaging, unattended installs, drivers, troubleshooting
- **Cloud**: Azure administration
- **ITSM**: ServiceNow, including the ServiceNow SDK
- **Security**: cybersecurity research
- **Automation**: PowerShell tooling, with AI-assisted workflows where they help

## Featured project

### [usb-builder](https://github.com/gitColinX/usb-builder)
PowerShell tooling that builds Windows 11 installer USB sticks with an unattended
answer file and per-model Dell drivers, without Rufus. It started as a Rufus format
failure I traced with Process Monitor and the tool's own logs to a partition-layout
bug, then designed around: a single GPT/FAT32 layout, a DISM-split image, and drivers
staged so the SSD and network work on first boot.

`PowerShell` · `DISM` · `Windows Setup / autounattend` · `Dell driver packs`

## Get in touch

Open an issue on any of my repos, or connect through GitHub.
