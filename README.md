# Linux Administration Labs

A practical, continuously maintained portfolio of Linux administration labs and projects. This repository documents my learning through **university coursework** and, in parallel, the **Linux (LPIC-1) course by Quera College**, taught by **Jadi Mirmirani**.

The focus is on applying Linux concepts in a real Ubuntu environment, understanding system behaviour, troubleshooting issues, automating repetitive tasks, and preparing to operate and deploy software on Linux servers.

> **Learning context:** University coursework and the Quera LPIC-1 course are two parallel learning sources. The labs and projects here are my own practical exercises and documentation; they are not presented as official university or Quera assignments. This repository does not claim an LPIC-1 certification.

## Learning roadmap

This roadmap combines Linux fundamentals, LPIC-1-aligned topics, and practical skills commonly used in Linux administration, backend operations, and junior DevOps roles. Statuses describe work published in this repository, not course completion or certification progress.

| # | Topic | Key skills and tools | Status |
|---|---|---|---|
| 01 | Linux System Overview | Architecture, kernel, shell, user space, boot process, system information | In Progress |
| 02 | Command Line & GNU Utilities | Navigation, file operations, text processing, pipes, redirection, grep, find, man | Planned |
| 03 | Filesystems & Permissions | FHS, paths, links, ownership, chmod, chown, umask, mounts | Planned |
| 04 | Users, Groups & Access Control | Account management, sudo, account files, least privilege | Planned |
| 05 | Processes & Job Control | Process states, signals, jobs, priorities, ps, top, kill | Planned |
| 06 | Package Management | APT, repositories, installation, updates, package troubleshooting | Planned |
| 07 | Bash & Shell Automation | Variables, quoting, conditions, loops, functions, exit codes, robust scripts | Planned |
| 08 | Storage, Backup & Scheduling | Disks, partitions, filesystems, tar, gzip, cron, restore procedures | Planned |
| 09 | Services, systemd & Logs | systemctl, service units, journalctl, log inspection, troubleshooting | Planned |
| 10 | Linux Networking | IP addressing, routes, DNS, ports, sockets, connectivity diagnostics | Planned |
| 11 | SSH & Linux Security | SSH keys, secure remote access, firewall basics, updates, hardening | Planned |
| 12 | Monitoring & Troubleshooting | CPU, memory, disk, processes, logs, resource diagnosis, incident investigation | Planned |

### Practical projects

| Project | What it demonstrates | Status |
|---|---|---|
| [01 — Automated Backup System](projects/01-automated-backup/README.md) | Bash automation, archives, retention, cron, logging, validation and restore | Planned |
| [02 — Linux System Monitor](projects/02-linux-system-monitor/README.md) | Resource inspection, process/service checks, thresholds, reports and logs | Planned |
| [03 — Node.js Application Deployment](projects/03-nodejs-linux-deployment/README.md) | Linux setup, SSH, Node.js, systemd, Nginx, deployment and troubleshooting | Planned |

## Repository structure

```text
linux-admin-labs-lpic/
├── README.md
├── LICENSE
├── .gitignore
├── labs/
│   ├── 01-linux-system-overview/
│   ├── 02-command-line-and-gnu-utilities/
│   ├── 03-filesystems-and-permissions/
│   ├── 04-users-and-groups/
│   ├── 05-processes-and-job-control/
│   ├── 06-package-management/
│   ├── 07-bash-and-shell-scripting/
│   ├── 08-storage-backup-and-scheduling/
│   ├── 09-services-systemd-and-logs/
│   ├── 10-linux-networking/
│   ├── 11-ssh-and-linux-security/
│   └── 12-monitoring-and-troubleshooting/
├── projects/
│   ├── 01-automated-backup/
│   ├── 02-linux-system-monitor/
│   └── 03-nodejs-linux-deployment/
└── resources/
    └── references.md
```

Each lab and project has its own README so exercises, evidence, troubleshooting notes, and improvements can be added incrementally. Implementation files will be added when the relevant work is actually completed.

## Lab documentation standard

Each lab should record:

- **Objective:** what the exercise demonstrates.
- **Environment:** distribution, version, kernel, shell, and relevant tools.
- **Concepts covered:** the Linux concepts behind the task.
- **Practical exercises:** commands and tasks performed.
- **Evidence and output:** real, sanitized command output or test results.
- **Troubleshooting:** errors, diagnosis, and resolution.
- **Safety and cleanup:** risks of privileged/destructive commands and how changes are reverted.
- **What I learned:** concise takeaways and remaining questions.
- **References:** official documentation and course material.

Commands will not be listed as completed exercises until they have been run and verified.

## Environment

- Primary practice environment: **Ubuntu Linux (native installation)**.
- Main administration and automation shell: **Bash**.
- Version control: **Git**.
- Exact Ubuntu and kernel versions will be recorded after checking the practice machine.

## Learning approach

1. Study concepts through university coursework and the Quera LPIC-1 course.
2. Reproduce them in the Ubuntu environment.
3. Explain commands and inspect actual output.
4. Investigate errors instead of hiding them.
5. Add focused changes to the relevant lab or project.
6. Validate scripts/configurations before documenting them as working.
7. Commit each meaningful step with a descriptive message.

Suggested commit messages:

- `docs: add Linux system overview lab`
- `feat: implement automated backup script`
- `fix: handle missing backup source directory`
- `test: add backup script validation scenarios`
- `docs: document backup restoration process`

## Learning references

- **Quera College:** [Linux (LPIC-1) — Free Course](https://quera.org/college/landpage/25249/linux-lpic1-free)
- **Instructor:** Jadi Mirmirani
- **University coursework:** Linux and related systems topics studied as part of university learning. Specific course references can be added when documented.
- **LPIC-1 objectives:** [Linux Professional Institute](https://www.lpi.org/our-certifications/lpic-1-overview/)

Third-party course materials remain the property of their respective owners. The MIT license applies to original repository content and code, not third-party materials.

## Current focus

The immediate focus is **Lab 01 — Linux System Overview** on native Ubuntu. Environment details, commands, outputs, and findings will be added after they have been run and verified.

---

Learning by doing, testing, troubleshooting, and documenting.
