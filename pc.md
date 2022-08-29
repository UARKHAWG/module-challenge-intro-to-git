## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?  Git is an Open Source Distributed Version Control System.
2. What is the difference between Git and GitHub?  Git is a version control system which tracks the changes when working with computer codes while GitHub is a Web-based Git version control repository hosting service.
3. Why do we create a branch?  You should create a new branch when you're doing development work that is somewhat experimental in nature. A branch in Git is a way to keep developing and coding a new feature or modification to the software and still not affecting the main part of the project. We can also say that branches create another line of development in the project. The primary or default branch in Git is the master branch (similar to a trunk of the tree). As soon as the repository creates, so does the main branch (or the default branch).

4. What is the purpose of a Pull Request?  Also referred to as a merge request – is an event that takes place in software development when a contributor/developer is ready to begin the process of merging new code changes with the main project repository. Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main. $ git switch -c [branch-name]
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
$ git fetch
Downloads all history from the remote tracking branches
$ git merge [branch]
Combines the specified branch’s history into the current branch. This is usually done in pull requests, but is an important Git operation.
$ git pull
Updates your current local working branch with all new commits from the corresponding remote branch on GitHub. git pull is a combination of git fetch and git merge
8. What is a merge conflict?  Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge.
9. How do you resolve a merge conflict?  You can resolve merge conflicts using the command line and a text editor.
