# Git

## One Time Setup

` git config --global user.name "Pierce Angeloff" `
` git config --global user.email "angeloffpm@s.dcsdk12.org" `

## Project Setup

` git init `

## 3 Step Repeating Commit Process
1. Make changes to code
2. Stage related changes
    * git add
3. Commit changes with a message
    * git commit -m "Message"

## Commands

* status -> Tell me what files have been staged or committed
* add -> Add a file to the stage
* rm --cached -> Remove a file from a stage
* commit -m "Present tense description of what changed"
* log -> enter to move down, q to quit
* checkout -- filename -> revert file to old commit

## Problems
* commit without -m -> Use Esc :wq to quit Vim
* wrong message in commit -> git commit --amend -m "New message"
* wrong commit -> git checkout COMMIT_ID