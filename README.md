# Linux User and Sudo Management Lab

This repository documents hands-on Linux user and privilege management
practiced on Ubuntu (WSL).

The goal of this lab is to understand how Linux handles users, groups,
sudo permissions, and root access in a real-world DevOps environment.

---

## Environment
- OS: Ubuntu (WSL)
- Shell: Bash
- Primary User: codenamebj (sudo user)

---

## Concepts Covered
- Linux users and groups
- sudo vs su
- root vs non-root users
- /etc/passwd overview
- Permission errors and fixes
- WSL-specific behavior

---

## Key Lessons Learned
- Only root can manage users
- sudo depends on group membership
- whoami is more reliable than the shell prompt
- Working as non-root is best practice
- Linux security prevents dangerous mistakes

---

## Sample Commands
``bash
whoami
groups
sudo -l
cat /etc/passwd
sudo deluser ayomide


## Screenshots

## Example output
![Command Output](screenshots/screenshot.png)
