---
layout: "article"
title: "Helpful Unix Tricks"
date: "2015-02-12"
categories: "post"
excerpt: "Want to know more about Unix? This is your one stop shop."
image:
  feature:
  teaser:
  thumb:
---

# Unix

### What?

Unix is just framework for the basic underlying structure of many modern operating systems.
Linux is an operating system kernel that is designed like Unix's kernel, and there are a
number of different distributions of Linux, including Ubuntu, Mint, Debian, and Fedora.
Macintosh OS is actually a Unix-based system as well. Windows, however, is not.

### Why?

Unix is a really powerful operating system that is basically an open box. It has many security features, and
is usually found in the form of open-source operating systems. Many servers are running different variations
of a Unix based operating system.

### Commands

* `ls` - Will list all files and directories in the current directory
* `cd` - Will change the directory to the one specified (as in `cd /home` or `cd Pictures`)
* `w` - Will list all current users and last command used
* `vim` - Great file editor, simply specify the file name after (as in `vim oldFile.txt` or create a new one with `vim newFile.txt`)
* `mkdir` - Creates a new directory with the name specified (as in `mkdir newDirectory` will create a new directory called "newDirectory")
* `chmod` - Changes permissions of the files or directories. The important ones are `chmod 700 filename`, `chmod 755 filename`, and `chmod 777 filename`
* `rm` - Remove! This will delete files. Used as `rm filename`
* `rmdir` - This will remove an empty directory. Used as `rmdir emptyDirectory`
* `sudo` - This is the command to give you administrator rights to a system. Use only if you actually know the admin password. This works by simply including the command infront of any other command you do not have permission to run as a standard user.
* `apt-get install` - App libraries that allow you to automatically install new programs and commands from a dedicated server. Usually needs `sudo`. Use as `sudo apt-get install programName`.
* `passwd` - this will allow you to change your password
* `exit` - This command will log you out.
* `shutdown` - This command will mess with power settings. `shutdown -h now` for true shutdown.
