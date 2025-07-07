CSE_Training_2025

# Day 1 of Training

*Orientation Program*

- Firstly we attended orientation program organised by the faculty of CSE department in the auditorium
- There we learnt about our department, modules and faculty etc.

- **Topics Covered:**

**•Difference between Linux and Windows OS**
# Linux vs Windows - Basic Differences

| Feature              | Linux                                    | Windows                                 |
|----------------------|-------------------------------------------|------------------------------------------|
| Source Code          | Open Source                               | Closed Source                             |
| Cost                 | Free (mostly)                             | Paid License (some versions free)         |
| Customization        | Highly customizable                       | Limited customization                     |
| Security             | More secure (due to permissions & open code) | More targeted by viruses                 |
| Command Line         | Powerful and widely used                  | Optional, mainly GUI based                |
| Use in Servers       | Widely used (e.g., Ubuntu Server, CentOS) | Less common                              |
| Updates              | User-controlled, frequent small updates   | Automatic, sometimes forced              |
| Gaming               | Fewer native games, improving via Steam   | Most games supported                      |


**•Advantages of Linux over Windows:**
 -Free open source
 
 -More secure

 -Large and active community

**•Linux is used widely by most of the product and service based companies**

**•Learned about product based and service based companies**

**•Learned and explored about various carrier options under CSE**

**•Downloading process for linux:**
 •Dowloaded 3 softwares:
  
  -Oracle Virtualbox
 
  -Microsoft Visual C++
 
  -Ubuntu 24.04.02

  **•Booting and its types**
  - Booting is referred to as waking up the computer
  - # Cold Boot vs Warm Boot

| Boot Type  | Description                                                                 |
|------------|-----------------------------------------------------------------------------|
| Cold Boot  | When the computer is started from a completely powered-off state (eg, macOS). |          |
| Warm Boot  | When the computer is restarted without turning off the power (e.g.,windows).|



# Day 2 of Training
# Kernal
- It is a computer program that is a core of computer's Operating System

# Shell
- It is a computer program that acts as interface between user and OS.
- It basically acts as a translator

**Types**
 
| Shell Type |
|------------|
| sh         |
| bash       |
| zsh        |
| fish       |

**Categories**
- Command line shell
- Graphic shell

# Linux File System Structure

![Linux File System Structure](linux-filesystem.png)

# Commands
- We learned and emplemented various commands in linux.
- Below are the commands we learnt today

| Command   | Description                            |
|-----------|----------------------------------------|
| `ls`      | Lists files and directories             |
| `whoami`  | Shows current logged-in user            |
| `date`    | Displays current date and time          |
| `cd`      | Changes the directory                   |
| `mkdir`   | Creates a new directory                 |
| `cat`     | Displays content of a file              |
| `touch`   | Creates an empty file                   |
| `cp`      | Copies files or directories             |
| `pwd`     | Prints current working directory        |
| `whereis` | Finds location of a command             |
| `whatis`  | Shows a brief description of a command  |
| `mv`      | Moves or renames files and directories  |

- After learning, we practiced these commands on an online terminal


**ls**

- It lists all the directories and files

![Image Description](ls.png)

**mkdir**
   - It makes a new directory by using 'mkdir filename'
   - Here we made a new directory names newdirectory

**cd**
  - It changes the directory you are working on
  - Here we changed the directory to newdirectory

  ![mkdir and cd command output](mkdirandcd.png)

**cat**
 - It is used to create a file with content by using '>' operator
 - It is also used to display a file
 - Here we created a file named file1 and typed our content and then displayed file1 with cat.

![cat command output](cat.png)

**touch**
 - It is used to create a file without content
 - Here we created a file named file2 without any content in it.

![touch command output](touch.png)

**cp**
 - It is used to copy one file to another by using 'cp source_file destination_file'.
 - Here we copied the content of file1 to file2.

![cp command output](cp.png)

**whereis,** **whatis,** **whoami,** **pwd**

![ command output](whereis.png)

**mv**
 - It is used to rename a file
 - It is also used to move a file to a new directory
 - Here we renamed the file file2 to newfile

![mv command output](mv.png)



# DAY 3 of Training

# Dual Boot:
- Dual booting allows a computer to run two different operating systems, enabling users to choose which one to boot into upon startup.

# ISO file:
- In Linux, an ISO file is a single file containing a complete copy of the data from a CD, DVD, or other optical media, formatted as an ISO 9660 file system.

# Bare metal installation:
- It refers to setting up an operating system directly on a physical server's hardware, without any intervening virtualization layer like a hypervisor.

# VMware:
- VMware is a commercial product known for its enterprise-grade features, performance, and comprehensive support.

#  Virtual box:
-  VirtualBox is an open-source, free alternative, generally favored for personal use, testing, and development.
# Partitioning schemes:

- Dividing a hard disk into separate sections.

##  Difference Between MBR and GPT

| Feature                    | MBR (Master Boot Record)        | GPT (GUID Partition Table)              |
|----------------------------|----------------------------------|------------------------------------------|
| Maximum Partitions         | Up to 4 primary partitions       | Supports up to 128 partitions (by default) |
| Disk Size Support          | Up to 2 TB                       | Supports disks larger than 2 TB           |
| Partitioning Method        | Stores partition info in one place | Stores multiple copies for recovery     |
| Compatibility              | Older systems (BIOS)             | Modern systems (UEFI)                    |
| Security                   | No CRC protection                | Uses CRC for error checking              |
| Boot Mode                  | BIOS-based booting               | UEFI-based booting                       |
| Data Recovery              | Difficult                        | Easier (multiple headers)                |

# File and Directory permossions
-In Linux (like Ubuntu), permissions decide who can do what with a file or folder.

**chmod**
- chmod stands for change mode. It is used to change the permissions of files or directories in Linux.

**syntax**
-chmod [permission] [file]  
*for permission*
  - ./filename.sh 
*for displaying*

**chmod +x filename.sh**
- +x enables executable file

**chmod 444 filename.sh**
- 444 enables a read only file

**chmod 644 filename.sh**
- it enables permissions only to owner2.

# Redirection
- Redirection in Linux means sending the output or input of a command to somewhere else, like a file.
- Example: echo "Hello" > file.txt

## Redirection Operators in Linux

| Type         | Symbol | Example Command                  | Description                             |
|--------------|--------|----------------------------------|-----------------------------------------|
| Output       | `>`    | `echo "Hello" > file.txt`        | Writes "Hello" to `file.txt` (overwrites) |
| Append       | `>>`   | `echo "World" >> file.txt`       | Adds "World" to end of `file.txt`        |
| Input        | `<`    | `wc -l < file.txt`               | Reads `file.txt` as input to `wc -l`     |


# Pipe '|'
- In Linux, a pipe (|) is used to connect two commands — it takes the output of one command and passes it as input to another.

  **syntax**
  - command1 | command2
  - command1 → generates output
  - command2 → takes that output as input

  Example:

ls | sort

📄 This lists all files (ls) and sorts them (sort).

# Practice Programs
# Program 1

**To display various variables**

![program1](program1.1.png)

![program1](program1.2.png)


*Output*

![program1](program1.3.png)

# Program2

**To find the greater between two numbers**

![program2](program2.1.png)

![program2](program2.2.png)

*Output*

![program2](program2.3.png)

# Program3

**To print a multiplication table of a number**

![program3](program3.1.png)

![program3](program3.2.png)

*Output*

![program3](program3.3.png)


# Day4 of training 

# File Compression 
- File compression in Linux is the process of reducing the size of files or folders to save disk space or make them easier to transfer.

**syntax**
- gzip file.txt 

(creates file.txt.gz and deletes file.txt)

- gunzip file.txt.gz

(unzips the file file.txt.gz)

**If we want to keep both the zipped and unzipped files, then we use -k**

**syntax**
- gzip -k file.txt

![gzip](https://github.com/user-attachments/assets/fd0c6149-0459-4bea-8aec-55d304cd05ee)

# Wildcards
- Maches files without typing full names

| Wildcard | Description                                      | Example         | Matches                          |
|----------|--------------------------------------------------|-----------------|----------------------------------|
| `*`      | Matches zero or more characters                  | `ls *.txt`      | All `.txt` files                 |
| `?`      | Matches exactly one character                    | `ls file?.txt`  | `file1.txt`, `fileA.txt`, etc.  |
| `[...]`  | Matches any one character in the brackets        | `ls file[1-3].txt` | `file1.txt`, `file2.txt`, `file3.txt` |
| `[^...]` | Matches any one character **not** in the brackets| `ls file[^1].txt` | All files except `file1.txt`     |
| `{a,b}`  | Matches either `a` or `b` (brace expansion)      | `echo {Jan,Feb}` | `Jan` `Feb`                      |
| `\`      | Escapes a wildcard character                     | `ls \*.txt`     | Matches a file literally named `*.txt` |

![wildcards](https://github.com/user-attachments/assets/ac70c81d-1f0e-4795-97c6-d31669e5bc99)


# Assignment - Escaping Characters
- Escaping characters are used in the Linux command line (like Bash) to prevent special characters from being interpreted by the shell.
- Escaping characters = Telling the shell:

"Treat this symbol as a normal character, not something special."

| Character | Purpose                                           | Example            | Result                                                   |
|-----------|---------------------------------------------------|--------------------|----------------------------------------------------------|
| `\`       | Escape special characters (like `*`, `?`, `|`)    | `echo \*`          | Prints `*` instead of using it as a wildcard             |
| `\"`      | Escape double quote inside double-quoted strings  | `echo "She said \"Hi\""` | Prints `She said "Hi"`                          |
| `\'`      | Escape single quote inside single-quoted strings (rare; use other quoting) | `echo 'It\'s OK'` | May not work; better to use double quotes               |
| `\\`      | Escape backslash itself                           | `echo \\`          | Prints `\`                                                |
| ``\` ``   | Escape backtick or use it in command substitution | \`echo hello\`     | Runs command and replaces it with output                |
| `\$`      | Escape dollar sign to prevent variable expansion  | `echo \$HOME`      | Prints `$HOME` instead of expanding it                  |
| `\` inside `''` | No effect; backslashes are literal          | `echo '\$HOME'`    | Prints `\$HOME`                                          |


# Hardware
- Hardware refers to the physical parts of any computer system — the components you can see and touch.

| Category            | Examples                                           | Purpose                                      |
|---------------------|----------------------------------------------------|----------------------------------------------|
| **Input Devices**   | Keyboard, Mouse, Microphone, Scanner               | Send data *into* the computer                |
| **Output Devices**  | Monitor, Printer, Speakers                         | Show or deliver results *from* the computer  |
| **Processing Unit** | CPU (Central Processing Unit), GPU (Graphics Card) | The "brain" – processes instructions         |
| **Storage Devices** | Hard Drive (HDD), SSD, USB Drive, CD/DVD           | Store data permanently or temporarily        |
| **Memory**          | RAM (Random Access Memory), Cache                  | Holds data for fast access while working     |
| **Motherboard**     | Main circuit board                                 | Connects and allows communication between parts |
| **Power Supply**    | PSU (Power Supply Unit)                            | Converts electricity for the computer to use |
| **Cooling System**  | Fans, Heat Sinks, Liquid Cooling                   | Prevents overheating                         |
| **Ports & Expansion**| USB Ports, HDMI, Expansion Slots                  | Connect external devices or upgrade system   |

# Key components of CPU Cabinet

| Component              | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Motherboard**        | Main circuit board that connects all hardware components                   |
| **CPU (Processor)**    | Brain of the computer; performs all calculations and tasks                  |
| **RAM (Memory)**       | Temporary memory used while the computer is on                              |
| **Hard Drive / SSD**   | Storage devices for saving files and the operating system                   |
| **Power Supply (PSU)** | Converts electricity from the wall into usable power for the computer       |
| **Cooling System**     | Includes CPU fan, case fans, and sometimes liquid cooling to prevent overheating |
| **Optical Drive** *(optional)* | Reads CDs/DVDs (less common today)                               |
| **Expansion Cards**    | Graphics card (GPU), sound card, network card, etc.                         |
| **Ports and Connectors**| USB, HDMI, Ethernet, audio jacks — for connecting external devices         |
| **Cables and Wires**   | Power and data cables that connect all the parts together                   |

![image](https://github.com/user-attachments/assets/549c9ce4-27b5-4ccf-91c5-a251ebcc9c9b)

# Difference between RAM and Hard disk

| Feature              | RAM (Random Access Memory)                      | Hard Disk (HDD/SSD)                          |
|----------------------|--------------------------------------------------|----------------------------------------------|
| **Function**         | Temporary memory used while programs run         | Permanent storage for files and software     |
| **Data Storage**     | Stores data temporarily                         | Stores data permanently                      |
| **Speed**            | Very fast                                        | Slower compared to RAM                       |
| **Volatility**       | Volatile (data is lost when power is off)        | Non-volatile (data stays even when off)      |
| **Size/Capacity**    | Smaller (usually 4GB to 32GB in PCs)             | Larger (hundreds of GBs to several TBs)      |
| **Usage**            | Active processes, apps, and OS operations        | Documents, media, programs, OS installation  |
| **Upgrade Impact**   | Improves speed and multitasking                  | Increases storage space                      |

# Difference between Ram and cache memory

| Feature              | RAM (Random Access Memory)                      | Cache Memory                                 |
|----------------------|--------------------------------------------------|----------------------------------------------|
| **Function**         | Temporary memory for running programs            | Very fast memory for storing frequently used data |
| **Location**         | On the motherboard                               | Inside or very close to the CPU              |
| **Speed**            | Fast                                             | Faster than RAM                              |
| **Size/Capacity**    | Larger (4GB–32GB in most systems)                | Very small (KBs to few MBs)                  |
| **Access Time**      | Slower than cache                                | Extremely fast                               |
| **Volatility**       | Volatile (loses data when power is off)          | Volatile                                     |
| **Purpose**          | Holds programs and data being used by the system | Reduces CPU wait time by storing quick-access data |
| **Cost**             | Cheaper per GB                                   | More expensive per KB                        |

# ROM
- ROM stands for Read-Only Memory.
- It is a type of non-volatile memory, meaning it retains data even when the power is turned off.

| Feature              | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| **Full Form**        | Read-Only Memory                                                            |
| **Volatility**       | Non-volatile (data is not lost when power is off)                          |
| **Function**         | Stores permanent instructions for the computer to start (boot up)          |
| **Write Access**     | Usually written once, or rarely changed                                     |
| **Speed**            | Slower than RAM                                                             |
| **Examples**         | BIOS, Firmware, Embedded system software                                    |

# Process of booting

| Step | Hardware Component       | Description                                                                 |
|------|---------------------------|-----------------------------------------------------------------------------|
| 1    | **Power Supply (PSU)**    | Sends power to all components when the system is turned on                 |
| 2    | **Motherboard**           | Distributes power and connects CPU, RAM, and other components              |
| 3    | **CPU**                   | Starts executing instructions from ROM                                     |
| 4    | **ROM (BIOS/UEFI)**       | Runs POST (Power-On Self-Test) to check basic hardware                     |
| 5    | **RAM**                   | Is tested and then used to load the OS                                     |
| 6    | **Storage Drive (HDD/SSD)** | BIOS/UEFI finds the bootloader in the storage device                       |
| 7    | **Bootloader**            | Loads the operating system into RAM                                        |
| 8    | **Operating System**      | Starts running; shows login screen or desktop                              |


# Day5 of training 

# Computer Hardware and Troubleshooting 

# HDD
- HDD stands for Hard Disk Drive, a non-volatile storage device used to store data permanently on computers, laptops, servers, and other digital systems. It uses magnetic storage to write and retrieve digital information using one or more spinning platters and a moving read/write head.

## 🔹 Key Features of HDD

| Feature              | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| **Storage Capacity** | Typically ranges from 500 GB to several TB (terabytes).                    |
| **Speed (RPM)**      | Common speeds: 5400 RPM, 7200 RPM, 10000 RPM. Higher RPM = faster access.  |
| **Interface**        | Most commonly uses SATA (Serial ATA), older ones may use IDE or SCSI.      |
| **Durability**       | Mechanical parts make it more prone to physical damage than SSDs.           |
| **Cost**             | Cheaper per GB than SSDs.                                                  |
| **Use Cases**        | Great for large-scale storage like backups, videos, and archives.          |



## Types of HDD

1. Desktop HDD – Standard 3.5" drives used in desktop PCs.


2. Laptop HDD – Compact 2.5" drives designed for notebooks.


3. Enterprise HDD – High-performance drives for servers and data centers.


4. NAS HDD – Optimized for Network Attached Storage with 24/7 operation.


5. Surveillance HDD – Designed for continuous video recording (CCTV systems).


## If your PC is Running Slow
 
**Causes & Fixes**

| Issue                    | Explanation                                      | Fix/Solution                                                   |
|--------------------------|--------------------------------------------------|----------------------------------------------------------------|
| Too Many Startup Apps    | Slows boot time                                  | `Ctrl + Shift + Esc → Startup → Disable unnecessary apps`      |
| Low RAM                  | Can’t multitask well                             | Upgrade RAM to 8GB+                                            |
| Fragmented HDD           | File access delays (HDD only)                    | Run Disk Defragmenter                                          |
| Old/Faulty HDD           | Degrading speed                                  | Replace with SSD                                               |
| Background Processes     | Resource hogging apps                            | End unnecessary processes from Task Manager                    |
| Virus/Malware            | System lag & damage                              | Scan with antivirus                                            |
| Outdated Drivers         | Causes lag or crashes                            | Update from Device Manager or manufacturer site                |
| Overheating              | Thermal throttling slows system                  | Clean fans, apply thermal paste                                |
| Too Many Browser Tabs    | High RAM usage                                   | Close tabs, use light browsers                                 |
| Background Updates       | Slows performance                                | Let updates finish or pause                                    |
| Weak CPU                 | Can’t handle new apps                            | Upgrade processor (if possible)                                |

# Printer Issues & Solutions:

| Problem                            | Solution                                  |
| ---------------------------------- | ----------------------------------------- |
|  Paper Jam                       | Remove the stuck page carefully           |
|  Printer Out of Paper During Print Job | Use Queue.                 |
|  Faded or Poor Quality Prints   | Refill or replace ink/toner               |
|  Overlapping Lines in Print      | Possible drum issue, replace the drum |

# BSOD
- BSOD stands for Blue Screen of Death. It is a critical system error screen displayed by Microsoft Windows operating systems when the system encounters a fatal error that it cannot recover from, often requiring a restart.


# Causes of BSOD

1. Driver Issues – Outdated, corrupted, or incompatible hardware drivers.


2. Hardware Failures – Failing RAM, hard drives, overheating, etc.


3. Corrupt System Files – System files required for Windows to run may get damaged.


4. Overclocking – Increasing CPU/GPU speeds can lead to instability.


5. Malware – Malicious software can interfere with system processes.


6. Software Conflicts – Newly installed applications conflicting with existing ones.


7. Windows Updates – In rare cases, a new update can trigger instability.


# BIOS/UEFI Settings and POST Errors:

| Term                                             | Meaning                                                                                                     |
| ------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| **BIOS (Basic Input/Output System)**             | The traditional firmware that initializes hardware during boot before handing over to the OS.               |
| **UEFI (Unified Extensible Firmware Interface)** | A modern, more advanced replacement for BIOS with a graphical interface, mouse support, and faster booting. |

# What is POST (Power-On Self-Test)?

POST is a built-in diagnostic program that runs automatically when a computer is powered on. It checks if the hardware components of the system are working properly before loading the operating system (OS).

**Functions of POST:**

1. Checks the CPU


2. Tests RAM (memory)


3. Checks motherboard components


4. Tests video card (graphics)


5. Detects keyboard and mouse


6. Detects storage devices (HDD, SSD)

## POST vs BIOS vs Boot Process

| Term     | Full Form                 | Function                                                                 | When It Happens                    | Key Responsibilities                                |
|----------|---------------------------|--------------------------------------------------------------------------|------------------------------------|-----------------------------------------------------|
| POST     | Power-On Self-Test        | Checks hardware components and basic system functionality                | Immediately after system is powered on | Verifies CPU, RAM, keyboard, storage, etc.          |
| BIOS     | Basic Input/Output System | Initializes and configures hardware, provides an interface for firmware | Right after POST is complete       | Loads device settings, runs POST, and starts boot   |
| Boot     | Booting Process           | Loads the operating system into memory                                   | After BIOS hands over control      | Loads OS from storage (HDD/SSD) into RAM            |


# Day6 of training 

# Safe mode
- Safe Mode is a special way to start a computer or operating system (like Windows, macOS, or Android) that loads only the most basic and essential software and drivers.

**[F8, Shift+Restart]**

**Why it's used:**

Safe Mode helps when:

Your system is crashing or freezing.

You want to remove malware or viruses.

You need to uninstall programs or drivers that may be causing problems.

You need to fix startup issues.

# Recovery Tools 
- Recovery tools are built-in or external software utilities that help repair, restore, or recover your system when it isn’t working properly.


| **Tool Name**              | **What It Does**                                                             |
|----------------------------|------------------------------------------------------------------------------|
| System Restore             | Restores your system to a previous state using restore points                |
| Startup Repair             | Fixes issues preventing Windows from booting properly                       |
| System Image Recovery      | Restores the entire system from a system image backup                        |
| Command Prompt             | Allows advanced users to run manual repair commands (e.g., chkdsk, sfc)      |
| Reset This PC              | Reinstalls Windows with options to keep or remove your personal files        |
| Safe Mode                  | Boots the system with only basic drivers and services for troubleshooting     |
| Windows Memory Diagnostic  | Checks your system’s RAM for errors                                           |
| UEFI Firmware Settings     | Lets you change BIOS/firmware settings                                       |

# OS Repair
- OS Repair means fixing problems in the operating system (OS)—like Windows, macOS, or Linux—so that the system runs properly again. It can involve repairing corrupted files, fixing boot problems, or restoring the OS to a working state without erasing your data.

**When is OS Repair Needed?**

System won’t boot or crashes often

System files are corrupted or missing

Updates failed or caused problems

Blue Screen of Death (BSOD) errors

Windows features stop working

## Methods to Repair an OS (Windows Example)

| **Repair Method**           | **What It Does**                                            | **Command or Tool**                                      |
|----------------------------|-------------------------------------------------------------|-----------------------------------------------------------|
| Startup Repair             | Fixes boot errors and missing system files                  | Recovery > Advanced > Startup Repair                      |
| System File Checker (SFC)  | Scans and fixes corrupted system files                      | `sfc /scannow`                                            |
| DISM Tool                  | Repairs Windows image and update components                 | `DISM /Online /Cleanup-Image /RestoreHealth`              |
| System Restore             | Restores the OS to a previous good configuration            | `rstrui`                                                  |
| Reset This PC              | Reinstalls Windows (optionally keeps files)                 | Settings > Recovery > Reset                               |
| In-place Upgrade Repair    | Reinstalls Windows using a USB or ISO without deleting data | Bootable USB or run `Setup.exe` from a Windows ISO file   |
| Chkdsk (Check Disk)        | Fixes file system and hard disk issues                      | `chkdsk /f /r`                                            |

##  Common Symptoms of a Virus or Malware Infection

| **Category**         | **Symptoms**                                                                 |
|----------------------|------------------------------------------------------------------------------|
| Performance Issues   | - Slow computer<br>- Frequent crashes or freezing                            |
| Pop-ups & Ads        | - Unexpected ads and pop-ups even when browser is closed                     |
| Browser Problems     | - Homepage changed<br>- Search engine redirected<br>- Unknown toolbars        |
| Unusual Activity     | - Unknown apps or files appear<br>- High CPU usage<br>- System behaving oddly |
| Security Warnings    | - Fake antivirus alerts<br>- Access denied to folders or settings             |
| Network Issues       | - Internet disconnects<br>- Suspicious network traffic                        |
| File Issues          | - Files missing or encrypted<br>- Extensions changed (e.g., .exe → .xyz)      |

## Basic Virus & Malware Removal Steps (Windows)

| **Step**                        | **What To Do**                                                                 |
|----------------------------------|--------------------------------------------------------------------------------|
| Boot into Safe Mode             | Use minimal drivers/services to prevent malware from loading                   |
| Run Windows Security            | Go to *Settings > Privacy & Security > Windows Security > Virus & threat protection* |
| Use Malware Removal Tools       | Install & scan with tools like **Malwarebytes** or **AdwCleaner**              |
| Uninstall Suspicious Programs   | Go to *Control Panel > Programs > Uninstall a program* and remove unknown apps |
| Check Browser Extensions        | Remove unfamiliar or suspicious browser add-ons/extensions                     |
| Run Disk Cleanup                | Run `cleanmgr` to delete temporary and malicious leftover files                |
| Update Windows                  | Install the latest security updates via *Settings > Windows Update*            |
| Use Command-Line Repairs        | Run `sfc /scannow` and `DISM /Online /Cleanup-Image /RestoreHealth`            |


# Day7 of training 

# Networking 

# 🔹 What is an IP Address?

IP Address (Internet Protocol Address) is a unique number assigned to each device on a network.

It identifies a host on a network and enables devices to communicate.


** Types of IP Addresses**

1. IPv4 (Internet Protocol version 4)

- Format: XXX.XXX.XXX.XXX (e.g. 192.168.1.1)

- 32-bit address (4 bytes)

- Range: 0.0.0.0 to 255.255.255.255

- About 4.3 billion unique addresses


2. IPv6

- 128-bit address (more than 340 undecillion addresses!)

- Format: 8 groups of 4 hexadecimal digits (e.g. 2001:0db8:85a3:0000:0000:8a2e:0370:7334)

- Developed due to IPv4 exhaustion

##  Classes of IPv4 Addresses

| **Class** | **Starting Range**               | **Purpose**              | **Default Subnet Mask**     |
|-----------|----------------------------------|---------------------------|-----------------------------|
| A         | 1.0.0.0 – 126.0.0.0              | Large networks            | 255.0.0.0 (/8)              |
| B         | 128.0.0.0 – 191.255.0.0          | Medium-sized networks     | 255.255.0.0 (/16)           |
| C         | 192.0.0.0 – 223.255.255.0        | Small networks            | 255.255.255.0 (/24)         |
| D         | 224.0.0.0 – 239.255.255.255      | Multicasting              | Not used for host addressing|
| E         | 240.0.0.0 – 255.255.255.255      | Research & Reserved       | Not used publicly           |

**What is Subnetting?**

Subnetting is the process of dividing a large network into smaller, manageable sub-networks (subnets).

Helps improve network performance, security, and IP address management.


 **Subnet Mask**

A subnet mask separates:

- Network portion of an IP address

- Host portion of an IP address

**Default Gateway**

A default gateway is a device (usually a router) that connects your local network to other networks, like the internet.

It acts like a door for your device to send data outside its local network.

**MAC Address**

MAC = Media Access Control Address

A unique identifier assigned to every network interface card (NIC) or device that connects to a network.

It's used to identify devices on a local network.

**DNS**

DNS is like the phonebook of the internet.

It translates human-friendly domain names (like www.google.com) into IP addresses (like 142.250.195.100).

**DHCP**

DHCP is a network protocol that automatically assigns IP addresses and other network settings to devices on a network.

It saves time and prevents IP conflicts by eliminating the need for manual configuration.

# Day8 of training 

# Basic Networking Commands


**1. ping**

Purpose:
Tests connectivity between your device and another (like a website or IP address).

**Syntax:**

ping <hostname or IP address>

**Example:**

ping google.com

**What It Does:**

- Sends ICMP Echo Request

- Receives ICMP Echo Reply

- Measures response time in ms


**Use Cases:**

- Check if a device is reachable

- Detect packet loss or network issues


**2. traceroute (Linux/macOS) / tracert (Windows)**

**Purpose:**
Shows the path your data takes through routers to reach a destination.

**Syntax:**

On Windows:


tracert <hostname or IP>

On Linux/macOS:


traceroute <hostname or IP>

**Example:**

tracert google.com

**What It Does:**

- Displays all the hops (routers) between you and the destination

- Shows delay (latency) at each hop


**Use Cases:**

- Identify where the network slows down or fails

- Diagnose routing problems


**3. ipconfig (Windows only)**

**Purpose:**
- Displays network configuration details of your system.

**Syntax:**

ipconfig

Advanced:

ipconfig /all

**What It Shows:**

IP address

Subnet mask

Default gateway

DNS servers

MAC address (as "Physical Address")


# Ethernet:
- It is used to connect devices with a physical cable so that they can communicate or access.

**How it Works:**
- Plug one end of an Ethernet cable into your PC's network port.
- Plug the other end of the cable into a modem or router.
- Your PC can now communicate over the network and access the internet.