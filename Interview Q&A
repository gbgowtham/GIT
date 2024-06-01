# GIT:

1.  What is GIT?
  Git is a distributed version control system.
it designed to handle from small to very large projects
git works with speed and efficiency. 
Git allows multiple developers to work on the same project simultaneously without interfering with each other's work. 
Git always track the changes in source code, 


2.  What is GITHUB?
  GitHub is a web-based platform built around Git,and Its user-friendly interface 
GitHub has become a central hub for software development, particularly in the open-source community, 
Github is distributed version control system. 
GitHub offers a range of features that enhance collaboration, code review and project management.


3.  What is diff btw GIT vs GITHUB?
  Git is a software, while Git-Hub is a service
Git installed locally in system while the Git-Hub hosted in Web
Git is a command Line Tool While Git-Hub is Graphical User Interface
Git is a tool to manage different versions of edit,Made to the file of git repository while GitHub is a space to upload  copy of the git repository


4.  What is diff btw GIT vs SVN?
Feature                    Git                             SVN

VCS                     Distributed                Centralized
Branching and merging   Easy and efficient         More complex and can be slow
Offline support         Yes                        No
Performance             Faster                     Slower
Learning curve          Steeper                    Easier
Popularity              More popular               Less popular




5.  What is GIT Merge?
  Git Merge command is used to merge a developer code from one branch to Another branch.
eg: consider that we have two branches, master and feature. 
The master branch is the main branch of our project, 
and the feature branch contains a new feature that we are working on it and then commit it. 
Then, switch to the master branch and merge the feature branch with master branch by using folling command "git merge feature"



6.  What is GIT Rebase?
  git rebase is a way of moving the changes from one branch onto another branch.
git rebase create a linear history.
It mostly used for to avoid merge conflict


7.  Diff btw GIT Merge & GIT Rebase?
git merge is a way of combining changes from one branch (source branch) into another branch (target branch) where as 
git rebase is a way of moving the changes from one branch onto another branch.

git merge keep the history of both branches.
git rebase create a linear history.


8.  How will you resolve Merge Conflicts?
merge conflicts will resolved with the heip of following command 

git config --gobal merge.tool vimdiff
git config --gobal merge.conflictstyle diff3
git config --gobal mergetool.prompt false
git mergetool


9.  Diff Btw Fork,Clone & Branch?
Fork is a way to create a copy of a repository to your github account
clone is used to pull a complete repository from GitHub repository to local repository

 
10. Diff btw Pull & Fetch?

pull--> if we pull the source code from remote repository, to get updated source code, the source code will copied in local repo and working directory of the git server
command : git pull repo_url

Fetch--> if we Fetch the source code from remote repository, to get updated source code, the source code will copied only in local repo of the git server
command : git Fetch repo_url


11. What is GIT Push?
git push command used to push the source code from local repository to remote repository,
command : git push origin master 


12. What is GIT Clone?
clone is used to pull a complete repository from GitHub repository to local repository

13. How many ways we clone our repo?
3-ways to clone,
-->Using the command line
-->Using the Git GUI
-->Using Visual Studio

14. What is GIT Stash?
GIT Stash is a temporary storage area,  
the incompleted code in working directory saves in the stash area for later use, 
and then reverts back to working copy


15. What is .gitignore?
.gitignore help to keep Git-Repo clean and organized, by ignoring unnecessary files and directory.  it easier to manage repository and collaborate with other developer


16. What is the difference between git stash apply vs git stash pop command?
git stash apply : git stash apply copy the stash code to working directory,
git stash pop : git stash pop move the stash code to working directory.


17. What is GIT Cherry-pick?
GIT Cherry-pick command used to pick a paticular commit in a branch,  but the internal commit id will change when cherry-pick is done

18. What is Pull Request in GIT?
Pull Request is a notification to the repository owner that changes have been made to a branch and that the contributor would like to have those changes merged into the main codebase.

19. What are the branching strategy or git workflow?


20. What is GIT Squash?
Git squash is a command that combines multiple commits into a single commit. 
It is often used to clean up the commit history before merging a branch into another branch.


21. How to revert a bad commit which is already pushed?
git revert commit_id , In git revert, the wrong source code commit is removed but the reference commit mgs will display in log 

22. How to revert previous commit in git?


23. Diff btw GIT soft reset & hard reset?
GIT soft reset : git reset --soft commit_id 
git soft reset will delete only commit_id and the code remain same 


git hard reset : git reset --hard commit_id 
git hard reset will delete both commit and code.

24. Diff btw GIT Local vs GIT Remote?
Git is a tool to manage different versions of edit,Made to the file of git repository 

while GitHub is a space to upload  copy of the git repository



25. What is GIT Fork?
Fork is a way to create a copy of a repository to your github account


26. Diff btw Revert & reset?
revert 
git revert commit_id , In git revert, the wrong source code commit is removed but the reference commit mgs will display in log 


reset
there are two types of reset,they are
GIT soft reset : git reset --soft commit_id 
git soft reset will delete only commit_id and the code remain same 


git hard reset : git reset --hard commit_id 
git hard reset will delete both commit and code.


27. How to disable forking in github?
directly we can't disable the fork in git, but we can change the github repo privately. so that No one can fork that application


28. How will you secure your github account?
-->Use two-factor authentication (2FA):  2FA requires a temporary code from an authentication app or SMS to verify access to the repository.
-->Use strong passwords: Use a strong password that is at least 12 characters long and includes a mix of upper and lower case letters.
-->Don't share accounts or passwords: Never let users share GitHub accounts or passwords.
-->Secure devices: Ensure that devices with access to your source code are properly secured.
-->Use HTTPS encryption: GitHub Pages provides HTTPS encryption by default, it help secure data transmission between users and your website.
-->Use a secret manager: instead of hardcoding authentication credentials like tokens, keys, or app-related secrets into your code.

29. Command to Create Branch, Delete branch, Rename a branch

Create Branch: git branch BRANCH_NAME

Delete branch: git branch -d BRANCH_NAME or git branch -D BRANCH_NAME (To delete branch Forcefully)

Rename a branch : git branch -m OLD_BRANCH_NAME NEW_BRANCH_NAME


30. How will you switch from one branch to another branch
To switch one branch to another branch, The following command is used :
git checkout BRANCH_NAME
eg: consider that we are in master branch, we need to switch to feature branch.. "git checkout feature" command is use 



31. Command to restore delete branch
To restore delete branch, we use "git reflog" command, to view the reflog id with commit mgs 
choose the specfic reflog id and use the following command 
"git branch BRANCH_NAME REFLOG_ID" or "git checkout -b BRANCH_NAME REFLOG_ID"



32. Command to merge feature to master/main branch

git merge FEATURE_BRANCH



33. Command to check merged branches in master

To check merged branches in master : git branch --merged master

To check no merged branches in master : git branch --no-merged master


34. What is the command to modify or change your commit?

	"git commit --amend" command can only be used to modify the most recent commit. 
If you want to modify an older commit, then we will need to use the "git rebase" command.


35. How to restrict commit on github?

Branch protection rules: use branch protection rules to restrict who can push to a branch, and require pull requests before merging.

Required status checks: require status checks to pass before a commit can be merged.

Signed commits: require commits to be signed with a GPG key. A GPG key, or GNU Privacy Guard key, is a public-private key pair used to digitally sign files and verify their authenticity

Protected branches: protect a branch so that only certain people can push to it.

36. How to remove a file from git without removing it from your file system?

	To remove a file from Git without removing it from your local filesystem, use the "git rm --cached" command.




37. When do you use git rebase instead of git merge?
	If we want to preserve the history of our repository, we should use git merge. 

	If we want to create a linear history for our repository, or if you are working on a private branch, we can use git rebase.

38. What is command to create/delete/rename a user in github?
	gh repo create <repository-name> --public --description "Repository description"
	gh repo delete <repository-owner>/<repository-name>
	gh repo rename <new-repository-name>
	gh auth login


39. What is GITHUB Actions and how it works?
	GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your build, test, and deployment pipeline. 
we can create workflows that build and test every pull request to your repository, or deploy merged pull requests to production.


40. Diff Btw GITHUB & Github Actions? Diff btw Github actions & Jenkins?




41.How will intergate git with jenkins



---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Interview Q&A:
--------------

1)      What is GIT?

GIT is a distributed version control system and source code management (SCM) system with an emphasis to handle small and large projects with speed and efficiency.

2)      What is a repository in GIT?

A repository contains a directory named .git, where git keeps all of its metadata for the repository. The content of the .git directory are private to git.

3)      What is the command you can use to write a commit message?

The command that is used to write a commit message is “git commit –a”.  The –a on the command line instructs git to commit the new content of all tracked files that have been modified. You can use “git add<file>” before git commit –a if new files need to be committed for the first time.

4)      What is the difference between GIT and SVN?

The difference between GIT and SVN is

a)      Git is less preferred for handling extremely large files or frequently changing binary files while SVN can handle multiple projects stored in the same repository.

b)      GIT does not support ‘commits’ across multiple branches or tags.  Subversion allows the creation of folders at any location in the repository layout.

c)        Gits are unchangeable, while Subversion allows committers to treat a tag as a branch and to create multiple revisions under a tag root.

5)      What are the advantages of using GIT?

a)      Data redundancy and replication

b)      High availability

c)       Only one.git directory per repository

d)      Superior disk utilization and network performance

e)      Collaboration friendly

f)       Any sort of projects can use GIT

6)      What language is used in GIT?

GIT is fast, and ‘C’ language makes this possible by reducing the overhead of runtimes associated with higher languages.

7)      What is the function of ‘GIT PUSH’ in GIT?

‘GIT PUSH’ updates remote refs along with associated objects.

8)      Why GIT better than Subversion?

GIT is an open source version control system; it will allow you to run ‘versions’ of a project, which show the changes that were made to the code overtime also it allows you keep the backtrack if necessary and undo those changes.  Multiple developers can checkout, and upload changes and each change can then be attributed to a specific developer.

9)      What is “Staging Area” or “Index” in GIT?

Before completing the commits, it can be formatted and reviewed in an intermediate area known as ‘Staging Area’ or ‘Index’.

10)   What is GIT stash?

GIT stash takes the current state of the working directory and index and puts in on the stack for later and gives you back a clean working directory.  So in case if you are in the middle of something and need to jump over to the other job, and at the same time you don’t want to lose your current edits then you can use GIT stash.

11)   What is GIT stash drop?

When you are done with the stashed item or want to remove it from the list, run the git ‘stash drop’ command.  It will remove the last added stash item by default, and it can also remove a specific item if you include as an argument.

12)   How will you know in GIT if a branch has been already merged into master?

Git branch—merged lists the branches that have been merged into the current branch

Git branch—-no merged lists the branches that have not been merged

13)   What is the function of git clone?

The git clone command creates a copy of an existing Git repository.  To get the copy of a central repository, ‘cloning’  is the most common way used by programmers.

14)   What is the function of ‘git config’?

The ‘git config’ command is a convenient way to set configuration options for your Git installation.  Behaviour of a repository, user info, preferences etc. can be defined through this command.

15)   What does commit object contain?

a)      A set of files, representing the state of a project at a given point of time

b)      Reference to parent commit objects

c)       An SHAI name, a 40 character string that uniquely identifies the commit object.

16)   How can you create a repository in Git?

In Git, to create a repository, create a directory for the project if it does not exist, and then run command “git init”. By running this command .git directory will be created in the project directory, the directory does not need to be empty.

17)   What is ‘head’ in git and how many heads can be created in a repository?

A ‘head’ is simply a reference to a commit object. In every repository, there is a default head referred as “Master”.  A repository can contain any number of heads.

18)   What is the purpose of branching in GIT?

The purpose of branching in GIT is that you can create your own branch and jump between those branches. It will allow you to go to your previous work keeping your recent work intact.

19)   What is the common branching pattern in GIT?

The common way of creating branch in GIT is to maintain one as “Main" branch and create another branch to implement new features. This pattern is particularly useful when there are multiple developers working on a single project.

20)   How can you bring a new feature in the main branch?

To bring a new feature in the main branch, you can use a command “git merge” or “git pull command”.

21)   What is a ‘conflict’ in git?

A ‘conflict’ arises when the commit that has to be merged has some change in one place, and the current commit also has a change at the same place. Git will not be able to predict which change should take precedence.

22)   How can conflict in git resolved?

To resolve the conflict in git, edit the files to fix the conflicting changes and then add the resolved files by running “git add” after that to commit the repaired merge,  run “git commit”.  Git remembers that you are in the middle of a merger, so it sets the parents of the commit correctly.

23)   To delete a branch what is the command that is used?

Once your development branch is merged into the main branch, you don’t need development branch.  
To delete a branch use, the command “git branch –d [head]”.

24)   What is another option for merging in git?

“Rebasing” is an alternative to merging in git.

25)   What is the syntax for “Rebasing” in Git?

The syntax used for rebase is “git rebase [new-commit] “

26)   What is the difference between ‘git remote’ and ‘git clone’?

‘git remote add’  just creates an entry in your git config that specifies a name for a particular URL.  While, ‘git clone’ creates a new git repository by copying and existing one located at the URI.

27)   What is GIT version control?

With the help of GIT version control, you can track the history of a collection of files and includes the functionality to revert the collection of files to another version.  Each version captures a snapshot of the file system at a certain point of time. A collection of files and their complete history are stored in a repository.

28)   Mention some of the best graphical GIT client for LINUX?

Some of the best GIT client for LINUX is

a)      Git Cola
b)      Git-g
c)       Smart git
d)      Giggle
e)      Git GUI
f)       qGit

29)   What is Subgit? Why to use Subgit?

‘Subgit’ is a tool for a smooth, stress-free SVN to Git migration.  Subgit is a solution for a company -wide migration from SVN to Git that is:

a)      It is much better than git-svn
b)      No requirement to change the infrastructure that is already placed
c)       Allows to use all git and all sub-version features
d)      Provides genuine stress –free migration experience.

30)   What is the function of ‘git diff ’ in git?

‘git diff ’ shows the changes between commits, commit and working tree etc.

31)   What is ‘git status’ is used for?

As ‘Git Status’ shows you the difference between the working directory and the index, it is helpful in understanding a git more comprehensively.

32)   What is the difference between the ‘git diff ’and ‘git status’?

‘git diff’ is similar to ‘git status’, but it shows the differences between various commits and also between the working directory and index.

33)   What is the function of ‘git checkout’ in git?

A ‘git checkout’ command is used to update directories or specific files in your working tree with those from another branch without merging it in the whole branch.

34)   What is the function of ‘git rm’?

To remove the file from the staging area and also off your disk ‘git rm’ is used.

35)   What is the function of ‘git stash apply’?

When you want to continue working where you have left your work, ‘git stash apply’ command is used to bring back the saved changes onto the working directory.

36)   What is the use of ‘git log’?

To find specific commits in your project history- by author, date, content or history ‘git log’ is used.

37)   What is ‘git add’ is used for?

‘git add’ adds file changes in your existing directory to your index.

38)   What is the function of ‘git reset’?

The function of ‘Git Reset’ is to reset your index as well as the working directory to the state of your last commit.

39)   What is git Is-tree?

‘git Is-tree’ represents a tree object including the mode and the name of each item and the SHA-1 value of the blob or the tree.

40)   How git instaweb is used?

‘Git Instaweb’ automatically directs a web browser and runs webserver with an interface into your local repository.

41)   What does ‘hooks’ consist of in git?

This directory consists of Shell scripts which are activated after running the corresponding Git commands.  For example, git will try to execute the post-commit script after you run a commit.

42)   Explain what is commit message?

Commit message is a feature of git which appears when you commit a change. Git provides you a text editor where you can enter the modifications made in commits.

43)   How can you fix a broken commit?

To fix any broken commit, you will use the command “git commit—amend”. By running this command, you can fix the broken commit message in the editor.

44)   Why is it advisable to create an additional commit rather than amending an existing commit?

There are couple of reason

a)      The amend operation will destroy the state that was previously saved in a commit.  If it’s just the commit message being changed then that’s not an issue.  But if the contents are being amended then chances of eliminating something important remains more.

b)      Abusing “git commit- amend” can cause a small commit to grow and acquire unrelated changes.

45)   What is ‘bare repository’ in GIT?

To co-ordinate with the distributed development and developers team, especially when you are working on a project from multiple computers ‘Bare Repository’ is used. A bare repository comprises of a version history of your code.

46)   Name a few Git repository hosting services

Pikacode
Visual Studio Online
GitHub
GitEnterprise
SourceForge.net

47) What is the difference between Git and Github?

Git is a revision control system, a tool to manage your source code history.

GitHub is a hosting service for Git repositories.

GitHub is a website where you can upload a copy of your Git repository. It is a Git repository hosting service, which offers all of the distributed revision control and source code management (SCM) functionality of Git as well as adding its own features.

48) How do you rate GIT in terms of speed?

Git is fast. Speed and performance has been a primary design goal of the Git from the start. With Git, nearly all operations are performed locally, giving it a huge speed advantage on centralized systems that constantly have to communicate with a server somewhere.

Git was built to work on the Linux kernel, meaning that it has had to effectively handle large repositories from day one. Git is written in C, reducing the overhead of runtimes associated with higher-level languages.

49) In Git how do you revert a commit that has already been pushed and made public?

There can be two answers to this question and make sure that you include both because any of the below options can be used depending on the situation:

Remove or fix the bad file in a new commit and push it to the remote repository. This is the most natural way to fix an error. Once you have made necessary changes to the file, commit it to the remote repository for that I will use
git commit -m “commit message” .

Create a new commit that undoes all changes that were made in the bad commit.to do this I will use a command
git revert <name of bad commit>

50) What is the difference between git pull and git fetch?

Git pull command pulls new changes or commits from a particular branch from your central repository and updates your target branch in your local repository.

Git fetch is also used for the same purpose but it works in a slightly different way. When you perform a git fetch, it pulls all new commits from the desired branch and stores it in a new branch in your local repository. If you want to reflect these changes in your target branch, git fetch must be followed with a git merge. Your target branch will only be updated after merging the target branch and fetched branch. Just to make it easy for you, remember the equation below:

Git pull = git fetch + git merge





=================================================================================================================================================




  
