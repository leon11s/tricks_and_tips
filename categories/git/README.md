# Git

## Courses

## Books

## Videos
- [Git Explained in 100 Seconds](https://www.youtube.com/watch?v=hwP7WQkmECE): A quick overview about Git, explaining core principles.
- [Git vs. GitHub: What's the difference?](https://www.youtube.com/watch?v=wpISo9TNjfU): A tutorial focusing on explaining the differences between Git and GitHub.
- [Git and GitHub for Beginners - Crash Course](https://www.youtube.com/watch?v=RGOj5yH7evk): Learn about how to work with Git, use commands like add, commit, push, pull, create branches, fork projects, etc.
- [Git for Professionals Tutorial - Tools & Concepts for Mastering Version Control with Git](https://www.youtube.com/watch?v=Uszj_k0DGsg): You'll go beyond the basic commands and look at some of the more advanced concepts and tools to make you more productive and confident with Git.

## Repositories
- [GitHub Cheat Sheet](https://github.com/tiimgreen/github-cheat-sheet#ignore-whitespace): A collection of cool hidden and not so hidden features of Git and GitHub.


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





