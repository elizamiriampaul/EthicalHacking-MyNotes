# Day 01
Objective of the Class:
Understand the role of GitHub in cyber security and development.
Learn basic GitHub functionalities.
Explore repositories and understand their structure and purpose.

-> Relevance of GitHub in Cyber Security
Used by developers and cyber security professionals for:
Managing code securely.
Collaborating on open-source tools.
Auditing changes in security tools.

| Term             | Definition                                                                        |
| ---------------- | --------------------------------------------------------------------------------- |
| **Repository**   | A container for a project. It contains folders, files, code, and version history. |
| **Commit**       | A snapshot of changes made to the code.                                           |
| **Branch**       | A parallel version of a repository to work on features independently.             |
| **Clone**        | A local copy of a repository.                                                     |
| **Fork**         | Your own copy of someone else’s repo to make changes freely.                      |
| **Pull Request** | A way to propose changes to a repository.                                         |


# Day 02
Objective of the Class:
Understand how to set up a virtual environment for cybersecurity testing.
Learn how to install and launch Kali Linux using VirtualBox.
Use 7-Zip to extract compressed VM files.
Successfully log in to Kali Linux.

 Tools Used in This Lecture:
 | Tool           | Purpose                                                                           |
| -------------- | --------------------------------------------------------------------------------- |
| **VirtualBox** | Free virtualization software to run virtual machines (VMs).                       |
| **Kali Linux** | A Linux-based OS for ethical hacking, penetration testing, and digital forensics. |
| **7-Zip**      | File archiver to extract `.7z` or `.zip` VM files.                                |

Steps Followed in Class:
1. Downloaded Required Software
VirtualBox:
Downloaded from https://www.virtualbox.org/

Kali Linux VM (VirtualBox Version):
Downloaded from https://www.kali.org/get-kali/#kali-virtual-machines

7-Zip (Windows):
Downloaded from https://www.7-zip.org/

2. Extracted Kali Linux File
The Kali VM file was compressed in .7z format.

Used 7-Zip to extract it.

Right-click the file → 7-Zip → Extract Here.

3. Installed and Launched VirtualBox
Installed VirtualBox and launched it.

Went to File → Import Appliance.

Selected the .ova file from the extracted Kali Linux VM folder.

Clicked Next → Import to load the Kali VM.

4. Started Kali Linux VM
After importing, selected the Kali VM and clicked Start.
Waited for Kali Linux to boot up (first time may take longer).

5. Logged into Kali Linux
Used default credentials:
Username: kali
Password: kali
Once logged in, Kali’s desktop environment was visible.



# Day 03
 Lecture Objective:
Understand the purpose and usage of essential tools in Kali Linux.
Learn about EXE files and their relevance in cybersecurity.

Tools Explored in Kali Linux
Below are the tools discussed and briefly used during the session:
| Tool                | Description                                                                |
| ------------------- | -------------------------------------------------------------------------- |
| **Nmap**            | Network scanner used to discover hosts and services on a computer network. |
| **Wireshark**       | Packet analyzer for monitoring network traffic in real time.               |
| **Metasploit**      | A powerful framework used for developing and executing exploit code.       |
| **Burp Suite**      | Web vulnerability scanner for testing web application security.            |
| **John the Ripper** | Password cracking tool that helps detect weak passwords.                   |

 1. Nmap – Network Mapper
Command-line tool for scanning IP addresses, ports, and services.
Common usage:
Helps identify open ports, OS details, and running services – vital for reconnaissance.

 2. Wireshark – Network Packet Analyzer
Captures and analyzes real-time network traffic.
Helps detect:
Unencrypted data transmission
Suspicious packets
Malware communication

3. Metasploit Framework
A penetration testing platform to find, exploit, and validate vulnerabilities.
Components:
Exploit modules
Payloads
Listeners
Can be used to test how vulnerable a system is to known exploits.

4. Burp Suite – Web Security Testing
GUI tool used for:
Intercepting HTTP requests/responses
Scanning for XSS, SQLi, and other vulnerabilities
Testing login forms, cookies, sessions

Key components:
Proxy
Repeater
Scanner (in Pro version)
Intruder

5. John the Ripper – Password Cracker
Tool for cracking password hashes using dictionary or brute-force attacks.

static analysis
dynamic analysis




# Day 04
