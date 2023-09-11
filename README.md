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

### Git handy commandsauthor
- `git init`      --> `initialize the git repo` 
- `ls -la`        --> `list all the hidden files for eg: .git`
- `git help`      --> `git manual`
- `git add .`     --> `adding files to staging area`
- `git commit -m "Initial commit"` --> `commiting the changes with expressive message`
- ****** `git commit -am "message "` --> `adds everything and commits`
- `git status`    --> `shows nice status`
- `git log`       --> `retrives last commits`
- `git checkout -b new-branch` --> `creating anew branch and making the head to point to created branch`
- `git branches`  --> `shows all the branches you have access to`
- `git push origin(your_github_repo) branch-name` --> `pushes the changes from your_local_repo to your_remote_github_repo`
- `git remote -v` --> `shows all the remote that your local is connected to`
- `git remote add upstream (name of main master repo) URL` --> `adding upstream_repo`
- `git fetch upstream` --> ``
- `git reset`
- `git reset -hard upstream/master`
- `git push origin master`
