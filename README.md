# git-tutorial

## Important Git Commands

1. `git where` or `git which`
2. `git --version`
3. mac configuration to - git autocompletion - `https://github.com/git/git/tree/master/contrib/completion`

   
   ```
   cd
   curl -OL https://github.com/git/git/blob/master/contrib/completion/git-completion.bash
   mv ~/git-completion.bash .git-completion.bash
   ```
- Create bash_profile if not exist

  ```
    nano .bash_profile
    if [ -f ~/.git-completion.bash ]; then
      source  ~/.git-completion.bash
    fi
  ```
- OR install it using homebrew
-   `brew install git && brew install bash-completion`
-   `Add bash completion to your ~/.bash_profile`

4. initialize git `git init` -> create an empty repo and initialize the git
- `ls -la`

-- `git help`
-- `git add .`
-- `git commit -m "Initial commit"`
-- `git status`
-- `git log` -> shows how many commits are made
-- `git checkout -b new-branch`
--  `git branches` --> shows all the branches you have access to
-- `git push origin (your github) branch-name` --> push the changes from local to your remote github
-- `git remote -v` --> shows all the remote that your local is connected to
-- `git remote add upstream (name of main master repo) URL`
-- `git fetch upstream`
-- `git reset`
-- `git reset -hard upstream/master`
-- `git push origin master`
