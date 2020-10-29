1. Create new repo on github  
1. Open the terminal.  
1. Change the current working directory to your local project.  
1.Initialize the local directory as a git repository.  
`git init`  
1. Add the files in your new local repository. This stages them for the first commit.  
`git add .`  
1. Commit the files that you've staged in your local repository.  
`git commit -m "commit message"`

1. At the top of your gitHub repository's quick setup page, click  to copy the remote repository URL.  
1. In Terminal, on the next command, replace <remote_repository_URL> with the remote repository URL where your local repository will be pushed.  

1. Set the new remote repo  
`git remote add origin <remote_repository_URL>`  
1. Verifies the new remote URL  
`git remote -v`
1. Push the changes in your local repository to gitHub.  
`git push origin master`
