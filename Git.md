 # Git
 ## One Time Setup
 
 `git config --global user.name "Alex Hauser"`
`git config --global user.email "hauserap@s.dcsdk12.org"`

## Project Setup

`git init`
` touch .gitignore`
Add `*.class` to save the .gitignore file and save it.
` git add .`
` git commit -m"Initial commit"`
 

## 3 Step Repeating Commit Process
1. Make changes to code
2. Stage realted changes
    * git add
3. Commit changes with a message
    * git commit -m "Message"

## Commands

* status -> tell me what files have been staged or commited
* add ->  add a file to the stage
* rm--cached-> remove a file from stage 
* commit- m "Present tense description of what changed"
* git log-> enter to move down, q to quit
* git checkout -- filename -> discard changes



## Problem

* commit without -m-> use esc :wq to quit vim
* wrong message -> git commit --amend -m"New message"
* wrong commit -> git checkout COMMIT_ID

