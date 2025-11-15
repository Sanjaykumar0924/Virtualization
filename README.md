## Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
## NAME: SANJAY KUMAR H
## REG NUMBER: 212223040182
## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox
## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:
- Machine with Internet access
- Minimum 4 GB RAM
- Sufficient storage space
## Steps:
1.Download Oracle VM VirtualBox:

- Visit Oracle VirtualBox Official Site
- Download installer for your OS (Windows/macOS/Linux).

2.Install Oracle VM VirtualBox (Example: Windows):

- Launch Installer → Allow Changes → Click Next.
- Choose Installation Options → Click Next.
- Accept Network Interface Warning → Click Yes.
- Click Install.
- Finish Installation and Launch VirtualBox.

3.Configure VirtualBox:

- Open VirtualBox.
- Click New → Name VM → Select Type (Linux/Windows) and Version.
- Allocate:
  
     Minimum 2 GB RAM
  
     Create Virtual Hard Disk (20 GB recommended).
  
- Start Virtual Machine and provide ISO to install OS.
## Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux
## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
- Oracle VM VirtualBox Installed
- 4 GB RAM and 20 GB Storage Minimum
- Kali Linux ISO image
## Steps:

1.Download Kali Linux ISO:
- Visit Kali Linux Official Site
- Download 64-bit ISO (Installer version).
  
2.Create a New Virtual Machine:
- Open VirtualBox → Click New.
- Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).

3. Allocate Memory:
- Minimum 2 GB RAM (recommended 4 GB).
  
4.Create Virtual Hard Disk:
- Select VDI (VirtualBox Disk Image).
- Choose Dynamically allocated.
- Set Disk size to 20 GB or more.
  
5.Configure ISO Image:
- Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
  
6.Start Installation:
- Boot Virtual Machine → Choose Graphical Install.
- Set Language, Region, Keyboard.
- Configure Network → Set Hostname (e.g., kali).
- Set root password.
- Disk Partitioning: Use entire disk → All files in one partition.
- Install System → Install GRUB Bootloader → Finish Installation.
  
7.Login to Kali Linux:
- Use root credentials.
  
8.(Optional) Install Guest Additions:
- Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
  
## Snapshots:

AWS Account Creation Snapshot
## Snapshot 1: Installing Oracle VirtualBox image
<img width="927" height="497" alt="Screenshot 2025-08-28 103507" src="https://github.com/user-attachments/assets/80010f1b-318d-437f-962c-a741cfda0d3d" />


## Snapshot 2: Kali Running in Virtual image
<img width="935" height="573" alt="Screenshot 2025-08-28 103519" src="https://github.com/user-attachments/assets/4894b551-1dc5-4ffd-8354-eadb514f50ba" />


## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali
## About Linux:
- Open-source operating system.
- Kernel manages communication between hardware and software.
- Commands are case-sensitive.
## Commands:
## 1) ls Command
The ls command is used to display a list of content of a directory.

Syntax: ls

<img width="855" height="68" alt="cs1" src="https://github.com/user-attachments/assets/f2f46d3b-604e-4c5c-8229-c7ca373282c2" />


## 2) pwd Command
The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="250" height="67" alt="cs2" src="https://github.com/user-attachments/assets/ed6c9de2-037f-4c56-bb03-b81df8c0241b" />


## 3) mkdir Command
The mkdir command is used to create a new directory under any directory.

Syntax: mkdir

<img width="930" height="116" alt="cs3" src="https://github.com/user-attachments/assets/11912044-da1b-4871-8437-23e2bfe86dfb" />


## 4) rmdir Command
The rmdir command is used to delete a directory.

Syntax: rmdir

<img width="888" height="127" alt="cs4" src="https://github.com/user-attachments/assets/1d3dabb8-df45-48c7-84f8-23dfc91e86d1" />


## 5) cd Command
The cd command is used to change the current directory.

Syntax: cd

<img width="354" height="158" alt="cs5" src="https://github.com/user-attachments/assets/ab7062f1-24ad-4e23-9460-fd2f937e7b51" />


## 6) cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="350" height="183" alt="cs6" src="https://github.com/user-attachments/assets/367c2256-e65c-4251-94b4-968e150a1f24" />


## 7) cp Command
The cp command is used to copy a file or directory.

Syntax: cp

<img width="334" height="133" alt="cs7" src="https://github.com/user-attachments/assets/7437249d-aaa5-430e-a242-c2037f9cf381" />


## 8) gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="501" height="40" alt="cs8" src="https://github.com/user-attachments/assets/aea7bca5-5c26-46bb-a180-986681a80e14" />


## 9) su Command
The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su

<img width="296" height="88" alt="cs9" src="https://github.com/user-attachments/assets/7ac4ef75-ca8e-4d35-8d53-0aaee9637d26" />


## 10) mv Command
The mv command is used to move a file or a directory form one location to another location.

Syntax: mv

<img width="363" height="265" alt="cs10" src="https://github.com/user-attachments/assets/82dfea24-c76b-4f78-ba13-62c8b1322160" />


## 11) rename Command
The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="462" height="171" alt="cs11" src="https://github.com/user-attachments/assets/926c9950-4260-437d-bb81-040c3a7670bb" />


## 12) head Command
The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head

<img width="394" height="528" alt="cs12" src="https://github.com/user-attachments/assets/73a75ddb-cb76-4f6d-b59c-6779272f29a0" />



## Result:
Thus, the execution of various Linux commands is executed successfully using Kali Linux.
