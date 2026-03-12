# Chaty DevOps

**Secure Offline DevOps Workstation for VPS & Dedicated Servers**

Chaty DevOps is a desktop application that unifies terminal access, file management, deployment workflows, log monitoring, and API testing into a single secure environment — designed for developers who prefer stable, controlled infrastructure management without relying on cloud-based DevOps platforms.

The application operates entirely offline, keeping all credentials, server configurations, and license data securely stored on the local machine.

---

## 🚀 What Is This Repository?

This public repository hosts the **official release builds** of Chaty DevOps.

The core application source code is maintained privately.

You can download the latest builds from the Releases section.

👉 **Download here**  
https://github.com/chatyshop/chaty_devops/releases

Available packages:

- **Windows Installer (.exe)**
- **Linux AppImage**

---

## 🔧 Core Capabilities

Chaty DevOps consolidates common DevOps tools into a single workstation environment.

Key features include:

- Multi-workspace interactive SSH terminals
- Secure remote command execution
- Integrated SFTP file management
- Deployment workflows with dry-run validation
- Real-time server log monitoring
- Built-in API request testing
- Device-bound offline licensing
- Fully offline infrastructure management

The platform reduces context switching by replacing multiple tools such as SSH clients, SFTP tools, log viewers, deployment scripts, and API testing utilities.

---

## 🏗 System Architecture

Chaty DevOps follows a layered desktop architecture designed for reliability and security.

Core internal services include:

- Terminal Service
- SSH Service
- SFTP Service
- Deployment Service
- Log Monitoring Service
- API Testing Service
- Server Configuration Service
- License Service

Each module is isolated and responsible for a specific part of the DevOps workflow.

---

## 🛡 Security Model

Security is a fundamental design principle of Chaty DevOps.

Key protections include:

- AES-256-GCM encryption for stored credentials
- Device-bound encryption keys
- Offline license verification
- Ed25519 signed licenses
- Tamper-resistant licensing system
- Controlled IPC boundaries
- Session isolation per workspace

Sensitive data is encrypted before being stored locally, ensuring that credentials are never written to disk in plaintext.

---

## 🌐 Offline-First Architecture

Chaty DevOps is designed to run **entirely offline**.

The system does **not require**:

- cloud services
- backend APIs
- external authentication servers
- internet connectivity

All functionality runs locally on the user’s machine.

Benefits include:

- improved security
- enhanced privacy
- reduced attack surface
- faster local execution
- compatibility with restricted network environments

---

## 🖥 Supported Environment

### Client

- Windows 10 / 11 (64-bit)
- Linux (AppImage compatible distributions)

### Remote Servers

Chaty DevOps supports any Linux server accessible via SSH, including:

- Ubuntu
- Debian
- CentOS / Rocky / AlmaLinux
- Amazon Linux
- Other Linux distributions with SSH enabled

---

## 📦 Latest Version

Current Release: **v1.2.5**  
Status: Early Access  
Release Date: 12 March 2026

See full release notes in the **Releases** section.

---

## 🌐 Official Website

https://devland.chatyshop.com/

---

## 📬 Feedback & Support

For feedback, questions, or installer-related issues:

- Open a **GitHub Issue**
- Use the **Contact page** on the official website

---

Chaty DevOps is built as a focused workstation for developers and DevOps engineers who prefer secure, controlled infrastructure management without relying on cloud DevOps platforms.
