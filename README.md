# Week 1: Linux Hands-on Lab

## Overview
This project demonstrates basic Linux file management, directory
navigation, file searching, and process identification using Ubuntu
on WSL2.

## Tasks Completed

### 1. Create the project workspace
Command:
```bash
mkdir -p ~/cloud-devops/week1
cd ~/cloud-devops/week1
pwd
```
Created the Week 1 project directory.

### 2. Create a file
Command:
```bash
touch notes.txt
ls -l
```
Created the notes.txt file.

### 3. Add text to the file
Command:
```bash
echo "Week 1: Learning Linux commands for Cloud and DevOps." > notes.txt
cat notes.txt
```
Added text and verified the file contents.

### 4. Create the scripts directory
Command:
```bash
mkdir scripts
ls -l
```
Created the scripts directory.

### 5. Move the file
Command:
```bash
mv notes.txt scripts/
ls -l scripts/
ls -R
```
Moved notes.txt into scripts/.

### 6. Search for the file
Command:
```bash
find . -name "notes.txt"
```
Located the file at ./scripts/notes.txt.

### 7. Identify a running process
Commands:
```bash
ps -ef
echo $$
ps -p $$ -o pid,ppid,comm
```
Listed running processes and identified the current shell's PID.

## Project Structure

```text
week1/
├── README.md
├── screenshots/
└── scripts/
    └── notes.txt
```

## Evidence

Screenshots demonstrating the tasks are available in the
`screenshots/` directory.

## Environment
- Operating System: Windows 11 with Ubuntu on WSL2
- Shell: Bash
- Version Control: Git


