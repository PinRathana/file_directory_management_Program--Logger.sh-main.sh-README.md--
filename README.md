# File & Directory Manager

## Overview
The **File & Directory Manager** is a collection of Bash scripts designed to automate various file and directory management tasks. This includes functionalities such as listing files, creating backups, counting files, checking disk usage, searching for files, and compressing files. The program also logs all actions performed into a log file for easy tracking.

## Features
- **List Files**: Lists all files in a specified directory, showing their sizes, permissions, and timestamps.
- **Create Backup**: Creates a backup of a specified file or directory.
- **Count Files**: Counts the total number of files in a specified directory.
- **Check Disk Usage**: Displays the total disk usage of a specified directory.
- **Search for Files**: Searches for files by name or extension in a specified directory.
- **Compress Files**: Compresses a file or directory into a `.tar.gz` archive.
- **Logging**: Logs all actions performed into a file called `script.log`.

## Repositories Overview

This project consists of four repositories. You can access and use each repository separately based on your needs. Below are the details on how to clone, install, and use each of them.

## Repositories and Links

1. **list_files.sh and backup.sh Script**  
   - 🔗 [GitHub Repository - list_files.sh and backup.sh](https://github.com/YourUsername/list-files-script)  
   - **Usage**:  
     Clone the repository:
     ```bash
     git clone https://github.com/YourUsername/list-files-script.git
     cd list-files-script
     chmod +x *.sh
     ./list_files.sh
     ./backup.sh
     ```

2. **count_files.sh + disk_usage.sh Script**  
   - 🔗 [GitHub Repository - count_files.sh + disk_usage.sh](https://github.com/YourUsername/backup-script)  
   - **Usage**:  
     Clone the repository:
     ```bash
     git clone https://github.com/YourUsername/backup-script.git
     cd backup-script
     chmod +x *.sh
     ./count_files.sh
     ./disk_usage.sh
     ```

3. **search_file.sh + compress.sh Script**  
   - 🔗 [GitHub Repository - search_file.sh + compress.sh](https://github.com/YourUsername/count-files-script)  
   - **Usage**:  
     Clone the repository:
     ```bash
     git clone https://github.com/YourUsername/count-files-script.git
     cd count-files-script
     chmod +x *.sh
     ./search_file.sh
     ./compress.sh
     ```

4. **logger.sh and main.sh Script**  
   - 🔗 [GitHub Repository - logger.sh and main.sh](https://github.com/YourUsername/logger-script)  
   - **Usage**:  
     Clone the repository:
     ```bash
     git clone https://github.com/YourUsername/logger-script.git
     cd logger-script
     chmod +x *.sh
     ./logger.sh
     ./main.sh
     ```

## Directory Structure

file_directory_management_Program/ 
│── list_files.sh 
│── backup.sh 
│── count_files.sh 
│── disk_usage.sh 
│── search_file.sh 
│── compress.sh 
│── logger.sh 
│── main.sh 
│── README.md 
│── script.log  # Log file (automatically created)

## Installation

### Prerequisites
Ensure you have the following installed on your system:
- **Bash** (default shell on most Linux distributions and macOS)
- **GNU Core Utilities** (ls, cp, find, wc, du, tar)
- **tar** (for file compression)

#### Steps
1. **Clone or download this repository**:
   ```bash
   git clone https://github.com/PinRathana/file_directory_management_Program.git
   cd file_directory_management_Program

2. Give execution permissions to all scripts:

    chmod +x *.sh

## Usage

    To run the program, execute the main script:

    ./main.sh


## Individual Script Usage

    Each script can be run independently:

    + **List files**: `./list_files.sh`
    + **Backup files/directories**: `./backup.sh`
    + **Count files**: `./count_files.sh`
    + **Check disk usage**: `./disk_usage.sh`
    + **Search for files**: `./search_file.sh`
    + **Compress files**: `./compress.sh`
    + **Log actions**: `./logger.sh`
    + **Run main script**: `./main.sh`

## Dependencies

    + Bash shell
    + GNU core utilities (ls, cp, find, wc, du, tar)


## Logs

    All actions performed using the scripts are logged in script.log.
