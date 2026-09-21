## Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
## NAME: ELANTHAMIZHAN R
## REG NUMBER: 212224080016
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
<img width="1920" height="1080" alt="Screenshot 2026-08-02 124820" src="https://github.com/user-attachments/assets/3861e879-18aa-41b4-a0be-7e38d6143220" />



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

<img width="1896" height="235" alt="image" src="https://github.com/user-attachments/assets/33614091-85fc-460e-b0eb-6160c5073d23" />


## 2) pwd Command
The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="601" height="58" alt="image" src="https://github.com/user-attachments/assets/069a3096-235a-495c-91ba-f5a448ae40ea" />


## 3) mkdir Command
The mkdir command is used to create a new directory under any directory.

Syntax: mkdir
<img width="1901" height="282" alt="image" src="https://github.com/user-attachments/assets/8e72dd2c-9639-45b1-b0cb-413940b0188d" />




## 4) rmdir Command
The rmdir command is used to delete a directory.

Syntax: rmdir

<img width="1884" height="277" alt="image" src="https://github.com/user-attachments/assets/a97322e6-89a4-467d-bf03-2ec5763c0303" />


## 5) cd Command
The cd command is used to change the current directory.

Syntax: cd

<img width="1902" height="131" alt="image" src="https://github.com/user-attachments/assets/addbb055-e944-4bf4-b53a-fc1e9818ef21" />


## 6) cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
<img width="807" height="156" alt="image" src="https://github.com/user-attachments/assets/778e661b-72af-4d0d-8fb0-311abfa04ab1" />



## 7) cp Command
The cp command is used to copy a file or directory.

Syntax: cp
<img width="616" height="101" alt="image" src="https://github.com/user-attachments/assets/01640e7f-25c6-4f19-bd8f-8586cfa11c9b" />


## 8) gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="1846" height="147" alt="image" src="https://github.com/user-attachments/assets/d3b93f37-8670-47f3-995e-d2d9c664585a" />

## 9) su Command
The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su

<img width="1891" height="335" alt="image" src="https://github.com/user-attachments/assets/521ecd9e-d8d9-4de7-8d6f-ce1012b20b9c" />


## 10) mv Command
The mv command is used to move a file or a directory form one location to another location.

Syntax: mv
<img width="1893" height="213" alt="image" src="https://github.com/user-attachments/assets/af682ffe-d4ea-4a7b-9fbb-16fca8a8e6bf" />



## 11) rename Command
The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="1550" height="159" alt="image" src="https://github.com/user-attachments/assets/93f5c42d-fd1a-496d-afc6-e30798976bcc" />


## 12) head Command
The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head
<img width="663" height="664" alt="image" src="https://github.com/user-attachments/assets/6478d7bb-4feb-42e1-ac61-7c7425a62871" />



## 13) tail Command
The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail

<img width="682" height="211" alt="image" src="https://github.com/user-attachments/assets/1b62f8b1-1ac7-4905-9455-48c166bdeedf" />


## 14) id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
  <img width="813" height="71" alt="image" src="https://github.com/user-attachments/assets/bf80cab3-9432-4326-9952-198f0722b724" />



## 15) grep Command
The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep

<img width="528" height="78" alt="image" src="https://github.com/user-attachments/assets/95fd4112-a087-4218-9659-7d9d869c69a5" />


## 16) tr Command
The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
<img width="562" height="193" alt="image" src="https://github.com/user-attachments/assets/080c7151-7d2d-443d-9c61-f0eeb99c276c" />



## 17) chmod Command
The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<file_name>
<img width="1032" height="149" alt="image" src="https://github.com/user-attachments/assets/c0317649-0b1b-4435-bc7c-06186076e201" />


## 18) tar Command
The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved] $ tar xvzf file.tar *.c

<img width="483" height="276" alt="image" src="https://github.com/user-attachments/assets/bf73e1f2-c593-4430-bd8a-618c07e161ab" />



## 19) ifconfig Command
The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
<img width="902" height="121" alt="image" src="https://github.com/user-attachments/assets/c32ac099-4fae-479a-af70-060c3393b53b" />



## 20) chmod 777 Command
The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name $chmod -R 777 /path/to/file/or/folder
<img width="571" height="179" alt="image" src="https://github.com/user-attachments/assets/8c396a2d-491e-4ceb-b55d-53b5623e5625" />


## 21) host Command
The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host or
<img width="771" height="114" alt="image" src="https://github.com/user-attachments/assets/50ca0d7a-8e9f-4859-8cd9-878e5ea2266c" />





## 22) sort Command
The sort command is used to sort files in alphabetical order.

Syntax:sort
<img width="650" height="136" alt="image" src="https://github.com/user-attachments/assets/af785c50-dcc4-4b2a-8be8-be364b89fb4e" />


## 23) cal Command
The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
<img width="409" height="172" alt="image" src="https://github.com/user-attachments/assets/946e8d82-7970-40b6-8c87-08b45d4bf42c" />


## 24) clear Command
Linux clear command is used to clear the terminal screen.

Syntax: clear
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/92dadccb-31e3-4767-8410-ba6aacefdfc5" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/45fec826-da8a-4637-b754-053f700c73ef" />



## 25) df Command
The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="954" height="229" alt="image" src="https://github.com/user-attachments/assets/9afdb62f-6908-477e-a65a-36992a21bb77" />


## 26) find Command
The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”
<img width="650" height="70" alt="image" src="https://github.com/user-attachments/assets/19551719-0d05-4628-b01a-ce3f0fa76ffb" />


## Result:
Thus, the execution of various Linux commands is executed successfully using Kali Linux.
