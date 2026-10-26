---
layout: default
---

## Introduction

The Command-line tools course taught me the basics of scripting, text processing, software management and connecting to and working on remote servers. This page is a summary of the course modules and what I learnt from them.

## Module 1: Introduction to Command Line Environments

This module was essentially an introduction to setting up and working in a command-line environment. Below are some commands featured in this section and what they relate to:

|Navigation |Viewing Text |Directories|
|-----------|:-----------:|----------:|
|`ls`       |`cat`        |`mkdir`    |
|`pwd`      |`less`       |`cp -R`    |
|`cd`       |`nano`       |`rmdir`    |

## Module 2: Text Processing in UNIX

Having established an understanding of how to navigate and work in a command-line environment, module 2 taught me how to actually process text in UNIX and revealed why working in a command-line environment is useful and even preferable for such tasks.
This module introduces pipelines, useful for stringing multiple operations together. Regular expressions (`grep`) featured heavily, along with `sed`, which were used to find and isolate words and phrases from texts. 
Combined with `tr`, `sort` and `uniq`, we learnt how to transform texts into frequency lists, sentence-per-line format and N-grams, all usefull for turning a text into analysable data. 

## Module 3: Scripting, Configuration Files and Installing Programs

<img src="assets/images/automation.png" alt="Photo" hspace="20" width="30%" align="right"/>
Having learnt how to create pipelines, the logical next step was scripting; turning the painstaking pipelines for the transformations we learnt in module 2 into files that can be saved and called upon as needed. The shell script dialect we learnt was bash.
We also learnt how to make permanent changes to environment variables in our command line profiles by edititng configuration files like .bashrc and getting root access with commands like `su` and `sudo`. 
This was done in preparation for learning how to install software. We learnt how to run python from a command line, install packages and create virtual environments. At this point I was really starting to grow in confidence regarding my ability to manage and use a command line environment.

## Module 4: Using ssh, scp and Version Control

This module was about working with remote servers and version control with github. We learnt how to connect with a remote server using `ssh` and copying data to and from a server using `scp`. 
I was not expecting to learn how to do this when starting the course but found it exciting to learn how. Learning how to operate Git on a command line was also very useful as we were taught how to manage branches and push changes to github.



 

 

