# lab-assignment
Lab Assingment Modules 1-4

# Question 1: Linux Environment Verification

# Objective

Perform basic environment verification on a lab machine as a junior systems engineer at IxD Systems.

# Assignment Overview

This repository contains my submission for the Linux Systems Engineering lab assignment. The assignment consists of 4 questions covering various aspects of Linux system administration and programming concepts.

# Repository Structure

lab-assignment/
├── README.md # This file
├── Question1/ # Linux Environment Verification
│ ├── commands_outputs.txt # All commands and their outputs
│ ├── explanation.md # Detailed explanations for each command
│ ├── user_info.txt # File created during Command 3
│ ├── log.txt # Sample log file for Command 7
│ └── screenshots/ # Screenshots of command executions

# Tasks Completed

1. **User Identity Verification** - Displayed username and group memberships
2. **Workspace Validation** - Checked current directory and listed files
3. **Environment Confirmation File** - Created and verified `user_info.txt`
4. **File Integrity Check** - Counted characters in created file
5. **Learning the Tools** - Explored `mkdir` manual page
6. **Home Directory Inspection** - Listed and sorted home directory contents
7. **Log Investigation** - Searched for "admin" patterns in log files
8. **System Information Check** - Displayed Linux kernel version
9. **Network Connectivity Test** - Verified connection to www.google.com
10. **System Health Awareness** - Checked system uptime and load averages

# Key Files in Question1

- `commands_outputs.txt`: Contains all 10 commands with their exact terminal outputs
- `explanation.md`: Detailed 1-2 sentence explanations for each command's purpose and significance
- `user_info.txt`: Actual file created during task execution
- `log.txt`: Sample log file demonstrating grep functionality
- `screenshots/`: Visual evidence of command executions

# Technical Implementation

# Concepts Demonstrated

- **User and Group Management**: Understanding system privileges
- **File Operations**: Creation, verification, and analysis
- **System Monitoring**: Checking uptime, load averages, and kernel versions
- **Network Diagnostics**: Basic connectivity testing
- **Text Processing**: Using grep for log analysis
- **Help System**: Effective use of manual pages

# Commands Used

- `whoami`, `groups` - User identity verification
- `pwd`, `ls -la` - Directory navigation and listing
- `echo`, `cat`, `wc` - File operations
- `grep` - Text pattern searching
- `uname -r` - System information
- `ping` - Network testing
- `uptime` - System health monitoring

# Question 1: Linux Environment Verification

# Objective

Perform basic environment verification on a lab machine as a junior systems engineer at IxD Systems.

# Assignment Overview

This repository contains my submission for the Linux Systems Engineering lab assignment. The assignment consists of 4 questions covering various aspects of Linux system administration and programming concepts.

# Repository Structure

lab-assignment/
├── README.md # This file
├── Question1/ # Linux Environment Verification
│ ├── commands_outputs.txt # All commands and their outputs
│ ├── explanation.md # Detailed explanations for each command
│ ├── user_info.txt # File created during Command 3
│ ├── log.txt # Sample log file for Command 7
│ └── screenshots/ # Screenshots of command executions

# Tasks Completed

1. **User Identity Verification** - Displayed username and group memberships
2. **Workspace Validation** - Checked current directory and listed files
3. **Environment Confirmation File** - Created and verified `user_info.txt`
4. **File Integrity Check** - Counted characters in created file
5. **Learning the Tools** - Explored `mkdir` manual page
6. **Home Directory Inspection** - Listed and sorted home directory contents
7. **Log Investigation** - Searched for "admin" patterns in log files
8. **System Information Check** - Displayed Linux kernel version
9. **Network Connectivity Test** - Verified connection to www.google.com
10. **System Health Awareness** - Checked system uptime and load averages

# Key Files in Question1

- `commands_outputs.txt`: Contains all 10 commands with their exact terminal outputs
- `explanation.md`: Detailed 1-2 sentence explanations for each command's purpose and significance
- `user_info.txt`: Actual file created during task execution
- `log.txt`: Sample log file demonstrating grep functionality
- `screenshots/`: Visual evidence of command executions

# Technical Implementation

# Concepts Demonstrated

- **User and Group Management**: Understanding system privileges
- **File Operations**: Creation, verification, and analysis
- **System Monitoring**: Checking uptime, load averages, and kernel versions
- **Network Diagnostics**: Basic connectivity testing
- **Text Processing**: Using grep for log analysis
- **Help System**: Effective use of manual pages

# Commands Used

- `whoami`, `groups` - User identity verification
- `pwd`, `ls -la` - Directory navigation and listing
- `echo`, `cat`, `wc` - File operations
- `grep` - Text pattern searching
- `uname -r` - System information
- `ping` - Network testing
- `uptime` - System health monitoring


# Question 2: File and Directory Management

# Overview

This directory contains the complete solution for Question 2 of the Linux Systems Engineering lab assignment. The task demonstrates practical file and directory management skills essential for a junior system administrator role at IxD Systems.

# Objective

Demonstrate understanding of Linux file and directory management commands through 10 sequential operations to organize project-related files in the home directory.

# Directory Structure

Question2/
├── commands_outputs.txt # All 10 commands with actual outputs
├── explanation.md # Detailed explanations for each command (1-2 sentences)
├── structure_diagram.txt # Visual representation of created directory hierarchy
├── screenshots/ # Screenshots of command execution
│ ├── command1.png # mkdir ~/documents
│ ├── command2.png # touch plan.txt
│ ├── command3.png # Content addition to plan.txt
│ ├── command4.png # File metadata verification
│ ├── command5.png # File duplication (cp)
│ ├── command6.png # Directory renaming (mv)
│ ├── command7.png # Archive structure creation
│ ├── command8.png # File organization (move to archive)
│ ├── command9.png # Recursive listing (find)
│ └── command10.png # Path verification (realpath)
└── README.md # This file


# Commands Executed

 1. **Project Workspace Setup**

mkdir ~/documents
Creates a directory named "documents" in the home directory to serve as the project workspace.

2. **File Creation**

cd ~/documents && touch plan.txt
Navigates to the documents directory and creates an empty file named "plan.txt" for project documentation.

3. **Content AAddition**

echo "Project Alpha: Weekly Tasks" > plan.txt
Writes structured project content into plan.txt using echo commands with redirection operators (> and >>).

4. **File Metadata Verification**

ls -la plan.txt && stat plan.txt
Displays file permissions, ownership, size, and detailed metadata using both ls and stat commands.

5. **File Duplication**

cp plan.txt plan_copy.txt
Creates an exact copy of plan.txt named plan_copy.txt for backup purposes.

6. **Directory Renaming**

mv ~/documents ~/project_documents
Renames the documents directory to project_documents to better reflect its purpose and scope.

7. **Archivial Structure**

mkdir ~/project_documents/archive
Creates an archive subdirectory within project_documents for organizing backup and historical files.

8. **File Organization**

mv ~/project_documents/plan_copy.txt ~/project_documents/archive/
Moves the duplicate file into the archive directory, demonstrating logical file organization.

9. **Recursive Listing**

find ~/project_documents -type f
Lists all files recursively within the project_documents directory to show complete structure.

10. **Path Verification**

realpath ~/project_documents/archive/plan_copy.txt
Displays the absolute path of the moved file, verifying its exact location in the filesystem.

# Final Directory Structure Created

/home/username/project_documents/
├── plan.txt                    (Original project plan with content)
└── archive/
    └── plan_copy.txt          (Backup copy in organized archive location)


# Question 3:

# Overview

This lab assignment demonstrates practical understanding of Linux file systems, focusing on link management, inode operations, and disk usage analysis. The assignment covers creating hard links, symbolic links, verifying inode information, and using disk utility commands.

# Objectives

Understand the difference between hard links and symbolic links

Learn how inodes work in Linux file systems

Practice disk usage analysis commands

Explore file metadata inspection

# Project Structure

q3-lab/
├── README.md                    # This file
├── commands.txt                # All commands used in the lab
├── explanation.md            # Explanationn of commands used
├──screenshots               # Screenshots of commands excecuted
└── sample_data.txt            # Original file created for the lab

1. File Creation
Create the sample file in your home directory:
cd ~
echo "This is sample text for Linux file management lab." > sample_data.txt
echo "Additional line of sample data." >> sample_data.txt

2. Hard Link Creation
Create a hard link:
ln sample_data.txt sample_hard.txt

3. Symbolic Link Creation
Create a symbolic link:
ln -s sample_data.txt sample_soft.txt

4. Inode Verification
Check inode numbers:
ls -i sample_data.txt sample_hard.txt sample_soft.txt

5. Inode Analysis
Expected Results:

sample_data.txt and sample_hard.txt: Same inode number

sample_soft.txt: Different inode number

Reason: Hard links share the same inode as they point directly to the same data blocks, while symbolic links are separate files containing path references.

6. File Metadata Inspection
View detailed file information:
ls -la sample_data.txt

7. Disk Usage Check
Check home directory usage:
du -sh ~

8. File Size Overview
List file sizes in home directory:
ls -lh ~

9. Link Deletion Test
Delete symbolic link and verify:
rm sample_soft.txt
ls -la sample_data.txt  # Verify original file still exists

10. Disk Utility Demonstration
Demonstrate du and df commands:

du (Disk Usage) Examples:
du -sh *                    # Human-readable sizes of all files/dirs
du -ah ~ | sort -hr        # All files sorted by size
du -csh ~                  # Total size with summary

df (Disk Free) Examples:
df -h                      # Human-readable disk space
df -i                      # Inode usage information
df -T                      # Show file system types
df -h --output=source,size,used,avail,pcent


# Question 4:

# Overview

This lab assignment focuses on Linux system monitoring, process management, and resource utilization. Students will practice commands for checking system uptime, analyzing processes, managing priorities, and monitoring disk/memory usage—all within their own user account without system configuration changes.

# Objectives

Monitor system resources and performance

Manage processes and priorities

Analyze CPU and memory usage

Practice output redirection and background jobs

Use disk analysis tools effectively

# Project Structure

q4-lab/
├── README.md                    # This file
├── commands_outputs.txt        # All commands used in the lab
├── system_report.txt           # Generated system report
├── explanation.md              # Explanation of commands used
└──screenshots               # Screenshots of commands excecuted

1. System Uptime Verification
Display time since last system boot:
uptime

Alternative detailed view:
cat /proc/uptime

Last boot time:
$ who -b

2. User Process Listing
List all processes running under your user account:
ps -u $(whoami)

Process count:
 ps -u $(whoami) | wc -l

Processes with more details:
 ps -u $(whoami) -o pid,ppid,cmd

3. CPU Usage Analysis
Identify process with highest CPU usage:
Top CPU consuming processes for user $(whoami):
 ps -u $(whoami) -o pid,pcpu,cmd --sort=-pcpu | head -5

Using top command (press q to exit):
top -u $(whoami) -n 1 -b | head -20

4. 4. Background Process Execution
Start a command in the background:
sleep 300 &

Verify it's running:
jobs -l

Process details:
 ps -u $(whoami) | grep sleep

Bringing to foreground to terminate:
 fg %1
Press Ctrl+C to terminate
^C

5. Process Priority Management
Change priority (niceness) of a process:
Starting a test process..."
 sleep 600 &
 TEST_PID=$!
Process started with PID: $TEST_PID

Current priority:
 ps -o pid,ni,cmd -p $TEST_PID

Changing niceness to +10 (lower priority)...
renice -n 10 -p $TEST_PID

Updated priority:
 ps -o pid,ni,cmd -p $TEST_PID

Terminating test process...
 kill $TEST_PID
 wait $TEST_PID 2>/dev/null

 6. Memory Usage Monitoring
Display memory usage in human-readable format:
free -h

Detailed memory info:
cat /proc/meminfo | head -10

Memory usage by process (top 5):
 ps -u $(whoami) -o pid,rss,cmd --sort=-rss | head -5

Using htop-like output:
ps -u $(whoami) -o pid,%mem,rss,cmd --sort=-%mem | head -5

7. Disk Space Inspection
Check filesystem containing home directory:
df -h $HOME

Detailed filesystem info:
 df -hT $HOME

All filesystems:
 df -h

Inode usage:
df -i $HOME

8. Shell Identification
Display current shell name:
echo $SHELL

Shell process:
 ps -p $$
Shell version:
 $SHELL --version | head -1

Alternative methods:"
Using echo \$0: $0"
Using ps -o comm= -p \$\$: $(ps -o comm= -p $$)

9. Output Redirection
Redirect system info to a file:

Creating system report..."
$ echo "=== SYSTEM REPORT ===" > system_report.txt
$ echo "Generated on: $(date)" >> system_report.txt
$ echo "" >> system_report.txt
$ echo "1. Uptime:" >> system_report.txt
$ uptime >> system_report.txt
$ echo "" >> system_report.txt
$ echo "2. Memory Info:" >> system_report.txt
$ free -h >> system_report.txt
$ echo "" >> system_report.txt
$ echo "3. Disk Usage:" >> system_report.txt
$ df -h >> system_report.txt
$ echo "" >> system_report.txt
$ echo "4. Current Processes:" >> system_report.txt
$ ps -u $(whoami) -o pid,cmd --sort=-pid | head -10 >> system_report.txt
$ echo "" >> system_report.txt
 System report saved to system_report.txt
First 20 lines of report:
 head -20 system_report.txt

 10. Disk Usage Visualization
Install ncdu (if not installed):
Checking if ncdu is installed..."
$ which ncdu || echo "ncdu not found, installing explanation..."
$ echo ""
$ echo "If ncdu is installed, typical usage would be:"
$ echo "$ ncdu ~"
$ echo ""
$ echo "Simulating ncdu output (if not installed):"
$ echo "ncdu (NCurses Disk Usage) is an interactive tool that provides:"
$ echo "1. Visual directory tree of disk usage"
$ echo "2. Ability to navigate with arrow keys"
$ echo "3. Sort by size with 's' key"
$ echo "4. Delete files with 'd' key"
$ echo "5. Export results with 'e' key"
$ echo ""
$ echo "Example alternative with du:"
$ du -h --max-depth=1 ~ | sort -hr | head -10
