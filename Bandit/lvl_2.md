# Bandit Level 1 → Level 2

## Challenge Overview
In this level, the password for the next level is stored in a file named `-` located in the home directory.  
Since `-` is a special character in Linux (often used to represent standard input/output), it cannot be accessed using a normal command.

---

## Level Goal
Find the password stored inside the file named `-` and use it to log in to **bandit2**.

---

## Login Details
Host: bandit.labs.overthewire.org  
Port: 2220  
Username: bandit1  
Password: (Password obtained from previous level)

---

## Steps to Solve

### Step 1: Connect to the Bandit Server
```bash
ssh -p 2220 bandit1@bandit.labs.overthewire.org
