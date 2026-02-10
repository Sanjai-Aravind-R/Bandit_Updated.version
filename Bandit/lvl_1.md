# Bandit Level 0 → Level 1

## Challenge Overview
Bandit is a beginner-friendly wargame by OverTheWire that helps build Linux and security fundamentals.  
In this challenge, the goal is to find the password for **Level 1**, which is stored in a file inside the home directory.

---

## Level Goal
- Locate the password for the next level
- Use that password to log in as `bandit1` via SSH

---

## Given Information
- Host: `bandit.labs.overthewire.org`
- Port: `2220`
- Username: `bandit0`
- Password: `bandit0`
- Password file name: `readme`
- File location: Home directory
- <img width="1617" height="565" alt="lvl1_1" src="https://github.com/user-attachments/assets/18a0912f-ec0d-4c4b-9559-25b5c2d9c6e5" />

---

## Steps to Solve

### Step 1: Log in to Bandit Level 0
Connect to the server using SSH with the provided credentials.

### Step 2: List Files in Home Directory
Check the contents of the home directory to identify available files.

### Step 3: Read the Password File
Open the `readme` file to reveal the password for the next level.
-<img width="951" height="333" alt="lvl1_2" src="https://github.com/user-attachments/assets/30855c99-bd14-4059-a1f7-41a1df7d4c9e" />


### Step 4: Log in to Bandit Level 1
Use the extracted password to log in as `bandit1` on the same host and port.
<img width="905" height="888" alt="lvl1_3" src="https://github.com/user-attachments/assets/b8fa0812-4cdb-4865-8357-50db9452354d" />
---


## Result
- Successfully retrieved the password for Level 1
- Logged into the Bandit Level 1 environment
- Completed the Level 0 → Level 1 transition

---

## Key Learnings
- Using SSH with a non-default port
- Navigating directories using basic Linux commands
- Reading files from the terminal
- Understanding how credentials are passed between levels
