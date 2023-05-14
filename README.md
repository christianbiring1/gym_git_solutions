# gym_git_solutions

## BUNDLE 1

### Exercise 1

```txt
git init

git branch -m main

git add . or git add <file_name>

git add remote git@github.com:christianbiring1/gym_git_solutions.git

git push -u origin main


git checkout -b dev
git checkout -b test

git checkout dev
git branch --delete test
```

### Exercise 2

```sh
git add home.html
git stash -- home.html

git add about.html
git stash -- about.html

git stash list // To see the list of my stashed files
git stash pop stash@{2} // to restore the second file(about.html) that I have stashed
git stash pop stash@{1}
```
