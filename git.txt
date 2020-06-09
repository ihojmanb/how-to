How to git
Adding an existing project to GitHub using the command line

Create a new repository on GitHub. To avoid errors, do not initialize the new repository with README, license, or gitignore files. You can add these files after your project has been pushed to GitHub.
Open Terminal.

Change the current working directory to your local project.

Initialize the local directory as a Git repository.
$ git init

Add the files in your new local repository. This stages them for the first commit.
$ git add .

Commit the files that you've staged in your local repository.
$git commit -m "First commit"

At the top of your GitHub repository's Quick Setup page, click  to copy the remote repository URL.
$ git remote add origin remote repository URL
# Sets the new remote
$ git remote -v
# Verifies the new remote URL

Push the changes in your local repository to GitHub.
$git push -u origin master


Errors:
"fatal: remote origin already exists”
-> TL;DR you should just update the existing remote:

$ git remote set-url origin git@github.com:ppreyer/first_app.git



Switch branches
$ git checkout <branch>
By passing in the -b option when executing the checkout command, a new branch will be created and you will be switched over thereafter.
$ git checkout -b <branch>
