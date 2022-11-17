# Git

## Courses

## Books

## Tricks

- **Pull from remote overwriting local changes:**
    - `git stash` (revert and stash changes locally)
    - `git pull` (pull from remote normally)
    - tip: to retrieve changes, do `git stash apply`

- **Delete only untracked files from working tree:**
    - `git clean -f -d `

- **Unstage files from index (but keep the files locally):**
    - `git rm --cached`

- **Undo a merge:**
    - `git checkout branch-name`
    - `git log --oneline`
    - `git revert -m commit-id` 

- **Remove a file from remote:**
    - `git rm filename (remove file from git)`
    - `git commit -m "commit message"`
    - `git push`

- **Undo last n commits:**
    - `git reset --soft HEAD^n (where n is the number of last commits you want to undo)` 

- **See diff between branches:**
    - `git diff branch_1..branch_2` 

- **Remove a tag from branch:**
    - `git push origin :refs/tags/tagname`
    - `git tag -d` 

- **Rename a branch locally & remote**
    - `git checkout old-branch`
    - `git branch -m new-name`
    - `git push origin :old-name new-name`

- **Move existing, uncommitted work to a new branch**
    - `git switch -c <new-branch> (git 2.3 onwards)` 





