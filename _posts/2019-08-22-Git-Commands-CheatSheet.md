---
layout: post
title: Git Commands Cheatsheet.
image: hyper.png
date: 2019-08-22 01:27 +0530
tags: [technologies,IDE]
categories: Tools
---


See the Regarding Post on Introduction to Git [Click Here](https://codewithdev.me/2019/08/15/How-to-use-git/)

Here We Go! The Git Commands CheatSheet is here...


### Prequisites 

 * Install `Git` 
 * Create a Folder anywhere in the Drive and Right Click with `Git Bash Here` to Initiate your directory and open.
 * Follow the related Commands whichever you want on the Command Prompt.
 
 
 
 
#### Basic Path Commands( Similar to Command Prompt Commands)
 
 1. `cd <space><path>`: To change the directory or to jump from one directory to another Directory.
 
 2. `cd<space>..`: To go one step back from one directory to another directory.
 
 3. `touch<space><filename>`: To create a new file on specified Path.
 
 
#### Configuration & Settings
 
 1. `git --version` : To get to know the current version of your Git.
 
 2. `git --config` : To configure your File and related info
 
 
#### Getting and Creating Repositaries
 
 1. `git init` : To initialize the Directory and preparing the directory for the first time Commit.
 
 2. `git add.`: Adding the file to index for indexing and before commiting.
 
 3. `git commit`: Commiting file and adding to the Staging Area before pushing directly to the repo.
 
#### Basic Snapshotting
 
 1. `git status`: To know the status of the directory whether it has staged, pushed or pulled.
 
 2.`git mv<space><filename><pathname>`: To move one directory to another directory or file.
 
 3.`git reset`: To reset the file or repositary.
     * Caution: `git reset` works only when the directory is in staged area. 
 
 4.`git branch`: To check in which Branch you are currently posting your Repo.
 
 5.`git branch<space><Branch name>`: To create a new Branch in Your Repo.
 
 6.`git push` : After staging instializes the directory for the Final Push in the Repos.
 
 7. `git revert`: To revert the changes you have while you are in Staging area.
 
 
 For more commands see the `Git Documentation` from here [Click Here](https://git-scm.com/docs)
 
 
   >_Did you liked this blog? So Dont forget to leave a comment, I would love to hear your suggestion and queries._
