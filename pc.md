## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
	- Git is a version control system that allows public users to post their projects and others to fork and work on them.

2. What is the difference between Git and GitHub?
	- Git is the software used for version control which allows for tracking changes in a coding project.
 
3. Why do we create a branch?
	- A branch allows you to change and modify an existing code without changing the actual code yet. It is a duplicate of the working copy to make changes.

4. What is the purpose of a Pull Request?
	- A Pull request asks for your changes to the code to be applied to the main code. Someone would review your code and accept your pull request. The code would
	- then merge with the working code.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
	- git checkout main. git checkout is the command, git checkout -b "name of new branch" is the command to make and enter a new branch

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
	- git fetch finds the latest meta-data from the original code but does not transfer any code. git pull finds the latest meta-data and transfers a copy to the 
	- repository. git merge combines all branches into 1 default branch to integrate all changes.

7. What is a merge conflict?
	- when two branches or commits have changes to the same line of code that cannot be merged by git. Other examples include if a user deletes a file that 
	- someone else was editing their would be a merge conflict. 

8. How do you resolve a merge conflict?
	- To resolve a merge conflict, you would have to find the conflicting lines of code in one of the branches and change them so they can better merge with the 
	- other branches. 
