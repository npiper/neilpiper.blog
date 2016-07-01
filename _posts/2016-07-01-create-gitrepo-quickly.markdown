---
layout: post
title:  "How to rapidly create GIT projects into github"
date:   2016-07-01 22:36:09 +1000
categories: git projects github
---
# How to rapidly create GIT projects into github

Creating from the command line, it's possible to get a new project into GITHUB in a few simple lines.  This is using the curl API's for github.

Say you've created your first files...

# What you need

* A github account, username
* curl
* git locally installed


```
## Initialise
>git init

## Add and commit files in one step
>git add . && git commit -am "initial commit"

## Create a remote repo (prompts password)

## User is your github user , name the repo
> curl -u 'USER' https://api.github.com/user/repos -d '{"name":"REPO"}'

## Add the remote origin to the master
> git remote add origin git@github.com:USER/REPO.git

## Push it:
> git push origin master

```