# Step-1
---
_Bandit is an introductory wargame by OverTheWire that focuses on building a strong foundation in Linux and security concepts. Level 0 is designed for absolute beginners and introduces the most important skill required for the entire game: logging into a remote system using SSH.

The Bandit Level 0 page clearly outlines the goal of the challenge. The task is not to exploit anything, but simply to establish a secure connection to the Bandit server. All required credentials are openly provided, making this level a guided learning step rather than a test of problem-solving.

The challenge page specifies the remote host, a non-default SSH port, and login credentials. This teaches an important lesson early on: real-world systems may not always use default configurations, and paying attention to connection details is crucial.

Before diving into advanced topics like privilege escalation or file manipulation, it is essential to understand how to access a system properly. Level 0 ensures that the player is comfortable with reading instructions and recognizing essential connection parameters._
<img width="1875" height="599" alt="lvl0_1" src="https://github.com/user-attachments/assets/b78b2dc6-8983-48f8-a7a5-59608d54a1a1" />
# Step-2
---
_Once the connection details are understood, the next step is to access the Bandit server from a local machine. In this case, Windows PowerShell is used as the terminal environment.

Using PowerShell for SSH:
Modern versions of Windows come with SSH pre-installed, making it possible to connect to remote Linux servers directly from PowerShell. This eliminates the need for third-party tools and encourages familiarity with command-line interfaces.

Connecting to the Server:
By specifying the username, host address, and the custom port, an SSH request is sent to the Bandit server. This step demonstrates how command-line tools interact with remote machines and how authentication requests are initiated.

This stage reinforces the idea that security tools are not always graphical. Many real-world environments rely heavily on terminals, and understanding how to navigate them is a key skill in cybersecurity and system administration._
<img width="936" height="231" alt="lvl0_2" src="https://github.com/user-attachments/assets/a83e096e-f554-4994-bb99-0a2b420bef64" />
# Step-3
_After issuing the SSH command, the server responds with authentication prompts and a welcome banner. This confirms that the connection attempt was successful.

Authentication Process:
The server requests the password associated with the Bandit Level 0 account. Entering the correct password grants access to the remote system. This mirrors real-world authentication mechanisms used across servers globally.

Server Response:
Once logged in, the user is greeted with the OverTheWire banner and confirmation messages. These indicate that the user is now inside the Bandit game environment and ready to proceed.

Successfully logging in marks the completion of Bandit Level 0. More importantly, it validates the user’s ability to access a remote Linux system securely—an essential skill that will be repeatedly used in higher levels.

With access established, the next challenges will introduce file discovery, permissions, and command-line problem-solving. Level 0 acts as the gateway to the entire Bandit learning journey._
<img width="1076" height="818" alt="lvl0_3" src="https://github.com/user-attachments/assets/5828754d-6887-4585-a714-1ee25fa30f64" />
