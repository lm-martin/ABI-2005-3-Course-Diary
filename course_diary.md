# Notes about git

In this course we are being introduced to git

we will learn about git commands and workflows

In git we have two repositories, one local and one remote

A repository consists of working directory, staging area and repository proper

git offers wide range of commands to work in the different areas of a repository

# Here I provide a list of the command most offen used, as well as a quick explanation of their function

# Command list:

1. git add
	Moves changes from your working directory to the Staging Area. It tells Git, "I want to include these specific files in my next save."
	Syntax (single file): git add filename.txt
	Syntax (all changes): git add .

2. git commit
	Saves your staged changes to the local repository. It creates a permanent "snapshot" in your project's history. Every commit requires a message describing what you did.
	Syntax: git commit -m "Your descriptive message here"

3. git push
	Uploads your local commits to a remote server (like GitHub, GitLab, or Bitbucket). This shares your work with others.
	Syntax: git push <remote-name> <branch-name>
	Common Example: git push origin main

4. git status
	Shows the current state of your project. It tells you which files are modified, which are staged for a commit, and if your local branch is ahead of the remote server.
	Syntax: git status  


Example of a Standard Workflow:

Modify your files.

git add . (Prepare the changes).

git commit -m "Fix bug" (Save the changes locally).

git push (Upload the changes to the cloud).
