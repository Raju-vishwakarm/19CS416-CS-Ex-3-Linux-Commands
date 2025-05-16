**Ex-3-Linux-Commands**

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**

![cs 1](https://github.com/user-attachments/assets/e8db9652-7660-48b4-9aaf-ad216c9977e2)



### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**

![Screenshot 2025-05-16 223237](https://github.com/user-attachments/assets/023f23d0-c3a9-4a9f-8cc7-62276d1a0a24)




### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**

![Screenshot 2025-05-16 223306](https://github.com/user-attachments/assets/c1b8133d-4b4a-4a85-b9ae-3030be538ae8)


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**

![Screenshot 2025-05-16 223333](https://github.com/user-attachments/assets/6dc6d6ca-660b-4fd7-9d75-63c94301e934)


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**

![Screenshot 2025-05-16 223344](https://github.com/user-attachments/assets/66810907-1811-4d0c-9591-d78bcdb24e23)


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**

![Screenshot 2025-05-16 223354](https://github.com/user-attachments/assets/6dc261aa-02c6-4e72-a6a4-a4b289ed8a12)


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

![Screenshot 2025-05-16 223406](https://github.com/user-attachments/assets/4ed068e4-1f93-4fff-8d96-f818b829fd97)


### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**

![Screenshot 2025-05-16 223421](https://github.com/user-attachments/assets/22a6b41e-af47-4c78-b909-e30cba8454ab)


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**

![Screenshot 2025-05-16 223429](https://github.com/user-attachments/assets/900df1e1-b583-47e9-bc0c-788fd5bd68a8)


### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**

![Screenshot 2025-05-16 223437](https://github.com/user-attachments/assets/59a388a1-8388-4e6b-9788-e485dc5d292a)



### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**

![Screenshot 2025-05-16 223443](https://github.com/user-attachments/assets/d7c6d534-0363-4ae3-99d6-6e1fe2ed1e65)


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**

![Screenshot 2025-05-16 223454](https://github.com/user-attachments/assets/c802c08c-6ec8-41cf-bad5-ac0317e6804b)


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**

![Screenshot 2025-05-16 223500](https://github.com/user-attachments/assets/2eff9ffe-9f7d-436a-ad94-5575cf0630bb)


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**

![Screenshot 2025-05-16 223510](https://github.com/user-attachments/assets/4944a2a0-0611-4ec4-9d32-f85f84c64681)


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**

![Screenshot 2025-05-16 223516](https://github.com/user-attachments/assets/3b094acd-b6f5-449e-ae03-2e3e9e31e712)


### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**

![Screenshot 2025-05-16 223524](https://github.com/user-attachments/assets/a7afd08b-3058-4609-be12-a4e45d905e9e)


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**

![Screenshot 2025-05-16 223531](https://github.com/user-attachments/assets/0d5d8c0d-7a72-43d5-b2a7-307bdc61457e)


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**

![Screenshot 2025-05-16 223616](https://github.com/user-attachments/assets/4313c570-ea77-403d-b4b6-05c750c551b5)


### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**

![Screenshot 2025-05-16 223625](https://github.com/user-attachments/assets/ed665d64-ef9b-4a8f-ac7b-21262065dbbd)


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**

![Screenshot 2025-05-16 223632](https://github.com/user-attachments/assets/20b2f370-94a0-419b-8323-d100eab0944e)


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**

![Screenshot 2025-05-16 223659](https://github.com/user-attachments/assets/672dd013-e677-4c76-b94f-65c13979e4fe)


### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**

![Screenshot 2025-05-16 223731](https://github.com/user-attachments/assets/61bc7fe4-9518-4e00-8f94-7a144d057938)


### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**

![Screenshot 2025-05-16 223741](https://github.com/user-attachments/assets/263e6261-eb29-4e37-a7ce-043d08031954)


### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**

![Screenshot 2025-05-16 223748](https://github.com/user-attachments/assets/bf355dcd-612f-424e-b294-1aeb2c2a6a39)


### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**

![Screenshot 2025-05-16 223800](https://github.com/user-attachments/assets/10346591-b00a-423f-ab14-0b473f4009ad)


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**

![Screenshot 2025-05-16 223808](https://github.com/user-attachments/assets/6e47926d-b932-43cd-ab95-e5b7e8d73bd1)


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**

![Screenshot 2025-05-16 223817](https://github.com/user-attachments/assets/18736d16-f40a-4458-8494-2d2fcd65b984)


### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**

![Screenshot 2025-05-16 223828](https://github.com/user-attachments/assets/429c0812-241b-48d7-b2eb-dc9cb8ac1be6)


### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**

![Screenshot 2025-05-16 223837](https://github.com/user-attachments/assets/fc64d2ce-154c-492d-80eb-2239abf382a4)


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**

![Screenshot 2025-05-16 223845](https://github.com/user-attachments/assets/2890d51b-4d12-430c-91b3-007824a41f26)


## Result

Linux commands are executed in the linux terminal successfully.
