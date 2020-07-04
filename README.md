# Useful commands

## Git

| Command | Description | 
| ------- | ----------- |
| `git clone repo_url` | clones an existing repo |
| `git init` | initializes new git repo in current folder |
| `git status` | shows info about the repo |
| `git branch` | shows a list of all the local branches |
| `git branch branch_name`  | creates a new `branch_name` branch |
| `git checkout branch_name` | switch to selected `branch_name` |
| `git checkout -b branch_name` | creates a branch and switches to it |
| `git remote`| shows a list of remote servers |
| `git remote show server_alias` | shows the detailed info about a server |
| `git remote add server_alias repo_url` | adds a new alias for a server with given `repo_url` |
| `git remote remove server_alias` | disconnects from a server |
| `git add ./path/to/files` | prepares changes for saving |
| `git commit -m 'a commit message'` | saves the changes |
| `git commit -am 'a commit message'` | add all changed files and saves the changes |
| `git push server_alias branch_name` | sends the `branch_name` to `server_alias` |
| `git fetch server_alias branch_name` | downloads the changes without merging them to local branch |
| `git pull server_alias branch_name` | downloads and merges changes |
| `git log` | shows the commits history |
| `git rm --cached` | exclude file from the tracking area |
  
## NPM

| Command | Description | 
| ------- | ----------- |
| `npm init` | creates `package.json` |
| `npm install`, `npm i` | installs all the `dependencies` and `devDependencies` |
| `npm run ...` runs a command from `scripts` section of `package.json` |
| `npm run start`, `npm start` | usually the main command to run the project |
| `npm run test`, `npm test` | a command running tests if present |
| `npm run lint` | checks the code style |
| `npm run test:only` | runs tests |
| `npm run test` | runs linter and tests |
| `npm run deploy` | deploys the website to the hosting (Github) |
