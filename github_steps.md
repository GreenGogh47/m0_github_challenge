# GitHub Steps

Describe in your own words how to establish a connection between a local repository and a remote repository on GitHub.

The following steps are assuming the repo hasn't been cloned from GitHub

# Local
1. Creat a local directory that you want to sync to GitHub in terminal with `mkdir <directory name>`
1. Go into that new directory with `cd <directory name>`
1. Initialize the connection with `git init`

# GitHub
1. Create a repo on GitHub
    - They don't have to have the same name, but golly gee will it make it easier.
    - Make sure that SSH is checked, not HTML
1. Copy the SSH code

# Terminal Again
1. Set the local repo to the GitHub address by running this in terminal `git remote add origin <copied SSH code>`
1. Name the main branch as main with this code `git branch -M main`
1. Send the current version to the origin/main branch, and set it as the default with `git push -u origin main`

You can now use git push to automatically send all commited changes to your GitHub repo! ^_^