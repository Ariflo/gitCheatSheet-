## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - Show changes between commits, commit and working tree, etc 


#### Repo History
`$ git log` - Shows commit logs (history of commits)

`$ git log --oneline --decorate --color --graph --all` - Print out the ref names of any commits that are shown line-by-line highlighting by color the directory and branch you are in and graphing all the ties to the parent (git log --help '/graph) 

`$ git log -p [filename]` -  Prints out the entire history of git commands run on the file 

#### Stage files to commit
`$ git add <filename>` - Stage all changes in `<filename>` for the next commit

`$ git add -A` - Stage all files

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - Record changes to the repository with the message, `<commit message>`

#### Branching
`$ git branch <branch name>` - create copy (branch) of file named <branch name>

`$ git branch` - Show which Branch your on

`$ git checkout <branch name>` - Move between Branches

#### Merging

`$ git merge <branch name>` - merge to <branch name> to master

#### Aliases

To create an aliase on git simply add it to your git config set up with:

`$ git config --global alias.'alias' 'actual command'` 