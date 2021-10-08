# How To Contribute to Open Source: Getting Started with Git
By Lisa Tagliaferri | September 8th 2021

## Introduction
Open-source projects that are hosted in public repositories benefit from contributions made by the broader developer community, and are typically managed through Git.

A distributed version control system, Git helps both individuals and teams contribute to and maintain open-source software projects. Free to download and use, Git is an example of an open-source project itself.

This tutorial will discuss the benefits of contributing to open-source projects, and go over installing and setting up Git so that you can contribute to software projects.

## Git

One of the most popular version control systems for software is Git. Git was created in 2005 by Linus Torvalds, the creator of the Linux kernel. Originally utilized for the development of the Linux kernel, Junio Hamano is the current maintainer of the project.

Many projects maintain their files in a Git repository, and sites like GitHub, GitLab, and Bitbucket have streamlined the process of sharing and contributing to code. Every working directory in Git is a full-fledged repository with complete history and tracking independent of network access or a central server.

Versions controls are indispensable tool in software development to track history of changes, revert to previous stages, and branch off to develop code without impacting main branches.

To use Git to contribute to open-source projects, let’s check if Git is installed, and if it’s not, let’s go through how to install it on your local machine.

## Check if Git is installed

First, you will want to check if you have Git command line tools installed on your computer. If you have been making repositories of your own code, then you likely have Git installed on your local machine. Some operating systems also come with Git installed, so it is worth checking before you install.

You can check whether Git is installed and what version you are using by opening up a terminal window in Linux or Mac, or a command prompt window in Windows, and typing the following command:

    $ git --version
    
However, if Git is not installed, you will receive an error similar to the following:

    -bash: git: command not found
    
    'git' is not recognized as an internal or external command, operable program, or batch file.

In this case, you should install Git into your machine. Let’s go through installation for several of the major operating systems.

## Installing Git on Linux

By far the easiest way of getting Git installed and ready to use is by using your version of Linux’s default repositories. Let’s go through how to install Git on your local Linux machine using this method.

### Installing Git on Ubuntu or Debian

You can install `git` with the package manager of your distribution. First, update your package list, for example running `sudo apt update` on Debian or Ubuntu.

Then, to install git :

    # Ubuntu and Debian
    $ sudo apt install git
    
    # CentOS
    $ sudo yum install git

    # Fedora
    $ sudo dnf install git

## Installing Git on macOS

On a local Macintosh computer, if you type a Git command into your Terminal window (as in `git --version` above), you’ll be prompted to install Git if it is not already on your system. When you receive this prompt, you should agree to have Git installed and follow the instructions and respond to the prompts in your Terminal window.

You can install the most recent version of Git onto your Mac by installing it through the binary installer. There is an OS X Git installer maintained and available for download through the Git website. Clicking here will cause the download to start automatically.

Once Git is fully installed, you can continue on to the section on Setting Up Git.

## Installing Git on Windows
For Windows, the official build is available for you to download through the [Git website](https://git-scm.com/downloads).

There is also an open-source project called [Git for Windows](https://gitforwindows.org/), which is separate from the official Git website. This tool provides both command line and graphical user interface tools for using Git effectively on your Windows machine. For more information about this project and to inspect and download the code, visit the Git for Windows project site.

Once Git is fully installed, you can continue on to the section on Setting Up Git.

## Setting Up Git
Now that you have Git installed, you need to do a few things so that the commit messages that will be generated for you will contain your correct information.

The easiest way of doing this is through the git config command. Specifically, we need to provide our name and email address because Git embeds this information into each commit we do. We can go ahead and add this information by typing:

    $ git config --global user.name "Your Name"
    $ git config --global user.email "youremail@domain.com"

We can review all of the configuration items that have been set by typing:

    $ git config --list

## Conclusion

With Git installed and set up on your local machine, you are now ready to use Git for version control of your own software projects as well as contribute to open-source projects that are open to the public.

Adding your own contributions to open-source software is a great way to become more involved in the broader developer community, and help to ensure that software made for the public is of high quality and fully representative of the end-users.
