# Linux-DevOps

**LINUX**
- LINUX - Lovable Intellect Not Using XP
**Linux** is an open-source Unix-like operating system kernel initially developed by Linus Torvalds in 1991. It serves as the foundation for various operating systems, known as Linux distributions.
- Kernel: The Linux kernel is the core of the operating system
- Distributions: Ubuntu, Fedora, Debian, CentOS, and Arch Linux.
- Terminal and Shell: Linux is known for its command-line interface (CLI)
- Root: [/] It was a root directory
  
**Kernel**: [CORE]
- The kernel is a core component of an operating system and serves as the main interface between the computer's physical hardware and the processes running on it. 
 - ![image](https://github.com/SalmanrasheedMohammed/Linux-DevOps/assets/101308889/006d20cf-9e86-4c46-b458-41283f8a4acf)

**CLI**: Command Line Interface (BASH)
- CLI is a text-based user interface that allows users to interact with a computer. CLIs are also known as console user interfaces, command-line user interfaces, and character user interfaces. 
- EX: ls -l

**SHELL** (BASH Script)
- Writing a series of commands in a file (shell script) to be executed by the shell. This is often used for automation or repetitive tasks.
- EX: echo "Hello, World!"

**SSH** (Secure Shell)
- It is a cryptographic network protocol used for secure communication over an unsecured network. It's commonly used for remote login to servers or systems over a network.

**LINUX ARCHITECTURE**
- ![image](https://github.com/SalmanrasheedMohammed/Linux-DevOps/assets/101308889/ff0cb09f-4286-4b32-a937-a114eada54cc)
- The Linux architecture is highly modular and configurable, offering a high degree of customization and flexibility to users and developers.

**- NOTE:**
  - Windows: It consists of C/D/E drives
  - Linux: It consists of (/) slash
  - Bash: Bourne again shell
  - GNU: GNU’s not Unix

**Linux Distributions**
- Ubuntu
- CentOS
- Debian
- Linux Mint
- Red Hat

**NETWORK SECURITY DEVOPS**
- A Computer network is a system that connects two or more computing devices to share information. These devices can be connected using physical wires or wirelessly.
Network DevOps is the application of DevOps principles and culture to network engineering and operations.
- Network Automation: API
- Continuous Development: Integration & Deployment
-  ![image](https://github.com/SalmanrasheedMohammed/Linux-DevOps/assets/101308889/233571b1-c4aa-4777-ba8e-970a169dc443)


**FIREWALL**
A firewall is a security device that protects a network from outside cyber attackers. It can be hardware or software. Firewalls work by monitoring attempts to access a computer's operating system and blocking unwanted incoming traffic. 
- TYPES:
  - Packet-filtering
  - Stateful inspection
  - proxy
  -
  -  ![image](https://github.com/SalmanrasheedMohammed/Linux-DevOps/assets/101308889/04de1c28-ac31-4665-b277-49288f5ed5bb) 

**PROTOCOLS**
-	Protocol refers to a set of guidelines or rules that are followed in a particular situation.
-	communication between devices or systems

**TCP MODEL**: TRANSMISSION CONTROL PROTOCOL
**IP MODEL**: INTERNET PROTOCOL
- ![image](https://github.com/SalmanrasheedMohammed/Linux-DevOps/assets/101308889/61e265ec-2b96-43d9-84b8-f216a573cfc7)

**OSI MODEL**: OPEN SYSTEM INTERCONNECTION 
•	OSI is a framework with 7 layers that computer systems use to communicate over a network.
•	TCP/IP is a set of standardized rules that allow computers to communicate on a network such as the Internet.

- ![image](https://github.com/SalmanrasheedMohammed/Linux-DevOps/assets/101308889/94f607a4-64d2-4ff1-8f7e-2024318c8db4)

**OSI Vs TCP**
- TCP/IP is a practical model that addresses specific communication challenges and relies on standardized protocols.
- OSI serves as a protocol-independent framework designed to encompass various network communication methods.
- ![image](https://github.com/SalmanrasheedMohammed/Linux-DevOps/assets/101308889/149885b7-c436-4c30-840a-42679d361601)

**Basic Commands LINUX**

**1. Navigation and File Management:**
  - pwd - Print the current working directory.
  - ls - List files and directories in the current directory.
    - **Options**:
    - ls -l (long format),
    - ls -a (show hidden files),
    - ls -h (human-readable file sizes).
  - cd - Change the current directory.
    - Examples:
    - cd /path/to/directory
    - cd .. (move to the parent directory)
    - cd ~ or cd (move to the home directory)
  - mkdir - Create a new directory.
    - Example:
    - mkdir new_directory
  - cp - Copy files or directories.
    - Example:
    - cp file.txt /path/to/destination
  - mv - Move or rename files or directories.
    - Examples:
    - mv file.txt /path/to/destination
    - mv old_name.txt new_name.txt
  - rm - Remove files or directories.
    - Examples: rm file.txt
    - rm -r directory (remove directory and its contents)
  - touch - Create an empty file.
    - Example:touch new_file.txt
  - nano or vim - Open a text editor to create or edit a file.
    - Example: nano filename.txt or vim filename.txt

**2. File Viewing:**
  - cat - Display the contents of a file.
    - Example: cat file.txt
  - more or less - Display contents of a file one screen at a time.
    - Example: less file.txt

**3. File Permissions:**
  - chmod - Change file permissions.
    - Example: chmod +x script.sh (add execute permission)
  - chown - Change file owner or group.
    - Example: chown user:group file.txt
      
**4. System Information:**
  -	uname - Display system information.
    - Example: uname -a (all information)
  - df - Display disk space usage.
    - Example: df -h (human-readable sizes)
  - du - Display file and directory space usage.
    - Example: du -h (human-readable sizes)

**5. Process Management:**
  -	ps - Display information about running processes.
    - Example: ps aux
  -	kill - Terminate a process.
    - Example: kill PID (replace PID with the actual process ID)

**6. Miscellaneous:**
  - echo - Display a message on the screen.
    - Example: echo "Hello, Linux!"
  -	man - Display the manual for a command.
    - Example: man ls
  - history - Display command history.
    - Example: history
  -	watch - Execute a program periodically, showing output fullscreen.
    - Example: watch -n 1 command
  - lsof - List open files and processes.
    - Example: lsof /path/to/file

**6. Searching and Finding:**
  - find - Search for files and directories.
    - Example: find /path/to/search -name filename.txt
  - grep - Search for a specific pattern in files.
    - Example: grep "pattern" file.txt

**7. Text Processing:**
  -	head - Display the first few lines of a file.
    - Example: head file.txt
  - tail - Display the last few lines of a file.
    - Example: tail file.txt
  - sort - Sort lines of text files.
    - Example: sort file.txt
  - cut - Remove sections from each line of a file.
    - Example: cut -d',' -f1 file.csv

**8. Networking:**
  - ping - Check the network connection to a remote host.
    - Example: ping google.com
  - ifconfig - Display network interface information.
    - Example: ifconfig
  - netstat - Display network statistics and connections.
    - Example: netstat -an
  - wget - Download files from the internet.
    - Example: wget https://example.com/file.zip
  - curl - Transfer data to or from a server.
    - Example: curl -o https://example.com/file.zip

**9. Compression and Archiving:**
  -	tar - Create or extract tar archives.
    - Example:
    - tar -cvf archive.tar.gz /path/to/directory
    - tar -xvf archive.tar.gz/path/to/directory
    - tar -tvf backup.tar.gz /path/to/data
  -	gzip and gunzip - Compress or decompress files.
    - Example: gzip file.txt

**10. User and Group Management:**
  - who - Display information about logged-in users.
    - Example: who
  -	groups - Display the groups a user belongs to.
    - Example: groups username
  -	useradd - Create a new user.
    - Example: useradd newuser

**11. System Control:**
  -	shutdown - Shutdown or restart the system.
    - Example: shutdown -h now (halt immediately)
  -	reboot - Restart the system.
    - Example: reboot
  -	date - Display or set the system date and time.
    - Example: date

**12. File Transfer:**
  -	scp - Securely copy files between hosts.
    - Example: scp file.txt user@remote:/path/to/destination
  -	rsync - Synchronize files and directories between systems.
    - Example: rsync -av source/ destination/

**13. Package Management:**
  - apt (Debian/Ubuntu) or yum (Red Hat/CentOS)
  - Package management commands for installing, updating, and removing software packages.
  - Example: sudo apt-get update or sudo yum install package_name

**14. Users and Groups:**
  - passwd - Change a user's password.
    - Example: passwd username
  - Usermod - Modify user account properties.
    - Example: sudo usermod -aG groupname username

**15. File Permissions:**
  - sudo - Execute a command with superuser privileges.
    - Example: sudo command

**16. Systemd Services:**
  - systemctl - Control the systemd system and service manager.
    - Example: systemctl status service_name

**sudo**
- **sudo** (Superuser Do) is a command-line utility that allows permitted users to execute a command as the superuser or another user, as specified by the security policy.
- In Ubuntu (sudo apt)
- In Amazon Linux (sudo yum)
- Update Package Lists: sudo apt-get update 
- Install a Package: sudo apt-get install package_name 
- Remove a Package: sudo apt-get remove package_name 
- Update System Packages: sudo apt-get upgrade
- Full System Upgrade: sudo apt-get dist-upgrade 
- Install a Package on Red Hat/CentOS: sudo yum install package_name 
- Remove a Package on Red Hat/CentOS: sudo yum remove package_name 
- Update System on Red Hat/CentOS: sudo yum update 
- Install Snap Package: sudo snap install package_name 
- Edit a System Configuration File: sudo nano /etc/example.conf 
- Restart the System: sudo reboot 
- Shut Down the System: sudo shutdown -h now 
- View Log Files: sudo cat /var/log/syslog 
- Change File Ownership: sudo chown user:group filename 
- Change File Permissions: sudo chmod 644 filename 
- Start/Stop/Restart System Services:
  - sudo systemctl start service_name
  - sudo systemctl stop service_name
  - sudo systemctl restart service_name 
- Add a User to the sudo Group: sudo usermod -aG sudo username 
- Run a Command as Another User: sudo -u username command

**sudo systemctl**
- systemctl is a command-line utility in Linux systems used to manage systemd services
* COMMANDS
  - systemctl enable <service_name>
  - systemctl disable <service_name>
  - systemctl restart <service_name>
  - systemctl status <service_name>
  - systemctl start <service_name>
  - systemctl stop <service_name>
  - systemctl reload <service_name>

**sudo ss -ntpl**
- The command sudo ss -ntpl is used to list listening TCP sockets along with the process information in a Linux system.
* When you run sudo ss -ntpl,
  - (n) port/local address
  - (t) TCP sockets
  - (p) PID name of the process associated with each socket
  - (l) list of sockets

**DocumentRoot**
- /var/www/html
- To host a custom site you can update the site to DocumentRoot

linux operations 