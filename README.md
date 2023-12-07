# Git Command Cheat Sheet

## Overview

Summary of common git commands, and practice with branching

## Summary of Branch Workflow

1. Checkout and pull main
	```bash
	git checkout main
	git pull origin main
	```
1. Checkout new branch
	```bash
	git checkout -b someFeature
	```
1. Work, committing each complete task, until feature is complete

1. Pull remote main into local branch
	```bash
	git add .
	git commit -m "Complete feature"
	git pull origin main
	```
	* If auto merge succeeds, save and quit from 'vi' editor
	```
	:wq
	```
	* If 'CONFLICT', fix conflicts in all files and remove merge markers
	```bash
	git add .
	git commit -m "Fix merge conflicts"
	```
1. Push to remote branch
	```bash
	git push origin someFeature
	```
1. On Github, create a pull request and merge with main
1. Checkout and pull main
	```bash
	git checkout main
	git pull origin main
	```

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
* 'git checkout -b branchName' - create and checkout a new branch

## Remote Commmands
* 'git remote add orgigin URL' - set 'origin' as alias for remote repo 'URL'
* 'git push origin branchName' - push local commits to 'origin' repository on branch 'branchName'
* 'git pull origin branchName' - pull from remote repository 'origin' to 'branchName'