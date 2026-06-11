# Day 06 - Linux Users & Groups Management 🚀

## Overview

Today I learned how Linux manages users, groups, and administrative access. Users and groups are essential for system security and access control.

---

## Topics Covered

### Check Current User

```bash
whoami
```

### User Information File

```bash
cat /etc/passwd
```

### Group Information File

```bash
cat /etc/group
```

---

## User Management

### Create a User

```bash
sudo useradd rahul
```

### Set Password

```bash
sudo passwd rahul
```

---

## Group Management

### Create a Group

```bash
sudo groupadd developers
```

### Add User to Group

```bash
sudo usermod -aG developers rahul
```

### Check User Groups

```bash
groups rahul
```

---

## Grant Sudo Access

```bash
sudo usermod -aG sudo rahul
```

---

## Practice Commands

### Create User and Group

```bash
sudo useradd ansible
sudo passwd ansible

sudo groupadd automation

sudo usermod -aG automation ansible
```

### Jenkins Example

```bash
sudo useradd jenkins
sudo passwd jenkins

sudo groupadd cicd

sudo usermod -aG cicd jenkins
sudo usermod -aG sudo jenkins
```

---

## Key Learning

- whoami → Check current user
- useradd → Create user
- passwd → Set password
- groupadd → Create group
- usermod -aG → Add user to group
- groups → Check user groups
- usermod -aG sudo → Grant admin access

---

## Real DevOps Use Cases

- Managing Jenkins users
- Creating CI/CD accounts
- Managing team access
- Granting sudo privileges
- Linux server administration

---

## Learning Summary

Today I learned:

✅ User Management

✅ Group Management

✅ Password Management

✅ Sudo Access

✅ /etc/passwd

✅ /etc/group

✅ useradd

✅ passwd

✅ groupadd

✅ usermod

---
