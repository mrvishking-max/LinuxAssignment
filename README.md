# LinuxAssignment

# 🐧 Linux Basics Assignment

## # 1 Repository Setup

Create a GitHub repository named:

```
linux-basic-assignment-<your-name>
```

Create a **README.md** file and answer all questions inside it.

---

# SECTION 1 – Purpose and Example Usage

## # 1 pwd

Purpose: Displays the current working directory.

Example:

```
pwd
```

---

## # 2 ls

Purpose: Lists files and directories in the current location.

Example:

```
ls
```

---

## # 3 cd

Purpose: Changes the current directory.

Example:

```
cd Documents
```

---

## # 4 mkdir

Purpose: Creates a new directory.

Example:

```
mkdir project
```

---

## # 5 rm -rf

Purpose: Removes files or directories forcefully and recursively.

Example:

```
rm -rf project
```

---

## # 6 ps -ef

Purpose: Displays all running processes in the system.

Example:

```
ps -ef
```

---

## # 7 top

Purpose: Shows real-time system processes and CPU usage.

Example:

```
top
```

---

## # 8 df -h

Purpose: Shows disk space usage in human-readable format.

Example:

```
df -h
```

---

## # 9 history

Purpose: Displays previously executed commands.

Example:

```
history
```

---

## # 10 uptime

Purpose: Shows how long the system has been running.

Example:

```
uptime
```

---

# SECTION 2 – Linux Commands for Tasks

## # 1 Create a directory called project-files

```
mkdir project-files
```

---

## # 2 Navigate into the project-files directory

```
cd project-files
```

---

## # 3 Create a file called notes.txt using vi

```
vi notes.txt
```

---

## # 4 Display the contents of notes.txt

```
cat notes.txt
```

---

## # 5 Copy notes.txt to backup.txt

```
cp notes.txt backup.txt
```

---

## # 6 Show the first 100 lines of logs.txt

```
head -100 logs.txt
```

---

## # 7 Show the last 100 lines of logs.txt

```
tail -100 logs.txt
```

---

## # 8 Check disk storage usage

```
df -h
```

---

## # 9 Check running processes

```
ps -ef
```

---

## # 10 Delete a file called temp.txt

```
rm temp.txt
```

---

# SECTION 3 – Concept Questions

## # 1 Difference between > and >>

`>` overwrites the file content.

Example:

```
echo hello > file.txt
```

`>>` appends content to the file.

Example:

```
echo hello >> file.txt
```

---

## # 2 Purpose of kill -9

The `kill -9` command forcefully terminates a running process.

Example:

```
kill -9 1234
```

---

## # 3 Difference between rm and rmdir

`rm` removes files or directories.

Example:

```
rm file.txt
```

`rmdir` removes only empty directories.

Example:

```
rmdir folder
```

---

## # 4 Purpose of netstat -tulpn

This command displays active network connections and listening ports along with process IDs.

Example:

```
netstat -tulpn
```

---

## # 5 Purpose of ping

The `ping` command checks connectivity between systems over a network.

Example:

```
ping google.com
```

---

# SECTION 4 – Scenario Based Questions

## # 1 Check current working directory

```
pwd
```

---

## # 2 Create a directory devops inside home directory

```
mkdir ~/devops
```

---

## # 3 Check which process is using high CPU

```
top
```

---

## # 4 Check server connectivity to google.com

```
ping google.com
```

---

## # 5 View the last 50 lines of application.log

```
tail -50 application.log
```
