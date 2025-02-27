# Linux & Shell Scripting Guide for DevOps

A comprehensive guide to mastering Linux fundamentals and shell scripting for DevOps professionals.

## Table of Contents

- [1. Linux Fundamentals](#1-linux-fundamentals)
- [2. Shell Scripting Basics](#2-shell-scripting-basics)
- [3. Text Processing & File Handling](#3-text-processing--file-handling)
- [4. Advanced Shell Scripting](#4-advanced-shell-scripting)
- [5. Automation & Scheduling](#5-automation--scheduling)
- [6. DevOps-Specific Scripting](#6-devops-specific-scripting)
- [7. Real-World Challenges](#7-real-world-challenges)
- [8. Suggested Study Plan](#8-suggested-study-plan)
- [9. Study Tips](#9-study-tips)
- [10. Useful References](#10-useful-references)

## 1. Linux Fundamentals

| Topic | Subtopics |
|-------|-----------|
| File & Directory Management | `ls`, `mkdir`, `rm`, `cp`, `mv`, `find`, `stat` |
| File Permissions & Ownership | `chmod`, `chown`, `umask`, ACL, symbolic vs numeric permissions |
| User & Group Management | `useradd`, `usermod`, `passwd`, `groups`, `/etc/passwd`, `/etc/group` |
| Process Management | `ps`, `top`, `htop`, `kill`, `jobs`, `bg`, `fg`, `nice`, `renice` |
| Disk & Memory Management | `df`, `du`, `free`, `iostat`, `vmstat` |
| Networking | `ip`, `ping`, `netstat`, `ss`, `curl`, `wget`, `nc` |

## 2. Shell Scripting Basics

| Topic | Subtopics |
|-------|-----------|
| Shell Types | bash, zsh, dash |
| Running Scripts | Execute with `./`, `bash`, `sh` |
| Command Line Arguments | `$1`, `$2`, `$#`, `"$@"`, `getopts` |
| Variables & Environment | `VAR=value`, `export VAR`, `read VAR`, scope (local/global) |
| Exit Codes & Error Handling | `$?`, `exit`, `set -e`, if conditions |
| Debugging & Logging | `echo`, `set -x`, `trap` |
| Loops & Conditions | `for`, `while`, `until`, `if`, `case` |

## 3. Text Processing & File Handling

| Tool | Purpose |
|------|---------|
| `cat`, `echo` | Basic file I/O |
| `grep` | Pattern matching |
| `awk` | Column extraction & processing |
| `sed` | Stream editing |
| `cut` | Column cutting |
| `sort`, `uniq` | Sorting & de-duplication |
| `xargs` | Argument passing |
| `find` | File discovery |
| `jq`/`yq` | JSON/YAML processing |

## 4. Advanced Shell Scripting

| Topic | Subtopics |
|-------|-----------|
| Functions | Define, call, pass arguments, return values |
| Background Jobs | `&`, `wait`, `xargs -P` |
| Signal Handling | `trap`, `SIGINT`, `SIGTERM`, `EXIT` |
| Here Documents & Strings | `<<EOF`, `<<<` |
| Process Substitution | `<(command)` |

## 5. Automation & Scheduling

| Task | Tools/Commands |
|------|----------------|
| Job Scheduling | `cron`, systemd timers |
| Log Rotation | `logrotate` |
| File Cleanup | `find -mtime`, `rm` |
| Backup Automation | `tar`, `gzip`, `rsync`, `scp` |

## 6. DevOps-Specific Scripting

| Use Case | Commands/Tools |
|----------|----------------|
| Health Checks | `curl`, `ping`, `nc`, process status check |
| Resource Monitoring | `free`, `df`, `top`, `iostat` |
| Backup & Restore | `tar`, `scp`, `rsync` |
| Service Management | `systemctl`, `service` |
| Safe Scripting | Sudo handling, safe file processing (IFS, quotes) |

## 7. Real-World Challenges

| Challenge | Skills Practiced |
|-----------|-------------------|
| Log Analysis Script | `grep`, `awk`, `sed`, error filtering |
| Disk Monitoring Script | `df`, `awk`, threshold alerts |
| Directory Backup Script | `tar`, `gzip`, `scp`, `rsync` |
| Process Watchdog | `ps`, `grep`, `systemctl restart` |
| Log Cleanup Cronjob | `find`, `rm`, date calculations |

## 8. Suggested Study Plan

1. Master Linux fundamentals (2 weeks)
2. Learn shell scripting basics (2 weeks)
3. Practice text processing tools (1 week)
4. Develop advanced scripting skills (2 weeks)
5. Build automation scripts (2 weeks)
6. Apply to DevOps-specific tasks (ongoing)
7. Complete real-world challenges (ongoing)

## 9. Study Tips

- Use a virtual machine or container for practice
- Document commands and scripts in a personal notebook
- Create mini-projects that combine multiple concepts
- Contribute to open-source shell scripts
- Read well-written scripts from established projects
- Participate in troubleshooting forums

## 10. Useful References

- [The Linux Command Line](https://linuxcommand.org/tlcl.php) by William Shotts
- [Advanced Bash-Scripting Guide](https://tldp.org/LDP/abs/html/)
- [Shell Style Guide](https://google.github.io/styleguide/shellguide.html)
- [Bash Hackers Wiki](https://wiki.bash-hackers.org/)
- [ExplainShell](https://explainshell.com/) - Interactive command explanation
- [ShellCheck](https://www.shellcheck.net/) - Script analysis tool
