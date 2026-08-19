# Chaty DevOps

**Secure, offline-first DevOps workstation for VPS and dedicated servers.**

Chaty DevOps is a desktop application that brings server access, deployments, monitoring, Nginx management, logs, and API testing into one local workspace. It is built for developers who want direct, controlled infrastructure management without depending on a hosted DevOps platform.

Your server profiles, credentials, workspace data, and license information stay on your own machine. Chaty DevOps does not require a Chaty cloud backend to manage your infrastructure.

---

## Downloads

This public repository contains the official Chaty DevOps release builds. The application source code is maintained privately.

Download the latest available package from [Releases](https://github.com/chatyshop/chaty_devops/releases):

- Windows installer (`.exe`)
- Linux AppImage (`.AppImage`), when available for that release

## Latest release

**Current release:** v1.3.0  
**Status:** Early Access  
**Release date:** 19 August 2026

### v1.3.0 highlights

- Deploy now saves service settings on each server for one-click dry runs and redeployments.
- Upload, inspect, edit, add, remove, and securely apply environment variables without including `.env` files in normal project uploads.
- Environment changes restart PM2 applications with updated variables; static and custom deployments rerun their saved deployment command.
- Deployment activity includes clearer progress, compact live logs, and cancellation controls.
- Nginx can discover existing deployed services and prepare them for deployment configuration on a new PC.
- SSL setup supports optional `www` and additional comma-separated domains, with automatic certificate renewal setup.
- SSL and Health now inspect Nginx's active configuration, improving support for sites created by earlier app versions or custom config filenames.
- Linux AppImage and Windows installer builds are available for this release.

See the release notes for package-specific changes and installation instructions.

---

## What you can do with Chaty DevOps

### Connect and manage servers

- Save server profiles and organize work by environment
- Open multi-workspace interactive SSH terminals
- Run remote commands securely
- Browse and transfer files with integrated SFTP
- Keep a terminal workspace available while reviewing Monitoring, Logs, or other modules

### Provision AWS VPS instances

- Connect your AWS IAM access key locally
- Create and manage beginner-friendly Amazon EC2 VPS instances
- Create or select key pairs and server settings
- Assign managed instances to Development, Staging, or Production so each environment stays focused
- Resize supported instances and EBS volumes from the app; where supported, Chaty can also expand the remote Linux filesystem
- Show a disk-aware monthly estimate before and after infrastructure changes
- Move from AWS provisioning to SSH, deploy, monitoring, and Nginx in one workflow

### Deploy applications with confidence

- Guided static-app and server-app deployment flows
- Preview commands before execution with dry-run validation
- Validate PM2 and target-directory requirements before deployment where applicable
- Track live deployment output and deployment history
- Keep deployment actions connected to the selected server

### Monitor server health

- View CPU, memory, disk, uptime, and server status
- Refresh individual servers or the full environment
- Configure polling intervals independently for Development, Staging, and Production
- Identify warning and critical resource usage early
- Inspect active TCP and UDP listening ports, including the owning process

### Manage Nginx, reverse proxy, and SSL

- Create static-hosting or reverse-proxy Nginx sites
- Validate configuration before applying changes
- Reload or restart Nginx and inspect access/error logs
- Run health checks for DNS, backend reachability, Nginx configuration, and ports 80/443
- Configure SSL for a real domain and monitor HTTPS readiness

### Troubleshoot and test

- Stream and search server logs with filtering, history, and export
- Detect unusually frequent suspicious web requests and surface an in-app security alert
- Send API requests from the built-in API testing workspace and save frequently used requests
- Keep terminal, logs, deployment, and server context in one desktop app

---

## Why use it instead of separate tools?

| If you use separate tools | With Chaty DevOps |
| --- | --- |
| AWS Console for EC2 | AWS provisioning and server setup inside Chaty DevOps |
| SSH client for commands | Saved servers and multi-terminal workspaces |
| FTP/SFTP client for files | Integrated remote file browsing and transfers |
| Deployment scripts and terminal windows | Guided deployments, dry runs, and live deployment logs |
| Browser/terminal for Nginx | Create sites, reverse proxy, validate config, reload, and inspect logs |
| Manual server checks | CPU, memory, disk, uptime, Nginx health, and listening-port visibility |
| Postman or curl for APIs | Built-in API testing |
| `tail` and `grep` for troubleshooting | Live logs, search, filters, history, and export |

---

## Security and privacy

Chaty DevOps is designed around local control:

- AES-256-GCM encryption for stored credentials
- Device-bound encryption keys
- Ed25519-signed, offline license verification
- Controlled desktop IPC boundaries and per-workspace session isolation
- No Chaty-hosted server is required for SSH, SFTP, deployment, monitoring, or Nginx management
- Environment switches warn before active terminal sessions, deployments, or file transfers are cancelled

Chaty DevOps is **offline-first**, not disconnected from your own infrastructure: internet or network access is only needed when you deliberately connect to AWS, a remote server, an API, or a certificate authority for SSL.

---

## Free 60-day evaluation

1. Download and install Chaty DevOps.
2. Create an account on the official website.
3. In the dashboard, select **Buy Now** on the Free plan to claim your free evaluation.
4. Receive one device-bound license key valid for **60 days**.
5. Activate the key inside the Chaty DevOps desktop app.

No payment is required for the 60-day evaluation. A license key is still required to activate the application on your device.

---

## Supported environments

### Client

- Windows 10 / 11 (64-bit)
- Linux distributions compatible with the provided AppImage

### Remote servers

Any Linux server reachable through SSH, including:

- Ubuntu
- Debian
- CentOS, Rocky Linux, and AlmaLinux
- Amazon Linux
- Other Linux distributions with SSH enabled

---

## Quick start

1. Download the package for your operating system from [Releases](https://github.com/chatyshop/chaty_devops/releases).
2. Install the app and activate your license key.
3. Add a server through SSH, or create an EC2 VPS using the AWS VPS Launcher.
4. Use Deploy, Monitoring, Nginx, Logs, and API Test to manage the selected environment.

---

## Official website and support

- Website: [devland.chatyshop.com](https://devland.chatyshop.com/)
- Feedback and issues: open a [GitHub Issue](https://github.com/chatyshop/chaty_devops/issues)
- Product and account questions: use the Contact page on the official website

Chaty DevOps is a focused workstation for developers and DevOps engineers who prefer secure, direct, and controlled infrastructure management.
