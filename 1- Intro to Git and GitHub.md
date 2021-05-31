# Intro to GIT and Version Control
- [Intro to GIT and Version Control](#intro-to-git-and-version-control)
  - [**1. What is Version Control and why should you care?**](#1-what-is-version-control-and-why-should-you-care)
  - [**2. Git VS Github**](#2-git-vs-github)
  - [**3. Terminology**](#3-terminology)


<p align="center">
  <img width="460" height="300" src="https://github.com/Ironhack-Data-0621-Remote/GitHub_Basics/blob/main/Images/giphy.gif">
</p>


## **1. What is Version Control and why should you care?**

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. For the examples in this book, you will use software source code as the files being version controlled, though in reality you can do this with nearly any type of file on a computer.

If you are a graphic or web designer and want to keep every version of an image or layout (which you would most certainly want to), a Version Control System (VCS) is a very wise thing to use. It allows you to revert selected files back to a previous state, revert the entire project back to a previous state, compare changes over time, see who last modified something that might be causing a problem, who introduced an issue and when, and more. Using a VCS also generally means that if you screw things up or lose files, you can easily recover. In addition, you get all this for very little overhead.

GIT is a VCS system designed with the following goals in mind:

  - Speed

  - Simple design

  - Strong support for non-linear development (thousands of parallel branches)

  - Fully distributed

  - Able to handle large projects like the Linux kernel efficiently (speed and data size)

  - Not enough reasons to learn GIT. Well, it is an absolute industry standard so... deal with it

    More documentation 👉🏽 [here](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

## **2. Git VS Github**
  
  - **Git** is local VCS software that allows developers to save snapshots of their projects over time. It is generally best for individual use.
  
  - **GitHub** is a web-based platform that incorporates the version control features of git so that they can be used collaboratively. It also includes project and team management features, as well as opportunities for networking and social coding.

<p align="center">
  <img width="460" height="300" src="https://github.com/Ironhack-Data-0621-Remote/GitHub_Basics/blob/main/Images/GithubvsGit.jpeg">
</p>


## **3. Terminology**
  
  - **Repository or repo** : storage location for a software package ("a folder with git monitoring")
  - **Untracked** : a file or directory not monitored by git, does not belong to the repo
  tracked : a file git was instructed to monitor (through the add command.)

  - **Commit** : a point on the temporal line of a repository. A "snapshot" of all the changes we "made official", or the last state of staged files before we commited. Every commit has a unique id and must have a commit message. The more descriptive the message, the better.


  - **Local repo** : a repository of code on the computer you are currently using
    
  - **Remote** : a repository on a different machine (e.g.: Github)
    
  - **Forking a repo** : creating an alternative timeline for a repo, usually someones repo we want to have a copy of our own.
  cloning a repo : making a local copy of a remote repo. 


  - **Push** : sending the changes from local repo to a remote.
    

  - **Pull** : bringing changes of a remote repo to a local one. 
    
  - **.gitignore** : text file with files/folders we do not want git to track or ask about.

