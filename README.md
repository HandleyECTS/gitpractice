# Git/Github Notes

Note: Use ctrl+shift+v to preview MD files in VS Code

## Basic Concepts

1. **Repository (repo)**
   A project folder that Git is tracking. Can **local** (on your computer) or **remote** (like GitHub)

2. **Version Control**
   A system that tracks changes to code over time, letting you revert to previous versions or collaborating with others.

3. **Commit**
   A snapshot of your changes. Includes a message describing what was changed.

4. **Working Directory**
   The current state of your files on disk.

5. **Staging Area**
   Where you rpepare changes before committing. You "stage" files that are ready to be committed.

---

6. `git init`
   Initializes a new Git repository in a folder.

7. `git status`
   Shows current state of the working directory and staging area.

8. `git add <file>`
   Stages changes in a file for the next commit. (Note: You can `git add *` to stage all files in the working directory, while `git add .` does the whole repository)

9. `git commit -m "message"`
   Saves the staged changes with a commit message.

10. ** Add a remote location for a repo**
    `git remote add origin <link to repo>`

11. `git push`
    Sends local commits to the remote repository

12. `git pull`
    Fetches **and merges** changes from the remote repository into your local one.

13. `git fetch`
    Downloads changes from the remote, but doesn't merge them automatically.

14. `git merge`
    Merges changes from one branch into another.

15. `git branch <branch_name>`
    Create a new branch

16. `git checkout <branch_name>`
    Switch to a different branch (edits/commits are on this now.)
