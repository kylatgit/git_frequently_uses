Git Frequently Used Commands
============================

## Preparation:

每台電腦設定一次就好:

  `>git config --global user.name NAME`
  
  `>git config --global user.email EMAIL`
  
  `>git config --global core.editor "gvim -f"` (or `"subl -w"`)

## Start:

In a directory which u want to push the contained files:

  `>git init`
  
  `>git status`
  
  `>git add .`
  
  `>git commit -u "message"`
  
## Generate SSH Keys:

  `>find ~/.ssh` (check existence)
  
  `>sudo apt-get install xclip`
  
  `>cd ~/.ssh`
  
  `>ssh-keygen -t rsa -C "EMAIL"` (need entering passphrase)
  
  `>xclip -sel clip < ~/.ssh/id_rsa_pub`
  
## Push and Pull:

  `>git remote add origin git@github.com:NAME/repository_name.git` (create first at Github)
  
  `>git status`
  
  `>git commit -m "Initial Commit:"`
  
  `>git pull -u orogin master`
  
  `>git push -u origon master`
  
## Once Changed:

  `>cp DIR/test.md ./README.md`
  
  `>git add .`
  
  `> git commit -m "Modified:"`
  
  `>git pull`
  
  `>git push`
