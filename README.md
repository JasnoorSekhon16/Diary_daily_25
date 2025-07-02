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

#HDD
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
