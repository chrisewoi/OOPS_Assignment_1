# Part 2: Questions

### 1. List three major version control for software engineering

- Git
- CVS
- SVN (Apache Subversion)

### 2.	What are the main advantages to using Git in your software development, and how is it useful for game developers.

The main advantages are:
- Distributed development for easier scaling and collaboration
- Branching and merging for working on different versions at the same time in a non-linear way
- It's fast and efficient - most work is done locally and only pushed to the reposotory as needed
- Open source and free

It is useful for game developers for these reasons also. Game developers can work on a few different prototype ideas at a time for their game, such as how the player character's movement mechanics should work, or testing different types of enemies with their own git branches.


### 3.	Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge

#### Branch

A branch is a snapshot of your changes at a given point in time. You can treat this snapshot as its own side-project where changes are independent of the main timeline

#### Pull

Downloads a remote repository and updates the local repo to match it

#### Push

Uploads local repository content to a remote repository

#### repository

A location for tracking all changes in files and directories, and managing them

#### working copy

A clone of a repository that a user works on locally

#### merge

combines changes from two branches back into one. It combines commits from two different branches into a single history


### 4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.



### 5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.

- Meld
- Araxis Merge
- Beyond Compare
- CodeCompare
- KDiff3
- UltraCompare

### 6.	In a merged source code file, how does Git let you know there is a conflict?

It will contain a list of commits that  conflict between the merging branches

### 7.	What are the steps you can take to resolve Git conflicts?

On github, you can 
- click the pull request with a merge conflict you want to resolve
- Click Resolve conflicts
- Decide which changes you want to keep, or make a new change that incorporates changes from both branches
- Delete the conflict markers and make final changes
- Repeat for all conflicts
- Click Mark as resolved


### 8.	What does git revert do, and how can you use it?



### 9.	What does git reset do, and how can you use it? 



### 10.	What is the difference between git revert and git reset?



### 11.	True or False: It is okay to commit broken code to the main branch.



### 12.	True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.



### 13.	Describe what is DevOps, how is it useful for game developers?



### 14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3)



### 15.	What is CI/CD and how can it be used to automate the game development process?

