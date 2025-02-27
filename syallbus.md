📖 Objective

This repository serves as a comprehensive study guide to master Linux and Shell Scripting, tailored for DevOps and SRE roles with 3+ years experience.

📋 Table of Contents

#	Section
1️⃣	Linux Fundamentals
2️⃣	Shell Scripting Basics
3️⃣	Text Processing & File Handling
4️⃣	Advanced Shell Scripting
5️⃣	Automation & Scheduling
6️⃣	DevOps-Specific Scripting
7️⃣	Real-World Challenges
8️⃣	Suggested Study Plan
9️⃣	Study Tips
🔗	Useful References
1️⃣ Linux Fundamentals

Topic	Subtopics
File & Directory Management	ls, mkdir, rm, cp, mv, find, stat
File Permissions & Ownership	chmod, chown, umask, ACL, symbolic vs numeric permissions
User & Group Management	useradd, usermod, passwd, groups, /etc/passwd, /etc/group
Process Management	ps, top, htop, kill, jobs, bg, fg, nice, renice
Disk & Memory Management	df, du, free, iostat, vmstat
Networking	ip, ping, netstat, ss, curl, wget, nc
2️⃣ Shell Scripting Basics

Topic	Subtopics
Shell Types	bash, zsh, dash
Running Scripts	Execute with ./, bash, sh
Command Line Arguments	$1, $2, $#, "$@", getopts
Variables & Environment	VAR=value, export VAR, read VAR, scope (local/global)
Exit Codes & Error Handling	$?, exit, set -e, if conditions
Debugging & Logging	echo, set -x, trap
Loops & Conditions	for, while, until, if, case
3️⃣ Text Processing & File Handling

Tool	Purpose
cat, echo	Basic file I/O
grep	Pattern matching
awk	Column extraction & processing
sed	Stream editing
cut	Column cutting
sort, uniq	Sorting & de-duplication
xargs	Argument passing
find	File discovery
jq/yq	JSON/YAML processing
4️⃣ Advanced Shell Scripting

Topic	Subtopics
Functions	Define, call, pass arguments, return values
Background Jobs	&, wait, xargs -P
Signal Handling	trap, SIGINT, SIGTERM, EXIT
Here Documents & Strings	<<EOF, <<<
Process Substitution	<(command)
5️⃣ Automation & Scheduling

Task	Tools/Commands
Job Scheduling	cron, systemd timers
Log Rotation	logrotate
File Cleanup	find -mtime, rm
Backup Automation	tar, gzip, rsync, scp
6️⃣ DevOps-Specific Scripting

Use Case	Commands/Tools
Health Checks	curl, ping, nc, process status check
Resource Monitoring	free, df, top, iostat
Backup & Restore	tar, scp, rsync
Service Management	systemctl, service
Safe Scripting	Sudo handling, safe file processing (IFS, quotes)
7️⃣ Real-World Challenges

Challenge	Skills Practiced
Log Analysis Script	grep, awk, sed, error filtering
Disk Monitoring Script	df, awk, threshold alerts
Directory Backup Script	tar, gzip, scp, rsync
Process Watchdog	ps, grep, systemctl restart
Log Cleanup Cronjob	find, rm, date calculations
