# LAB-001 — Linux Permissions and Ownership

## Objective

Practice Linux file ownership and permission management and understand
how permission-related failures can be diagnosed.

## Environment

- Linux / RHEL-compatible system
- Bash
- Command-line tools

## Topics

- file ownership
- user and group permissions
- `chmod`
- `chown`
- `chgrp`
- symbolic and numeric permissions
- permission troubleshooting

## Lab

### 1. Create a test directory

```bash
mkdir -p ~/permission-lab
cd ~/permission-lab