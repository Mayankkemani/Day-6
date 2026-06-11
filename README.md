# Day 06 - Linux Users & Groups + Python While Loop & Functions 🚀

## Overview

Today I learned Linux User & Group Management and Python While Loops and Functions. These concepts are important for Linux Administration, DevOps, and Automation.

---

# 🐧 Linux Learning

## Topics Covered

### Check Current User

```bash
whoami
```

### User Information

```bash
cat /etc/passwd
```

### Group Information

```bash
cat /etc/group
```

---

## User Management

### Create User

```bash
sudo useradd rahul
```

### Set Password

```bash
sudo passwd rahul
```

---

## Group Management

### Create Group

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

## Practice Example

```bash
sudo groupadd developers

sudo useradd rahul
sudo useradd amit
sudo useradd rohit

sudo passwd rahul
sudo passwd amit
sudo passwd rohit

sudo usermod -aG developers rahul
sudo usermod -aG developers amit
sudo usermod -aG developers rohit

sudo usermod -aG sudo rahul
```

---

# 🐍 Python Learning

## While Loop

### Basic Example

```python
i = 1

while i <= 5:
    print(i)
    i = i + 1
```

Output:

```text
1
2
3
4
5
```

---

### Even Numbers

```python
i = 2

while i <= 10:
    print(i)
    i = i + 2
```

Output:

```text
2
4
6
8
10
```

---

### Reverse Counting

```python
i = 5

while i >= 1:
    print(i)
    i = i - 1
```

Output:

```text
5
4
3
2
1
```

---

## Functions

### Basic Function

```python
def greet():
    print("Hello")
    
greet()
```

Output:

```text
Hello
```

---

### Function with Parameter

```python
def greet(name):
    print("Hello", name)

greet("Mayank")
```

Output:

```text
Hello Mayank
```

---

### Function with Return

```python
def add():
    return 10

x = add()

print(x)
```

Output:

```text
10
```

---

## Print vs Return

```text
print()  → Display output on screen

return   → Send value back to caller
```

---

# Key Learning

## Linux

- whoami
- useradd
- passwd
- groupadd
- usermod -aG
- groups
- sudo access
- /etc/passwd
- /etc/group

## Python

- while loop
- increment and decrement
- even and odd numbers
- reverse counting
- functions
- parameters
- arguments
- return
- print vs return

---

# Learning Summary

Today I learned how Linux manages users and groups, how to provide sudo access, and how to use Python while loops and functions to create reusable code.

---

