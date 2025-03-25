# Git Commands

- [Git Commands](#git-commands)
  - [Git Notes](#git-notes)
  - [To do list](#to-do-list)

```git
git clone <repo-URL>
```
>clone an repo from a remote source.

 
```git
git init
```
>initialize the git repo.

```git
git status
```
>shows the current state of the working directory and staging area.

```git
git commit -m"<message>" 
```
>takes a snapshot of staged folders/files.
```git
git add <. / name of the folder/file>
```
>adds itemt to staging folder.

```git
git push -u origin <branch-name>  
```
>Uploads committed items to a remote repo.\
>Origin represents the name of the remote repo.\
>-u means upstream. (push to the specific branch instead of the default)


```git
git pull origin <branch-name>
```
>pull a repo from a specific branch.

```git
git remote -v 
```
>Displays current remove origin.\
-v means verbose.


```git
#git remote add origin <URL>
```
>Adds a remote reop to the local repo.


```git
git config --list.
```
>lists configs
```git
git --version.
```
>showes version of git
```git
git checkout -b name 
```
>Changes the current branch\
>-b means branch.

```git
git merge (branchname)
```
>merges two branches.

```git
git reset 
```
>Undoes changes in the directory\
>Returns to previous commit snapshots.
```bash
ls -a 
```
>-a Shows hidden folders







## Git Notes


ls -a show hidden folders

#ignore is used to hide configs and sensitive infomation

#enviroment keys, hide bloated folders

#git remote add origin https://github.com/xt10101/week2-git-tech503.git


#git branch -M main -M move




push can go to the wrong place




>**What is git?**
>>version control software, tracking changes to files and folders over time, code sharing.  
>>Can roll back to prior versions, have mutiple people working on the same project, Isolate bugs or errors, open source. Speed, Branching and merging feature.
---
>**How does git Work?**
>> .git folder stores meta data and change history
>>changes are added to the staging area which will be added to the .git folder
>>a commit saves the snapshot of the projects state

>>. means the folder is hidden

---

>**Folder states of git**
>>1. Init git repo (un-tracked) in the same folder
>>1. When added to staging they will be tracked (staging) (only saves what has changed)
>>1. When comitted they will be finalised(snapshot)  

---

>**What is GitHub**
>>* denctralised version of the the Repo
>>* A provider
---

>**alternatives to github**
>>BitBucket
>>GitLab
---

>**Why are tools like git are important for Devops**?
>>Need to make things more effecient, Needs to be easily accessable and easily fluid
---

.gitingore

The tilde (~) is a Linux "shortcut" to denote a user's home directory

. current dierectory

.. back directory 


## To do list
* SSH
* Post Repo to Git
* HEAD https://learngitbranching.js.org/



