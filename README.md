This project automates the installation and configuration of **Auditd** on a **Ubuntu 24.x** virtual machine using **Ansible** and **GitHub**.  
Auditd (Linux Auditing System) is essential for monitoring system activities, providing traceability, and enhancing security compliance.  

The Ansible playbook:
- Installs and enables Auditd.
- Applies custom configurations (`audit.conf`).
- Deploys custom audit rules (`audit.rules`).
- Ensures Auditd starts automatically at boot.

---

## 🧩 System Requirements
| Component | Version | Notes |
|------------|----------|-------|
| **Ubuntu** | 24.x LTS | Tested on Ubuntu 24.04 |
| **Ansible** | 2.14+ | Installed via apt |
| **Git** | Latest | Required for ansible-pull |
| **Internet Access** | Yes | To fetch playbook from GitHub |

---

## 📁 Repository Structure

