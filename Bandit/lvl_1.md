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

---

## Steps to Solve

### Step 1: Log in to Bandit Level 0
Connect to the server using SSH with the provided credentials.

### Step 2: List Files in Home Directory
Check the contents of the home directory to identify available files.

### Step 3: Read the Password File
Open the `readme` file to reveal the password for the next level.

### Step 4: Log in to Bandit Level 1
Use the extracted password to log in as `bandit1` on the same host and port.

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

---

## Notes
- Always save passwords locally
- Bandit levels do not store progress automatically
- These basic skills are used repeatedly in higher levels

---

## Status
✅ Level 0 → Level 1 completed
