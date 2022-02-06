---
title: TASK 5 [CYS BASICS]
author: Author
    - Aghilan A & Dhanvinesh K
date: 2022-02-04
tags:
    - Linux Fundamentals
    - CYS
    - Bash Scripting
---

## Find the instructions given below for the task. This task is divided into two parts
<br>
<hr>
<br>

<b><span style="color: #FF6363; font-size: 1.4rem;">Linux Commands</span></b>
<br>

Linux is an operating systems Kernel. Kernel facilitates the communication between hardware and software. Linux comes with CLI or the command line interface. CLI executes the commands that you enter. Ctrl+Alt+T to open the terminal and lets get started.

<br>

<b><span style="color: #FF6363; font-size: 1rem;">Why learning bash is necessary?</span></b>
- Learning bash makes us more flexible
- Command line skills help with building repeatable data processes in linux
- Working with files are much easier
- Doesn't consume much hardware resources to perform actions
- As unix shell is everywhere (android, mac) the commands can be used in any unix based OS.

<br>
<hr>
<br>

<b><span style="color: #FF6363; font-size: 1rem;">Basic linux commands:</span></b>
- `whoami` – displays the username
- `hostname` – displays the hostname
- `date` – displays the date
- `time` – displays the time
- `cal` – displays the calendar
- `clear` – clears the terminal (shell)
- `exit` – exits the bash shell
- `pwd` – displays the present working directory
- `ls` – displays all the files in the directory you are in
- `cd` – change directory
- `mkdir` – make new directory
- `rmdir` – remove directory
- `rm` – remove files
- `touch` – create a file
- `cp` – copy file
- `mv` – move file
- `find` – can find files
- `locate` – locate a file in a linux system
- `man` – manual page of a linux command
- `echo` – print statement
- `cat` – displays the contents of a file
- `head` – top contents of a file
- `tail` – bottom contents of a file
- `grep` – displays for a particular string from the contents of a file if present
- `diff` – compares the lines of two files
- `sudo` – gives root privileges (super user do)
- `df` – displays the available disk space
- `du` – displays the disk usage
- `zip, unzip` – to compress and extract zip archives
- `tar` – to extract and compress tar files or tar.gz files
- `chmod` – to change the file permissions
- `apropos` – finds what command can we use for a process

<br>
<hr>
<br>

<b><span style="color: #FF6363; font-size: 1.4rem;">Instructions</span></b>
<br>
Try each and every commands in your virtual machine to understand how the commands work and then solve the below tasks. Use manual pages <span style="color: lightgreen;">(For example, to know about the command ls, type <b><u>man ls</u></b> to access the manual page)</span> or help <span style="color: lightgreen;">( For example, <b><u>[command] --help</u></b> )</span>. 
<br>
<br>

> <span style="color: #FF6363; font-size: 1rem;">Optional:</span> <br> Try to install another ubuntu virtual machine or even you can use your host Windows OS. Use ssh command to establish a connection between them. Use scp command to transfer files between them. This can be useful in future or for your own use.

<br>
<hr>
<br>

<b><span style="color: #FF6363; font-size: 1.4rem;">TASKS</span></b>
<br>

<b><span style="color: #FF6363; font-size: 1rem;">PART 1:</b>

#### You are provided with a zip file which has numerous flags hidden inside it. You need to find the flags to earn points.
> The flag format: <span style="color: lightgreen;">&ensp;flag{Th1s\_i5\_h0w\_@\_fl4g\_look5}.</span>

<br>

#### Download the [<span style="color: #FE83C6"> zip file </span>](https://drive.google.com/file/d/1ZYxekUIS4Oi7PHq8EEsVk4gRUbDWrkl9/view?usp=sharing) in linux and extract it using tar (tar -x -f file.tar.gz) and start working.

<br>

#### More the number of flags you find the more points you will score. **There are 11 flags in total. Try to find all.**

####  Screenshot should be provided of every new command that you encounter. Valid flag submission is only through the screenshot. **The screenshot should have the complete screen along with date and time.** 

#### For **mv,mkdir,cp,rm** commands create a directory and move &amp; copy it to a different location and delete it. Take a screenshot and submit this too. Write down the flags after the respective screenshots properly.


<br>

<span style="color: #FA4EAB"> **Note:** </span><br>
<span style="color: #FA4EAB">&emsp; - Do not take screenshots for the same command twice </span><br>
<span style="color: #FA4EAB">&emsp; - Do not use GUI applications use bash shell only!!</span>

<br>
<hr>
<br>

<b><span style="color: #FF6363; font-size: 1rem;">PART 2:</style></b>

#### Part two contains questions that requires the correct command for the desired result as specified in the question. Please enter the correct command under each question in your pdf.

<br>
<b><span style="color: #FF6363; font-size: 1rem;"> Questions: </span></b>
<br>
<br>

- <span style="color:#95CD41;"> Write a bash script to echo your name 25 times </span>
- <span style="color:#95CD41;"> What command should I use to display the **first** 30 entries of syslog file?
- <span style="color:#95CD41;"> What command should I use to display the **last** 30 entries of syslog file?
- <span style="color:#95CD41;"> What command should I use to arrange the entries of a file
  - <span style="color:#95CD41;"> Alphabetically
  - <span style="color:#95CD41;"> Reverse order
  - <span style="color:#95CD41;"> Numerical order
- <span style="color:#95CD41;"> Copee is a hard-working cop. He found a case and almost at the verge of cracking it. It could be his best breakthrough. He has the list of criminals but lots of duplicates are there. He needs to find the only one that is **different.** He sought your help. How will you sort this issue?
- <span style="color:#95CD41;"> What are the four parts of file&#39;s permission?

<br>
<hr>
<br>

## RESOURCES:
<b><span style="color: #FF6363; font-size: 1rem;"> Linux Fundamentals:</span></b>
- [<span style="color: #FE83C6">The Linux Command Handbook (freecodecamp.org) </span>](https://www.freecodecamp.org/news/the-linux-commands-handbook/)
- [<span style="color: #FE83C6"> Home | Linux Journey </span>](https://linuxjourney.com/)
- [<span style="color: #FE83C6"> LabEx - Linux Basic Commands - Practice Online on LabEx </span>](https://labex.io/courses/linux-basic-commands-practice-online)
- [<span style="color: #FE83C6"> TryHackMe | Linux Fundamentals </span>](https://tryhackme.com/module/linux-fundamentals)

<br>
<b><span style="color: #FF6363; font-size: 1rem;"> Bash Shell Scripting</span></b>

- [<span style="color: #FE83C6"> Bash Script Tutorial</span>](https://linuxconfig.org/bash-scripting-tutorial-for-beginners)
- [<span style="color: #FE83C6">Bash Script Examples](https://linuxhint.com/30_bash_script_examples/)
- [<span style="color: #FE83C6"> Bash Scripts for Automation</span>](https://www.youtube.com/watch?app=desktop&v=PPQ8m8xQAs8)

<br>
<br>
