# Linux Fundamentals Cheat Sheet (Task 2)

## File System Navigation

| Command | Purpose | Example |
| :--- | :--- | :--- |
| `pwd` | Print Working Directory (Show current location) | `pwd` |
| `ls -l` | List contents (long format) | `ls -l /etc/` |
| `cd` | Change Directory | `cd /var/log` |
| `mkdir` | Make Directory | `mkdir projects` |
| `touch` | Create an empty file | `touch lab.txt` |
| `mv` | Move or rename file/directory | `mv lab.txt report.txt` |

## File & Directory Permissions

| Command | Purpose | Example |
| :--- | :--- | :--- |
| `chmod 700` | Give user full access, deny all others (rwx------) | `chmod 700 private.sh` |
| `chown` | Change file owner | `sudo chown root config.ini` |

## Networking Commands

| Command | Purpose | Example |
| :--- | :--- | :--- |
| `ip addr` | View network interface configurations and IP address. | `ip addr show eth0` |
| `ping -c 4` | Test connectivity to a host (send 4 packets). | `ping -c 4 192.168.56.102` |
| `netstat -tuln` | View TCP/UDP ports in a listening state. | `netstat -tuln` |
