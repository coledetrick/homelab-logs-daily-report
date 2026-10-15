# Homelab Daily Reports

A running, public log of what I build, break, and fix in my home lab: virtualization,
monitoring, networking, automation, and the tooling around it. Each entry is a short,
plain-English summary written at the end of the day.

Private details (addresses, hostnames, credentials, personal data) are removed before
anything is published. The focus is on the engineering: what was done, why, and what came of it.

## Reports

<!-- INDEX:START -->
| Date | Headline | Focus |
|---|---|---|
| [2026-10-14](reports/2026-10-14.md) | Established key-based SSH to every lab host, then used that access to rescue two VMs with full disks, restore a lost Grafana service, and repair a host that had no SSH at all through the hypervisor's guest agent. | Linux administration Virtualization Monitoring Automation |
<!-- INDEX:END -->

## How these are produced

A `/daily-report` command gathers the day's activity from local session logs, git history,
shell history, and container state, then distills it into a readable summary and runs a
privacy scrub before committing. The reports are written to be useful to a reader skimming
them for the first time.
