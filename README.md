# 🐧 Operating System Lab — Linux Environment

<p align="center">
  <img src="https://img.shields.io/badge/Operating%20System-Linux-orange?style=for-the-badge&logo=linux&logoColor=white" alt="Linux Badge">
  <img src="https://img.shields.io/badge/Language-C-blue?style=for-the-badge&logo=c&logoColor=white" alt="C Badge">
  <img src="https://img.shields.io/badge/Scripting-Bash-green?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash Badge">
  <img src="https://img.shields.io/badge/Platform-Linux-lightgrey?style=for-the-badge&logo=linux" alt="Linux Platform">
</p>

## 📌 About This Repository

Welcome to my **Operating System Lab** repository! 🚀

This repository contains practical implementations and experiments performed as part of the **Operating System (OS) Laboratory** using the Linux environment.

The purpose of this lab is to understand fundamental operating system concepts through hands-on practice, including Linux commands, Bash scripting, process management, memory management, CPU scheduling, file operations, and system calls.

The repository includes shell scripts and C programs designed to demonstrate how an operating system manages processes, memory, files, and system resources.

## 🎯 Objectives

- 🐧 Learn basic Linux commands and terminal operations.
- 📂 Understand file and directory management.
- 🔀 Practice input/output redirection and pipes.
- 📝 Develop shell scripts using Bash.
- 💻 Implement string operations using C and shell scripting.
- ⚙️ Understand process creation, execution, and termination.
- 🧠 Explore memory allocation and process memory maps.
- 📊 Observe CPU utilization and process resource consumption.
- 🔗 Understand parent-child processes and process IDs.
- 🛠️ Gain practical experience with Linux system utilities.

## 🧪 List of Experiments

| No. | Experiment | Tools / Concepts |
|---|---|---|
| 1 | Practice basic Bash commands, I/O redirection, pipes, file and directory operations, searching files, process management, and vi/nano editor commands. | Bash, Linux Commands |
| 2 | Display the date and save the output of the `who` command to a file. Write a `sed` command to swap the first and second words of each line in a file. | `date`, `who`, `sed` |
| 3 | Write a shell script to check whether a command-line argument is a file or directory. Write another script to convert filenames supplied as arguments to uppercase. | Bash Scripting |
| 4 | Write shell scripts to determine how long a specified user has been working on the system, display lines between specified line numbers, and delete lines containing a specified word from given files. | `who`, `sed`, `grep`, Bash |
| 5 | Perform string operations in shell scripting and C: extract a substring and find the length of a string. Compare execution times using the `time` command. | Bash, C, `time` |
| 6 | Write a C program that accepts a memory size in megabytes as a command-line argument and allocates that amount of memory. Observe memory usage using the `free` command. | C, `malloc()`, `free` |
| 7 | Write CPU-bound and I/O-bound C programs and observe CPU utilization and process behavior using `top` and its variants. | C, `top` |
| 8 | Observe the memory maps of the previous two lab programs using the `pmap` command. | `pmap`, Process Memory |
| 9 | Write a C program that creates a child process, waits for its termination, and displays its process ID. | `fork()`, `wait()`, `getpid()` |
| 10 | Write a C program that prints the address of a variable and runs a long loop. Execute multiple instances of the same program and compare their printed addresses. | C, Process Memory, `&`, `while(1)` |

## 🛠️ Technologies and Tools

- **Operating System:** Linux
- **Shell:** Bash
- **Programming Language:** C
- **Text Editors:** Vim / vi and Nano
- **Compiler:** GCC
- **Process Monitoring:** `top`, `ps`
- **Memory Monitoring:** `free`, `pmap`
- **File Processing:** `sed`, `grep`, `awk`
- **Process Management:** `fork()`, `wait()`, `getpid()`
- **Version Control:** Git and GitHub

## ⚙️ Installation and Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/harshit-singh-jamwal/Operating-System-LAB.git
```

### 2️⃣ Navigate to the Repository

```bash
cd Operating-System-LAB
```

### 3️⃣ Check the Available Files

```bash
ls
```

To display files, including hidden files:

```bash
ls -la
```

### 4️⃣ Install GCC (If Required)

For Ubuntu or Debian-based Linux distributions:

```bash
sudo apt update
sudo apt install build-essential
```

### 5️⃣ Compile and Run a C Program

For example, if your C program is named `program.c`:

```bash
gcc program.c -o program
./program
```

For a program that accepts command-line arguments:

```bash
gcc program.c -o program
./program 10
```

**Note:** Replace `program.c` and the arguments with the actual filename and inputs used by your experiment.

## 🐧 Useful Linux Commands

| Command | Purpose |
|---|---|
| `pwd` | Display the current working directory |
| `ls` | List files and directories |
| `cd` | Change directory |
| `mkdir` | Create a directory |
| `touch` | Create an empty file |
| `cp` | Copy files |
| `mv` | Move or rename files |
| `rm` | Remove files |
| `cat` | Display file contents |
| `grep` | Search for text |
| `sed` | Edit or transform text |
| `ps` | Display process information |
| `top` | Monitor running processes and CPU usage |
| `free -h` | Display memory usage |
| `pmap` | Display a process's memory map |
| `time` | Measure command execution time |
| `who` | Display logged-in users |
| `date` | Display the current date and time |
| `man` | Display a command's manual page |

## 🧠 Key Learning Outcomes

After completing these experiments, I aim to:

- Understand the Linux command-line environment.
- Write and execute Bash scripts.
- Perform file and text-processing operations.
- Compile and execute C programs in Linux.
- Understand process creation and parent-child relationships.
- Monitor CPU and memory utilization.
- Explore process memory layouts and virtual memory.
- Measure program execution time.
- Understand how operating systems manage system resources.

## 📁 Repository Structure

The repository is organized around the practical experiments performed during the OS laboratory.

```text
Operating-System-LAB/
│
├── README.md
├── Experiment-1/
├── Experiment-2/
├── Experiment-3/
├── ...
└── Experiment-10/
```

*The structure above is illustrative. The actual filenames and folder names may differ depending on how the experiments are organized in the repository.*

## 🎓 Academic Information

- **Student:** Harshit Singh Jamwal
- **Programme:** B.Tech — Computer Science and Engineering (AI & ML)
- **Institution:** Model Institute of Engineering and Technology (MIET), Jammu
- **Subject:** Operating System Laboratory
- **Environment:** Linux

## 👨‍💻 Author

**Harshit Singh Jamwal**

- GitHub: [@harshit-singh-jamwal](https://github.com/harshit-singh-jamwal)
- Repository: [Operating-System-LAB](https://github.com/harshit-singh-jamwal/Operating-System-LAB)

## ⭐ Support

If you find this repository useful for learning Linux commands, Bash scripting, C programming, and operating system concepts, consider giving it a ⭐ on GitHub!

---

<p align="center">
  💻 <b>Learn by Practicing • Understand by Experimenting • Grow by Building</b> 🚀
</p>
