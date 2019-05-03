## Learning Git

This repository is meant to help me learn about *forking* and *updating* repositories on GitHub.

[reference article](https://help.github.com/en/articles/fork-a-repo "reference article")

### Git setup for repository

#### For global Git settings

`git config --global user.name "<USER"`

`git config --global user.email <EMAIL>`

#### For local repository Git settings

`git config user.name "<USER"`

`git config user.email <EMAIL>`

### After working on code
`git add .`

`git commit -m "Changed README.md"`

`git push origin master:master`

#### Sync with remote repository
`git pull`

It will only sync if the changes on the remote were committed (obviously).
