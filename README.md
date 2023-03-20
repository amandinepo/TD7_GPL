# TD7_GPL


# Exercise 2 : Push files to common repository

## Q1. Create a branch named after you
```
git branch amandine
```

## Q2. Create a new text file named after you (with the content you want)
```
> Rachel.txt
echo "This is the tutorial 7"
```

## Q3. Commit this new file.
```
git add Rachel.txt
git commit -m "Added new file with content"
```

## Q4. Push your branch to the remote repository
```
git push  https://github.com/amandinepo/TD7_GPL.git Rachel
```

# Exercise 3: Merge simple changes

## Q1. Merge your branch into the ’master’ branch
```
git ckeckout master
git merge Rachel
```

## Q2. Push your changes in the ’master’ branch to the remote repository
```
git push https://github.com/amandinepo/TD7_GPL.git main
```

# Exercise 4 :  Resolve merge conflicts

## Q1. Switch back to your own branch (not including the latest changes from the master branch)
```
git checkout Rachel
```

## Q2. Edit the lines 2 to 6 of the README.md file
```
vim README.md
```

## Q3. Commit this change
```
git add README.md
git commit -m "Edited lines 2 to 6 of README.md file"
```

## Q4. Pull latest status from the remote repository ’master’ branch into your local ’master’ branch.
```
git checkout main
git pull https://github.com/amandinepo/TD7_GPL.git main
```

## Q5. Merge your branch into the local ’master’ branch.
```
git merge TD7
```

## Q6. If there are conflicts, we want the paragraph to appear in alphabetical order in the final README.md file.
```
git add README.md
git commit -m "Merged TD7 branch into master branch"
```

## Q7. Push your changes in the ’master’ branch to the remote repository.
```
git push https://github.com/amandinepo/TD7_GPL.git master
```

# Exercise 5: Take latest changes from master in local branch

## Q1. Pull the latest changes in the ’master’ branch, check the README.md is up-to-date (contains all the paragraphs and the new line).
```
git checkout main
git pull https://github.com/amandinepo/TD7_GPL.git main
```

## Q2. Switch back to your own branch (not including the latest changes from the master branch).
```
git checkout lucie
```

## Q3. Merge the changes from ’master’ to your own branch.
```
git merge main
```

## Q4. Commit this change.
```
git add README.md
git commit -m "Merged changes from master branch into lucie branch"
```

# Exercice 6

## Q1. Delete your branch on local repository.
```
git branch -d amandine
```

## Q2. Delete your branch on local repository.
```
git push origin -d Rachel
```

# Exercice 7

## Q1. Pull the latest changes in the ’master’ branch.
```

```

## Q2. Create a new local branch named after you and switch to it.
```
git branch amandine
git checkout amandine
```
## Q3. Then with a separate commit for each change.
## a. Clear the whole file, removing all text.
```

```
## b. Add a title line "Git interactive rebase".
```

```
## c. Copy the first paragraph from https ://git-scm.com/book/en/v2/Git-Tools-Rewriting-History.
```

```
## d. Add the second paragraph from the same page.
```

```
