---
layout: post
title:  "Better Git Log"
date:   2015-04-13 02:55:00
categories: git
---

I didn't use `git log` that much before. When I wanted to show the commit history I was using `tig` which is an awesome command that is bundled in packages for **apt-get** and **Homebrew**. 

Then I found that `git log` has a lot of awesome options that can make it really outstand. So I will show you some of them.

###1. `--graph`

`git log --graph` This will add a text based graphical representation of the commit history to the left hand side of the output. It is handy to visualize branch topology. You will find if the commit belong to the current branch or another one.

###2. `--decorated`
`git log --decorated` You can print the refs names of each commit

###3. `--author` 

###4. All together git log --graph --oneline --decorate 

`git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit`


