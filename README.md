# FantasyOS – Operating System Simulation

**FantasyOS** is a simulated operating system developed as a **final year project** for the **Operating Systems Lab** course. It demonstrates core OS functionalities such as **process scheduling**, **resource management**, and **multitasking**, along with a custom-built **graphical user interface (GUI)**.

## Key Features

- **Command-line interface** to execute and manage programs  
- **Process creation**, execution, and **FIFO scheduling**  
- **Resource management** (CPU cores, RAM, disk)  
- **Shared memory** and **multithreading** using `pthreads`  
- GUI-based desktop with built-in applications:
  - **Calculator**
  - **Notepad**
  - **Number Guessing Game**
  - **Prime**, **Factorial**, **Armstrong** checkers
  - **Time & Date** display
  - **File operations**

## Technologies Used

- **C++** for core OS simulation  
- **GTK+ 3** for GUI development  
- **POSIX Threads (pthreads)**  
- **Linux system calls** and **shared memory (shm)**

## How to Run

```bash
sudo apt install libgtk-3-dev
cd ~/Desktop/OS-Project
./build.sh 4 8 256
