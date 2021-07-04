# 2021-07-02-git_collab-dan

- `git clone <URL>`: clones/downloads the repo to your computer

- `git branch <NAME>`: creates a branch called <NAME> where you are (HEAD)
- `git switch <NAME>`: move the the branch <NAME>
    - `git checkout <NAME>`: the "older" way to switch branches
- `git stash`: will create a temp commit
    - `git stash list`: show you the temp commits that are stashed
    - `git stash apply`: apply the last stash (pop)
    - `git stash clear`: remove all your stashes
- `git switch -c <NAME>`: create and move the the branch <NAME>
- `git checkout -b <NAME>`: also create and move to branch <NAME>
- `git rebase <BRANCH>`: change the history and update current branch with <BRANCH>

- reference
    -  https://swcarpentry.github.io/git-novice/reference.html
    -  https://chendaniely.github.io/training_ds_r/help-faq.html