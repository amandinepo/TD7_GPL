# TD7_GPL


# Exercise 2 : Push files to common repository

## Q1 : Create a branch named after you
```
git checkout -b TD7
```

## Q2 Create a new text file named after you (with the content you want)
```
touch TD7.txt
echo "This is the tutorial 7"
```
## Q3 Commit this new file.
```
git add TD7.txt
git commit -m "Added new file with content"
```

## Q4  Push your branch to the remote repository
```
git push  https://github.com/amandinepo/TD7_GPL.git TD7
```

# Exercise 3: Merge simple changes

## Q1 Merge your branch into the ’master’ branch
```
git ckeckout main
git merge <branch name>
```
## Q2 Push your changes in the ’master’ branch to the remote repository



# Exercise 4 :  Resolve merge conflicts

## Q1 Switch back to your own branch (not including the latest changes from the master branch)
```
git checkout Rachel
git checkout TD7
```
## Q2
```
git add README.md
```
## Q3 Commit this change
```
git commit -m "Edited lines 2 to 6 of README.md file"
```
## Q4 . Pull latest status from the remote repository ’master’ branch into your local ’master’ branch.
```

```
## Q5 Merge your branch into the local ’master’ branch.
```

```
## Q6 If there are conflicts, we want the paragraph to appear in alphabetical order in the final README.md file.

```

```
## Q7 Push your changes in the ’master’ branch to the remote repository.

```

```
