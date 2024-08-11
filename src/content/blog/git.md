---
title: 'Contribute to Open Source using Git'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Aug 2 2022'
heroImage: '/git.jpg'
---

When I started using Github , i was messed up with all the commands clone,push,commit etc . I wasted lot of time watching different videos , reading blogs but none of them helped out :/ So , I decided to write one blog that will help the beginners to start with their favourite projects on github❤

### What is Github?
**GitHub*** is a Git repository hosting service, but it adds many of its own features. While **Git** is a command line tool, GitHub provides a Web-based graphical interface.

Now,without wasting more time take a look at this simplest guide for git ✔


### Setup:

Download git for Windows- https://gitforwindows.org/

Download git for Linux- https://git-scm.com/download/linux

Download git for OSX- https://git-scm.com/download/mac

#### Step 1:
Fork your own copy of the project to which you want to contribute.
Forked copy of original project
On the right corner of the project , you will see the fork button. This step will create a new copy of the project that will be owned by you .
After fork , you will see yourUserName/ProjectName as new repository in your profile .You will get something like this after fork-


#### Step 2:
Clone the project on which you want to work.In GitBash(in desired directory), write clone command.
Usage : git clone url
url- Clone url from forked copy of the original project.
Clone Url

#### Step 3:
After clone , open the project in suitable IDE like Android Studio , Sublime.Now you can make desired changes in the forked copy on your editor . Always work on a new branch and don’t mess up the master branch.
To create a new branch- git branch branchname
To shift to new branch- git checkout branchname
To check all the available branches- git branch

#### Step 4:
After making changes in the forked copy , You can check the modified files using the command- git status

To add all the changed files : git add -A

To add specific file : git add filename

#### Step 5:
Commit all the changes using the command :

git commit -m”commit_message”

#### Step 6:
Push all the commited files using the command :

git push origin branchname

#### Step 7:
Now you have done some changes in your forked copy of original project 🎉

To tell the author of the original project about changes you made you need to do is Make a pull request . How to do that ?
All you need to do is click on the New Pull Request button on left side of the github page .

And Congratulations! You have created your first Pull request :)

