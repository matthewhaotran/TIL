#Git

### Setting up a remote repository

- `git init`
- `git add .`
- `git commit -m "Initial Commit"`
- `Go to GitHub/Bitbucket and create a repository`
- `git remote add origin <origin_url>`
- `git push -u origin master`

### Updating a remote repository after making changes

- `git add .`
- `git commit -m "Helpful commit message"`
- `git push`

### To add color the Git CLI, use:

- `git config --global color.branch auto`
- `git config --global color.diff auto`
- `git config --global color.interactive auto`
- `git config --global color.status auto`

### Working on same project on two computer (solo)
- Set up remote repo on computer 1, make changes, commit, and push to online repo
- On computer, before working, pull down changes to get current state
`git pull origin master`
- Make changes, commit, and push to server
- Back on computer 1, pull changes and make edits.