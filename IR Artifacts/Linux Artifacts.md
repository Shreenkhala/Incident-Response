# Linux Artifacts for Incident Response

In an incident response scenario, the following Linux artifacts should be collected to analyze and respond effectively:

## Process and Memory Information
- Running Processes
- Parent-Child Process Trees
- Memory Dumps
- Active Kernel Modules

## User and Software Data
- Users and Groups (e.g., `/etc/passwd`, `/etc/shadow`)
- Installed Packages
- System Logs (e.g., `/var/log/`)

## Network Information
- Established Connections
- Listening Ports
- Firewall Rules
- DNS Cache

## Filesystem and Persistence Mechanisms
- Scheduled Cron Jobs
- Recently Modified or Created Files
- File Integrity Checks (e.g., `sha256sum` comparisons)
- Auto-start Entries (e.g., `rc.local`, Init Scripts)

## Relevant Logs and Execution Traces
- Command History (`~/.bash_history`, ZSH history, etc.)
- Audit Logs (e.g., `auditd`)
- System Logs (`journalctl`, `/var/log/syslog`, `/var/log/messages`)

## Security and Intrusion Detection
- SELinux Logs
- Anti-virus and Intrusion Detection Logs

## Kernel and Boot
- Kernel Logs (`dmesg`)
- Boot Logs (`/var/log/boot.log`, `grub` configurations)

## File and Directory Permissions
- World-Writable Files and Directories
- SUID/SGID File Listings

These artifacts help identify malicious activity, persistence mechanisms, network connections, and unauthorized access. They provide a foundation for effective analysis and response to incidents.