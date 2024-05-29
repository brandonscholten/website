# Getting Started with Git
written by Brandon Scholten

This document is meant as an abbreviated introduction to version control for Kent State CS students. If you'd like to learn more about version control systems from the people who built subversion, there's an entire book [here](https://support.apple.com/en-us/104984).

In most of your classes at Kent State, you most likely use Canvas to submit all of your assignments. In Computer Sciences classes, there may be an additional way for you to submit code using a version control system. Getting familiar with version control now will give you an advantage when you begin working with software on a team later in your career. 

Some studnets who click on this guide may wonder why I am reusing my introduction to version control from the Subversion guide for a guide on Git. This is because most version control sysetms have similar features, and regardless of the version control system you use, the first chapter of the Subversion book is a relatively easy to follow explanation of how version control systems work. 

## What is version control?

Typically when you are working on a software project, you would start by creating a folder to put all of the nseecary files in for the project. Over time these files will change. In the case of a CS class, you might create a folder for each lab or assignment you are tasked with and submit this folder once you have completed your assignment. 

A <b>version control system (VCS)</b> allows you to take a "snapshot" of your folder at any given time and return to it if nessecary. For those familiar with MacOS, this could be compared to the [time machine](https://support.apple.com/en-us/104984) feature that allows for incremental backups of a folder. As a developer, it is useful to save a copy of your work in this fashion each time you achieve something significant (such as finishing a feature or fixing a bug). 

### Repositories

In a version control system, a repository is a central location where a collection of files and directories are stored such that multiple people can access them. In our use case, both you and whoever is responsible for grading your work will have access to the same repository. As a Kent State CS Student, you will likely be given access to a folder in a repository which is named after your Flashline username. This repository lives in a server in the Math and Sciences building, and anyone who has been given access (you and your grader) can download and upload to the repository. Files that are downloaded from a repository and manipulated locally (on your computer) are in a <b>working copy</b>. The changes you make are then kept tract of by the VCS and applied when you upload (or commit) to the repository.

#### Copy, Modify, Merge

The two version control systems most people care about (Git and Subversion) use a model in which two or more users can download, modify, and upload files to the repository at the same time. 

While working on an assignment you will likely start by downloading your code from the repository. While you are editing your code your lab instructor may download the previous version that is in the repository and grade your previous work. This is a situation in which you and your grader now have separate working copies of the same repository. 

When the grader submits your grades to your folder, it will create a new version of the repository. As you finish and submit your assignment, the version control system will combine your changes with the most recent version of the folder in the repository. This means that a new version will be created with both your code and the grades that were posted earlier. 

Note that this is a functional but incomplete picture of how version control works. Refer to the book linked at the beginning of this writing for a more accurate explanation. 

## What is Git? 

## Using Git with VS Code


