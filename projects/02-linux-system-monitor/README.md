# Project 02 — Linux System Monitor

**Status:** Planned  
**Primary language:** Bash (Python may be considered as a later extension)

## Goal

Create a lightweight command-line tool that collects useful Linux health information and produces a readable report.

## Planned capabilities

- [ ] CPU load and utilization indicators.
- [ ] Memory and swap usage.
- [ ] Disk usage and filesystem capacity.
- [ ] Top resource-consuming processes.
- [ ] Selected systemd service status checks.
- [ ] Timestamped reports and logging.
- [ ] Configurable warning thresholds.
- [ ] Clear handling of unavailable tools or permissions.

## Concepts and tools

Bash, procps utilities, filesystem tools, systemd, systemctl, journalctl, process inspection and basic performance troubleshooting.

## Planned structure

```text
02-linux-system-monitor/
├── README.md
├── monitor.sh
├── config/
├── tests/
└── examples/
```

## Validation plan

Compare reported values with trusted system utilities, test missing commands and permission restrictions, and verify threshold behaviour using controlled test inputs.

## Results

To be documented after implementation and testing.
