#### 1. Change author name and email for last commit 
` git commit --amend --author="first last <email-address>"`
e.g : `git commit --amend --author="code eagle <codeagle-org@gmail.com`

#### 2. Add a git remote to local for push and fetch
`git remote add <branch-name> <remote-repo-link>`
e.g : `git remote add mainline https://github.com/codeagle-org/compiler.git`

#### 3. Check linked remote repo and operation
`git remote -v`

#### 4. Git pull remote to sync with local [first time] with unrelated history
` git pull  https://github.com/codeagle-org/compiler.git mainline --allow-unrelated-histories`

#### 5. Git push to remote 
`git push --set-upstream https://github.com/codeagle-org/compiler.git mainline`
