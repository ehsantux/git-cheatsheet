# git-cheatsheet
1- Because it simplifies the process of managing and maintaining software projects and gives us capabilities such as code retention, versioning and tracking written code.

2- A git repository has a directory named .git that is located inside the project and tracks all files of project. A good repository has readme,.gitignore and licence.

3- A good document should have a description of the project. What is this project? Where is it for? What does it contain? How to install and run it? and how the other persons can contribute to this project?

4- git clone command makes a copy of the repository to a specific target.

5- In the directory that is the local repository, run the git pull command.

6- Use checkout to change the working directory or to retrieve working tree files. 
git revert, reverts to the previous commit and creates a new commit after that and finally head points to the reverted commit. git reset gives a commit and transfers the Head to that commit and Removes subsequent commits.

7- In rebase, first the commits of the target branch (the brunch in which we want to rebase from the other brunch) are placed in the tree and the commits of the feature brunch are placed next to the tree. But in merge, changes of the target and feature commits are merged into a separate commit.

8- Use git log

9- Use git log <filename> command
  
10- The tag in git is a reference to a specific point in the git history. The tag is used to create a version at a specific point in the git. The tag is like a branch that does not change. For example, to create a tag called v.3.0, use the following command: 
  
  git tag -a v3.0 -m "New release for v3.0"
  
11- To participate in a project in git, we clone a copy of the project on our host and make the necessary changes to a dedicated branch. After applying the necessary changes, in order to merge changes we will send a merge request to the remote repository in main branch.
  
12- In a software project, if we have several developers and each developer wants to apply and test their changes independently and isolated in the project, it creates a branch of the project for itself and after the finalization of the changes, it merges in the final branch. Merge or rebase can be used to merge two branches.

