1. `git init` -> Powers your folder to be managed by git. And initializes new empty folder.

2. `touch` -> command is used to create a new folder inside you repository.
3. `cat` -> command is used open your folder that you have created.
4. `ls -a` -> command is used to view your .git folder.
5. `rm -rf .git` -> command is used to remove your existing .git folder.

### running`git init` will reinitialize the git into the repository.

6. `git status` 
    -> Working Area : 
        -> Are not in staging area.
        -> Not managed by git.
        -> Any changes is also not managed by git.
        -> Always files you will see in the "Untracked Files" means all the files in the working area.
    -> Staging Area
        -> Area in which files will be going to be part of the next version.
    -> Repository Area
        -> Git manages all the files and know the version history.
        -> knows the previous registered version.

6. `git add README.txt` -> Moving file from working area to staging area.
7. `git rm --cached README.txt` -> Moving file from staging area to working area.

### In git version are managed by commits.
### One git commit is one version.
### Commit -> A commit is a snapshot of the project in the staged changes and create a version out of it.

8. `git commit` -> register staging changes to a commit.