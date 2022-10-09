# Exercise 7 - More than one changed file

1. Ensure you have a clean working directory

        git status

2. Edit one of your `fruits.txt`, add a few items

        blueberry
        strawberry
        etc.

3. Edit `appliances.txt` and add a few items

        dishwasher
        dryer
        etc.

4. Look at git status, paste the output here

        git status

5. Can you commit both of the changed files in a single commit?
# Yes I can commit both of the changed files in a single commit
6. After you do so, check that you have a clean working directory by running `git status`, and pasting the output here
        PS C:\Users\mkhan\Desktop\cisw 17\msac-lab6> git status
        On branch master
        Your branch is ahead of 'origin/master' by 4 commits.
        (use "git push" to publish your local commits)

        Changes not staged for commit:
        (use "git add <file>..." to update what will be committed)
        (use "git restore <file>..." to discard changes in working directory)
                modified:   exercise01.md
                modified:   exercise02.md
                modified:   exercise03.md
                modified:   exercise04.md
                modified:   exercise05.md
                modified:   exercise06.md
                modified:   exercise07.md
                modified:   fruits.txt
                modified:   mainDirectory/equipment/appliances.txt
                no changes added to commit (use "git add" and/or "git commit -a")
7. Create a new file `equipment/furniture.txt`. Add content to both `vegetables.txt` and `furniture.txt`

8. How can you commit just one of the changed files?
 if you want to commit only parts of a file, you can use the interactive mode, which is turned on by the -p option. 
9. Check your `git status`

10. What does red text mean in the output of `git status`?
Red shows file is in git repository but latest changes has not been committed. If you will hit git commit command only red marked file will be select to commit.

11. What does green text mean in the output of `git status`?
Green shows file is in git repository and committed with latest changes

12. How can you make a single file show in both red and green in the output of `git status`?
git config --global color.ui auto
