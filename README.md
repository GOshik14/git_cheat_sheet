# My cheat sheet for [git](https://github.com/git/git/blob/master/README.md)

---

## Initialize repository and the firest commit

Create new repository(repo) and change current directory(dir) to new:

$ mkdir new_repo && cd new_repo

U can check the status of directory with command git status:
$ git status

This is not a git repo, u can try to find .git repositiry with git meatdata:
$ ls -a
 or type command:
 
$git status

U can make a dir as a git dir with command:

$ git init

Then create file README.md:

$touch README.md

Add file to traced files for git:

$ git add README.md

And make u first commit with commit message "My first commit":

$ git commit -m"My first commit" 

---

## History of commits

U can get the commit's history with command:

$ git log

U can see the hesh (SHA/SHA-1 etc. algorithms names) of commits, author of each commit, date of creation the commit and commit message

There are short and long version for log command:

$ git log --one line

$ git log -v

There are four mode of files in git: untraced(not in git history, have no version), traced(after the first command git add), staged(after git add),

 modified = traced and with change then the last state files after git add.
 
 ---
