# Project 03 — Node.js Application Deployment on Linux

**Status:** Planned  
**Application:** A Node.js / TypeScript API  
**Focus:** Linux operations and deployment, not application feature development

## Goal

Deploy and operate a Node.js API as a service in a Linux environment. Connect backend development experience with practical Linux server administration.

## Planned capabilities

- [ ] Prepare and update an Ubuntu server environment.
- [ ] Configure a dedicated, non-root application user.
- [ ] Install and verify a supported Node.js runtime.
- [ ] Configure environment variables without committing secrets.
- [ ] Deploy the API and install production dependencies.
- [ ] Run the application with a systemd service unit.
- [ ] Configure Nginx as a reverse proxy.
- [ ] Configure SSH access and key-based authentication.
- [ ] Inspect application and system logs.
- [ ] Test service restart, failure recovery and deployment updates.
- [ ] Document firewall and network requirements.

## Concepts and tools

Linux users and permissions, SSH, Node.js, npm, environment configuration, systemd, Nginx, ports, logs, process management and troubleshooting.

## Planned structure

```text
03-nodejs-linux-deployment/
├── README.md
├── deployment/
│   ├── systemd/
│   └── nginx/
├── scripts/
├── docs/
└── evidence/
```

Configuration examples must use placeholders. Never commit private keys, credentials, production environment files, or personal server details.

## Validation plan

Verify local application health, service startup after reboot, reverse-proxy behaviour, access restrictions, log visibility, and recovery after an intentional test failure.

## Results

To be documented after implementation and testing.
