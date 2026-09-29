
**IT Support | Windows | Linux | Networking | Infrastructure**

I work with IT support, system installation, troubleshooting, virtualization, networking, remote access and self-hosted infrastructure.

My current focus is building practical projects that improve my experience with Linux, servers, automation, networking and technical support.

---

## Skills

- Windows 10/11
- Linux
- IT Support
- Troubleshooting
- Hardware & Software Support
- System Installation & Configuration
- Networking
- TCP/IP, DHCP and DNS fundamentals
- SSH and Remote Access
- VirtualBox
- Docker
- Git & GitHub
- PowerShell / BAT
- Technical Documentation

---

## Projects

### ARGOS — Local AI Server
**Status:** Functional / In development

Local AI server built in a virtualized Ubuntu Server environment.

**Technologies**
- Ubuntu Server
- Docker
- Ollama
- Open WebUI
- SSH
- Local networking

**Implemented**
- Local LLM hosting
- Web interface for model access
- Remote administration through SSH
- Network access from other devices
- Workflow and endpoint experiments
- VM snapshots and recovery checkpoints

---

### NADIR — Private Cloud
**Status:** Functional

Self-hosted private cloud focused on personal storage, remote access and local network integration.

**Technologies**
- UmbrelOS
- SMB
- Tailscale
- Virtualization
- Self-hosted services

**Implemented**
- Private file storage
- Windows network share integration
- Remote access through Tailscale
- Mapped network drive on Windows
- Cross-device file access
- Self-hosted service testing

---

### VESPER — Pocket Linux
**Status:** Functional / In development

Portable Linux environment running on Android through Termux.

**Technologies**
- Termux
- Linux CLI
- Python
- Git
- SSH

**Implemented**
- Portable command-line environment
- SSH access to remote systems
- Git/GitHub workflow
- Python scripts
- Remote administration experiments
- Integration with ARGOS

---

### GHOST — Portable Diagnostic Terminal
**Status:** In development

Portable diagnostic environment designed for authorized system and network troubleshooting.

**Technologies**
- Debian Linux
- Python
- SSH
- Web interface
- Networking

**Planned / In progress**
- Portable diagnostic toolkit
- Local web dashboard
- Network troubleshooting tools
- Ethernet-based diagnostics
- Raspberry Pi deployment

---

### CYPHER — Virtual Infrastructure Lab
**Status:** In development

Virtual lab designed to simulate a small corporate infrastructure for study and testing.

**Technologies / Planned stack**
- Windows Server
- Active Directory
- DNS
- DHCP
- Windows clients
- OPNsense
- Zabbix
- VirtualBox

**Goals**
- Build a domain environment
- Configure users and policies
- Study enterprise networking
- Practice remote administration
- Monitor infrastructure and services

---

## Current Focus

- Improving Linux administration
- Expanding Windows troubleshooting skills
- Learning backend development and APIs
- Building automation workflows
- Documenting real infrastructure projects

---

## Contact

- **GitHub:** Akemi-Veyrath
- **Discord:** ak_veyrath
- **Email:** Akemiveyrath@gmail.com
"""

path = Path("/mnt/data/README_Akemi_Veyrath_Portfolio.md")
path.write_text(content, encoding="utf-8")
print(path)

Add profile README;
