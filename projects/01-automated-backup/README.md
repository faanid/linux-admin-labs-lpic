# Project 01 — Automated Backup System

**Status:** Planned  
**Primary language:** Bash

## Goal

Build a reliable, configurable backup script for selected files and directories on Linux. Demonstrate safe shell scripting and practical backup/restore operations.

## Planned capabilities

- [ ] Validate source and destination paths.
- [ ] Create timestamped archives.
- [ ] Compress archives using gzip.
- [ ] Verify archive integrity.
- [ ] Implement configurable retention and safe cleanup.
- [ ] Record activity and errors in logs.
- [ ] Return meaningful exit codes and handle failures.
- [ ] Schedule backups with cron.
- [ ] Document and test restoration.
- [ ] Add dry-run mode before destructive operations.

## Concepts and tools

Bash, quoting, exit codes, filesystem permissions, tar, gzip, cron, logging, validation and restore testing.

## Planned structure

```text
01-automated-backup/
├── README.md
├── backup.sh
├── config/
│   └── backup.conf.example
├── tests/
└── examples/
```

Files will be added when implemented. Do not commit real backup data, secrets, or machine-specific paths.

## Validation plan

Test successful backups, missing source paths, unreadable files, unavailable destinations, archive integrity, retention boundaries, and restoration into a separate test directory.

## Results

To be documented after implementation and testing.
