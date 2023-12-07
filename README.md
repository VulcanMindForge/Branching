# Git Command Cheat Sheet

## Overview

Summary of common git commands, and practice with branching

## Basic Commands
* 'git init' - initialize local git repository
* 'git add filename.ext' - add file to be committed
* 'git add .' - add all files in folder to be committed
* 'git commit -m "message"' - commit files to repository/save changes. Requires informational message


## Info Commands
* 'git status' - indicates what files have changed since last commit
* 'git log' - provides log history of commits with messages
* 'git log --oneline' - list commit history compact format
* 'git config -l' - list local git config
* 'git help' - show get help

## Branching commands
* 'git branch' - list local branches
* 'git branch branchName' - create local branch
* 'git checkout branchName' - move to branch

## Remote Commmands
* 'git remote add orgigin URL' - set 'origin' as alias for remote repo 'URL'
* 'git push origin branchName' - push local commits to 'origin' repository on branch 'branchName'