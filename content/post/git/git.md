---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Git"
subtitle: "In recent years, the popularity of Git has been showing explosive growth. This version control system is used by various open source projects."
summary: "In recent years, the popularity of Git has been showing explosive growth. This version control system is used by various open source projects."
authors: [Viktoria Zheldakova]
tags: [git]
categories: []
date: 2022-05-07T15:31:02+03:00
lastmod: 2022-05-07T15:31:02+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

![Git logo](/post/git/git-logo.png)

In programming, the version control system is responsible for saving code at checkpoints — a special technology that can be connected to any project. The version control system insures against errors and returns the code to the state when everything worked. 

## A Brief history of Git

Like many things in life, Git started with a bit of creative chaos and heated arguments.

The Linux kernel is a fairly large open source project. For most of the Linux kernel development time (1991-2002), changes were passed between developers in the form of patches and archives. In 2002, the Linux kernel project started using the proprietary decentralized BitKeeper SCR.

In 2005, the relationship between the Linux kernel development community and the commercial company that developed BitKeeper ceased, and free use of the utility became impossible. This prompted the Linux kernel development community (and in particular Linus Torvalds, the creator of Linux) to develop their own utility, taking into account the lessons learned while working with BitKeeper. Some of the goals pursued by the new system were:

 - Speed
 - Simple architecture
 - Good support for non-linear development (thousands of parallel branches)
 - Full decentralization
    
The ability to effectively manage large projects, such as the Linux kernel (speed and reasonable use of disk space)
Since its introduction in 2005, Git has evolved into an easy-to-use system while retaining its original qualities. It is surprisingly fast, efficient in working with large projects and has an excellent branch system for non-linear development.

## Git is a distributed version system

Version control systems can be local, centralized, or distributed.

A local system stores files on a single device, a centralized system uses a shared server, and a distributed system uses shared cloud storage and local devices of team members. It is convenient to work with large projects in a local system, but it is difficult to interact with a remote team.

In a centralized system, remote work is established, but everything is tied to one server. Any failure or hacking can damage the project files.

Remote work is established in the distributed system. If something happens to the files of the main repository, it is easy to restore the project from a copy of any team member.

## Git is not GitHub

Git is a program that needs to be installed and connected to a project to manage a version control system. GitHub is a repository site for project version histories: you connect Git, register on GitHub, create an online repository and transfer files from Git to GitHub.

Git is the most popular version control system, and GitHub is an online code repository. Git and GitHub are configured to interact and therefore are often used as a single mechanism for working with a project.

## Why would a beginner learn Git

Git is used in most companies where at least two developers work on the project:

 - A new person comes to the company and clones the project repository on a PC.
 - Gets a task, creates a new branch and writes code.
 - When everything is ready, it sends a request to add code to the master branch.
 - Other developers look at the code, leave comments and point out errors.
 - The beginner completes the code, updates the master branch and moves on to the next task.
 
