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

-------------------------------------------------------
Adding some new lines. 
Delete it after the work is done.
-------------------------------------------------------

9. `git restore README.txt` -> File in the staging area and remove all the modified content in the file.
                            -> Instead of deleting all the changed in the file line by line, restore the last 
                            clean version of the file.

10. `git restore --staged README.txt` -> help you to move back your file changes from staging area to working area.
                                      -> Then you can restore the file and get the clean a last version of it.

-------------------------------------------------------
Again doing this to lean the staging and unstaging of the git.

Adding some new lines. 
Delete it after the work is done.
-------------------------------------------------------


11. `git diff commitID2 commitID1` -> This provide a difference between both the commited files.

12. `git commit -m "this is my final"` -> To avoid vim/nano editor and directly commit the message with the git command only.

13. `git remote` -> To list down all the remote connection name.

14. Remote Connection -> It help you to link 2 git repos for uploading and downloading changes from each other.

15. `git remote add <remote name> <remote link>`

16. `git push <remote name> <branch name>`

17. `git remote rm <name of the remote>`

18. `git remote rename <oldName> <newName>` -> To rename the file name.

19. `git add .` -> To add multiple files from working to the staging area.

Changes made by some other user.

20. `git pull origin master` -> Help you to pull all the changes made by your team mate to the same repo.

### Best practice to use-
Make changes
Add file to staging area
Commit those changes
First pull to avoid conflict.
Then push the changes to the repo.

### stuck with the merge conflict!!

merge conflict occured. Please resolve!

New merge conflict by user 1.

New merge Conflict by user 2

21. `git fetch origin master` -> To fetch the latest changes

22. `git merge origin/master` -> To merge the changes from the remote 'master' branch.

23.  `git remote -v` -> To verify the remote

24. `git branch` -> To check all the branch repo has.

25. `git branch -M main` -> To change the branch name or we can say to rename the branch.

26. `git checkout <branch name>` -> To navigate from one branch to another branch.

27. `git checkout -b <new Branch Name>` (git checkout -b starter) -> This command is used to create 
                                                                     a new branch.

28. `git branch -d <branch name>` -> To delete the branch.


---------------------------UnDoing Commit Changes-------------------------------

29. `git reset HEAD~1` -> Undoing for one commit

30. `git reset <commit hash>` -> For many commit

31. `git reset --hard <commit hast>` -> For many commit


-------------------Concluded--------------------------------
