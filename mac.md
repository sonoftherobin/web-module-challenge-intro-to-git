## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 
Git is a decentralized version control system.  It also keeps a record or history of th project logging all versions of the code and all changes made.

2. What is the difference between Git and GitHub? 

Git is the software used for version control.  Git hub is a host for git repositories, it als serves as an online community for developers.

3. Why do we create a branch? 

Branches allow multiple developers to work on the same project without affecting the master.

4. What is the purpose of a Pull Request?

A pull request is how a developer uploads his/her changes to a specific project on git hub, it allows others to view the changes but does not inherently affect the main branch.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.   

git checkout main

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do? 

git pull is the command to use when you want to recieve the lates version of the code that has been commited to Github
git merge is how you would combine different versions(branches) of a project into one. i.e. a local branch onto the main branch.
git fetch allows you to download from aseperate repository than the one you are working on

7. What is a merge conflict?

A merge conflict happens when two branches have competing changes(commits) to the same line of code or one has deleted a file that another has edited  etc. 

8. How do you resolve a merge conflict?

The line(s) in conflict must be manually edited. Some can be resolved with the conflict editor on github, some will need to be resolved by editing one of the competing local clones
