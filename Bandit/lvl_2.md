# Bandit Level 1 → Level 2

## Challenge Overview
Bandit is a beginner-friendly wargame from OverTheWire that teaches Linux and cybersecurity fundamentals.  
In this level, the goal is to retrieve the password for **Level 2**, which is stored in a file with a special name.

---

## Level Goal
- Find the password stored in a file named `-`
- Use that password to log in to `bandit2`

---

## Given Information
- Host: `bandit.labs.overthewire.org`
- Port: `2220`
- Username: `bandit1`
- Password: *(password obtained from previous level)*
- Password file name: `-`
- File location: Home directory

<img width="1617" height="565" alt="lvl2_1" src="https://github.com/user-attachments/assets/18a0912f-ec0d-4c4b-9559-25b5c2d9c6e5" />

---

## Steps to Solve

### Step 1: Log in to Bandit Level 1
Use SSH to connect to the Bandit server with the credentials obtained from the previous level.
![alt text]("C:\Users\sanja\OneDrive\Pictures\Screenshots 1\Bandit\lvl2\Screenshot 2026-02-10 183342.png")
### Step 2: List Files in the Directory
Run the `ls` command to check available files in the home directory.

### Step 3: Identify the Special File
You will notice a file named `-`.  
Since `-` is treated as a special character in Linux commands, it must be accessed carefully.

### Step 4: Read the File
Use the following command to read the contents of the file:

This command treats `-` as a file in the current directory instead of an option.

### Step 5: Log in to Bandit Level 2
Use the retrieved password to log in to the next level.
![Alt text]("C:\Users\sanja\OneDrive\Pictures\Screenshots 1\Bandit\lvl2\Screenshot 2026-02-10 190701.png")

---

## Result
- Successfully retrieved the password from the file named `-`
- Logged into the Bandit Level 2 environment
- Completed the **Level 1 → Level 2** challenge

---

## Key Learnings
- Handling files with special characters in Linux
- Using relative paths like `./` to access files
- Understanding how Linux treats `-` as a command option
- Continuing level progression using retrieved credentials
