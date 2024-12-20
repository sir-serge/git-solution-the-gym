#   git exercises 
  bundle 1
exericses1 
```
gymkubaho@Kubahos-iMac-2 git exercises % git init
Initialized empty Git repository in /Users/gymkubaho/Desktop/git exercises/.git/
gymkubaho@Kubahos-iMac-2 git exercises % git status
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)
gymkubaho@Kubahos-iMac-2 git exercises % git git branch -M "master"
git: 'git' is not a git command. See 'git --help'.

The most similar command is
        init
gymkubaho@Kubahos-iMac-2 git exercises % git branch -M "master" 
gymkubaho@Kubahos-iMac-2 git exercises % git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme.md

nothing added to commit but untracked files present (use "git add" to track)
gymkubaho@Kubahos-iMac-2 git exercises % git add readme.md
gymkubaho@Kubahos-iMac-2 git exercises % git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   readme.md

gymkubaho@Kubahos-iMac-2 git exercises % git commit -m "creat readme "
[master (root-commit) b0bbccd] creat readme
 1 file changed, 2 insertions(+)
 create mode 100644 readme.md
gymkubaho@Kubahos-iMac-2 git exercises % git remote add origin https://github.com/sir-serge/git-solution-the-gym.git
gymkubaho@Kubahos-iMac-2 git exercises % git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 241 bytes | 241.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/sir-serge/git-solution-the-gym.git
 * [new branch]      master -> master
gymkubaho@Kubahos-iMac-2 git exercises % git checkout -b "dev"
Switched to a new branch 'dev'
gymkubaho@Kubahos-iMac-2 git exercises % git status
On branch dev
gymkubaho@Kubahos-iMac-2 git exercises %  git checkout -b test dev
Switched to a new branch 'test'
gymkubaho@Kubahos-iMac-2 git exercises % git status
On branch test
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

no changes added to commit (use "git add" and/or "git commit -a")
gymkubaho@Kubahos-iMac-2 git exercises % git checkout dev
M       readme.md
Switched to branch 'dev'
gymkubaho@Kubahos-iMac-2 git exercises % git branch -d test
Deleted branch test (was b0bbccd).
gymkubaho@Kubahos-iMac-2 git exercises %  
```