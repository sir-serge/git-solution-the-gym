#   git exercises 
  bundle 1
exericses1 
```bash
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

bundle 1 
exercises 2
```bash
Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git push --set-upstream origin dev
error: src refspec dev does not match any
error: failed to push some refs to 'origin'

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git remote add origin https://github.com/sir-serge/git-solution-the-gym.git

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git push --set-upstream origin dev
error: src refspec dev does not match any
error: failed to push some refs to 'https://github.com/sir-serge/git-solution-the-gym.git'

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git checkout dev
error: pathspec 'dev' did not match any file(s) known to git

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git push origin dev
error: src refspec dev does not match any
error: failed to push some refs to 'https://github.com/sir-serge/git-solution-the-gym.git'

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git remote -v
origin  https://github.com/sir-serge/git-solution-the-gym.git (fetch)
origin  https://github.com/sir-serge/git-solution-the-gym.git (push)
orrigin https://github.com/sir-serge/git-solution-the-gym.git (fetch)
orrigin https://github.com/sir-serge/git-solution-the-gym.git (push)

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git push origin dev
error: src refspec dev does not match any
error: failed to push some refs to 'https://github.com/sir-serge/git-solution-the-gym.git'

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git push origin dev
error: src refspec dev does not match any
error: failed to push some refs to 'https://github.com/sir-serge/git-solution-the-gym.git'

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git push origin main
Everything up-to-date

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git status
On branch main
Your branch is up to date with 'orrigin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme.md

nothing added to commit but untracked files present (use "git add" to track)

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git pull
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 9 (delta 1), reused 9 (delta 1), pack-reused 0 (from 0)
Unpacking objects: 100% (9/9), 1.44 KiB | 47.00 KiB/s, done.
From https://github.com/sir-serge/git-solution-the-gym
 * [new branch]      dev        -> orrigin/dev
 * [new branch]      master     -> orrigin/master
Already up to date.

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git push origin dev
error: src refspec dev does not match any
error: failed to push some refs to 'https://github.com/sir-serge/git-solution-the-gym.git'

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git a
add        am         apply      archive    askpass    askyesno   

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git add home.html 

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git status
On branch main
Your branch is up to date with 'orrigin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme.md

nothing added to commit but untracked files present (use "git add" to track)

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git push origin dev
error: src refspec dev does not match any
error: The following untracked working tree files would be overwritten by checkout:
        readme.md
Please move or remove them before you switch branches.
Aborting

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'orrigin/main'.

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (main)
$ git checkout dev
branch 'dev' set up to track 'orrigin/dev'.
Switched to a new branch 'dev'

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git status
On branch dev
Your branch is up to date with 'orrigin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        home.html

nothing added to commit but untracked files present (use "git add" to track)

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git add home.html 

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git status
On branch dev
Your branch is up to date with 'orrigin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   home.html


Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git commit -m 'creat home.html'
[dev 442e5e3] creat home.html
 1 file changed, 11 insertions(+)
 create mode 100644 home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git push origin dev
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 440 bytes | 440.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/sir-serge/git-solution-the-gym.git
   f622725..442e5e3  dev -> dev

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git checkout -b test
Switched to a new branch 'test'

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (test)
$ git checkout dev
Switched to branch 'dev'
Your branch is ahead of 'orrigin/dev' by 1 commit.
  (use "git push" to publish your local commits)

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git branch -d test
Deleted branch test (was 442e5e3).

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash list

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git add home.html 

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash  
No local changes to save

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git pull
From https://github.com/sir-serge/git-solution-the-gym
   f622725..442e5e3  dev        -> orrigin/dev
Already up to date.

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git status
On branch dev
Your branch is up to date with 'orrigin/dev'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git status
On branch dev
Your branch is up to date with 'orrigin/dev'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash
Saved working directory and index state WIP on dev: 442e5e3 creat home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git status
On branch dev

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git status
On branch dev
Your branch is up to date with 'orrigin/dev'.  

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html


Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash
Saved working directory and index state WIP on dev: 442e5e3 creat home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git status
On branch dev
Your branch is up to date with 'orrigin/dev'.  
sent (use "git add" to track)

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git add team.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash
Saved working directory and index state WIP on dev: 442e5e3 creat home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash list
stash@{0}: WIP on dev: 442e5e3 creat home.html
stash@{1}: WIP on dev: 442e5e3 creat home.html
stash@{2}: WIP on dev: 442e5e3 creat home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash pop
On branch dev
Your branch is up to date with 'orrigin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (96ca3f03d5b07916b54f85dc71bb5736a23c8864)

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash list
stash@{0}: WIP on dev: 442e5e3 creat home.html
stash@{1}: WIP on dev: 442e5e3 creat home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash pop
On branch dev
Your branch is up to date with 'orrigin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   team.html

Dropped refs/stash@{0} (4b8fb346788134de188a265155be0ad77ef4d7c4)

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash list
stash@{0}: WIP on dev: 442e5e3 creat home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git add team.html 

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git add about.html 

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash list
stash@{0}: WIP on dev: 442e5e3 creat home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash 
Saved working directory and index state WIP on dev: 442e5e3 creat home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash list
stash@{0}: WIP on dev: 442e5e3 creat home.html
stash@{1}: WIP on dev: 442e5e3 creat home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash pop
On branch dev
Your branch is up to date with 'orrigin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   team.html

Dropped refs/stash@{0} (c1c68b36f583af8adfc745e9db58dd8fdb5867ab)

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash push about.html
Saved working directory and index state WIP on dev: 442e5e3 creat home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash push team.html
Saved working directory and index state WIP on dev: 442e5e3 creat home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash list
stash@{0}: WIP on dev: 442e5e3 creat home.html
stash@{1}: WIP on dev: 442e5e3 creat home.html
stash@{2}: WIP on dev: 442e5e3 creat home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash pop stash@{1}
On branch dev
Your branch is up to date with 'orrigin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   team.html

Dropped stash@{1} (50ffe4ed41595cb63a267229ff529e2a94d8c92c)

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash list
stash@{0}: WIP on dev: 442e5e3 creat home.html
stash@{1}: WIP on dev: 442e5e3 creat home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash pop stash@{1}
On branch dev
Your branch is up to date with 'orrigin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   team.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

Dropped stash@{1} (2f5f1d220869c68d7f5eb5a18f42e12e75130027)

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git status
On branch dev
Your branch is up to date with 'orrigin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   team.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html


Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git commit -m 'create and setup the home,about and team page'
[dev bc921b3] create and setup the home,about and team page
 2 files changed, 22 insertions(+)
 create mode 100644 about.html
 create mode 100644 team.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 556 bytes | 556.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/sir-serge/git-solution-the-gym.git
   442e5e3..bc921b3  dev -> dev

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash list
stash@{0}: WIP on dev: 442e5e3 creat home.html

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git stash pop stash@{0}
On branch dev
Your branch is up to date with 'orrigin/dev'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped stash@{0} (d5ffed5691a48aee4de1b5bd1fbf468b17ec01df)

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git rest --hard
git: 'rest' is not a git command. See 'git --help'.

The most similar commands are
        restore
        reset

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$ git reset --hard
HEAD is now at bc921b3 create and setup the home,about and team page

Serge@DESKTOP-N7T6QJS MINGW64 ~/Desktop/git-trello (dev)
$
```
```bash 
gymiriba@Iribas-iMac git-solution-the-gym % git checkout -b ft/bundle-2

Switched to a new branch 'ft/bundle-2'
gymiriba@Iribas-iMac git-solution-the-gym % git add services.html 
gymiriba@Iribas-iMac git-solution-the-gym % git commit -m "Add services page"

[ft/bundle-2 099bfb5] Add services page
 Committer: Gym Iriba <gymiriba@Iribas-iMac.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 services.html
gymiriba@Iribas-iMac git-solution-the-gym % git push -u origin ft/bundle-2

Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 284 bytes | 284.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/sir-serge/git-solution-the-gym/pull/new/ft/bundle-2
remote: 
To https://github.com/sir-serge/git-solution-the-gym.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.
gymiriba@Iribas-iMac git-solution-the-gym % git checkout main

error: Your local changes to the following files would be overwritten by checkout:
        readme.md
Please commit your changes or stash them before you switch branches.
Aborting
gymiriba@Iribas-iMac git-solution-the-gym % git stash save "Changes to readme.md"

Saved working directory and index state On ft/bundle-2: Changes to readme.md
gymiriba@Iribas-iMac git-solution-the-gym % git checkout main

branch 'main' set up to track 'origin/main'.
Switched to a new branch 'main'
gymiriba@Iribas-iMac git-solution-the-gym % git merge ft/bundle-2
fatal: refusing to merge unrelated histories
gymiriba@Iribas-iMac git-solution-the-gym % git merge --allow-unrelated-histories ft/bundle-2
hint: Waiting for your editor to close the file... 
 *  History restored 

gymiriba@Iribas-iMac git-solution-the-gym % git checkout dev                                 
A       services.html
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.
gymiriba@Iribas-iMac git-solution-the-gym % git merge ft/bundle-2                            
Updating c87bea5..099bfb5
Fast-forward
 services.html | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 services.html
gymiriba@Iribas-iMac git-solution-the-gym % git push origin main

Everything up-to-date
gymiriba@Iribas-iMac git-solution-the-gym % git status
On branch dev
Your branch is ahead of 'origin/dev' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
gymiriba@Iribas-iMac git-solution-the-gym % git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/sir-serge/git-solution-the-gym.git 
   c87bea5..099bfb5  dev -> dev
gymiriba@Iribas-iMac git-solution-the-gym % 
```


###bundle 4 exercise 1
```bash
PS C:\Users\Serge\Desktop\git-solution-the-gym> git status 
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
PS C:\Users\Serge\Desktop\git-solution-the-gym> git chckout main
git: 'chckout' is not a git command. See 'git --help'.

The most similar command is
        checkout
PS C:\Users\Serge\Desktop\git-solution-the-gym> git checkout main
branch 'main' set up to track 'origin/main'.
Switched to a new branch 'main'
PS C:\Users\git remote add git-copy https://github.com/sir-serge/git-exercises-bundle4.git
PS C:\Users\Serge\Desktop\git-solution-the-gym>


                                                    
PS C:\Users\Serge\Desktop\git-solution-the-gym> git add .\home.html
PS C:\Users\Serge\Desktop\git-solution-the-gym> git status 
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   home.html

PS C:\Users\Serge\Desktop\git-solution-the-gym> git add .
PS C:\Users\Serge\Desktop\git-solution-the-gym> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   home.html

PS C:\Users\Serge\Desktop\git-solution-the-gym> git commit -m"create git-copy"
[main aac2fd9] create git-copy
 1 file changed, 1 insertion(+)
PS C:\Users\Serge\Desktop\git-solution-the-gym> git push origin
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 318 bytes | 318.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.        
To https://github.com/sir-serge/git-solution-the-gym.git
   87ba4df..aac2fd9  main -> main
PS C:\Users\Serge\Desktop\git-solution-the-gym> git push git-copy
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 642 bytes | 642.00 KiB/s, done.
Total 6 (delta 1), reused 2 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/sir-serge/git-exercises-bundle4.git
 * [new branch]      main -> main
PS C:\Users\Serge\Desktop\git-solution-the-gym>
```
###bundle 4 exercise 2
```bash
PS C:\Users\Serge\Desktop\git-solution-the-gym> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\Serge\Desktop\git-solution-the-gym> git checkout -b ft/squashing

Switched to a new branch 'ft/squashing'
PS C:\Users\Serge\Desktop\git-solution-the-gym> git merge -- squash ft/footer
merge: squash - not something we can merge
PS C:\Users\Serge\Desktop\git-solution-the-gym> git merge --squash ft/footer
 
Updating aac2fd9..803b5e5
Fast-forward
Squash commit -- not updating HEAD
 home.html | 3 +++
 1 file changed, 3 insertions(+)
PS C:\Users\Serge\Desktop\git-solution-the-gym> git commit -m"footer changes squash"
[ft/squashing 2089907] footer changes squash
 1 file changed, 3 insertions(+)
Date:   Tue Mar 4 23:22:32 2025 +0200

    footer changes squash

commit aac2fd9034e25e17d63175ac178528fb3890ec38 (origin/main, git-copy/main, main)
Author: sir-serge <irkzsrg@gmail.com>
Date:   Tue Mar 4 22:09:47 2025 +0200

    create git-copy

commit 87ba4dfb14a0562aa513a12118ffa0a384a1f0ca
Author: sir-serge <irkzsrg@gmail.com>
Date:   Thu Jan 9 19:16:26 2025 +0200

    create home.html
PS C:\Users\Serge\Desktop\git-solution-the-gym> git push origin ft/squashing
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 338 bytes | 338.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/sir-serge/git-solution-the-gym/pull/new/ft/squashing
remote:
To https://github.com/sir-serge/git-solution-the-gym.git
 * [new branch]      ft/squashing -> ft/squashing
```
