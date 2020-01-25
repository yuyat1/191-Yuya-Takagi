I did all the exercise on git-katas repo by accident, log will not be available on this repo.

2:
Yuya@DESKTOP-CPMIB2 MINGW64 ~/git-katas/basic-commits/exercise (master)
$ git log
fatal: your current branch 'master' does not have any commits yet

4:
Yuya@DESKTOP-CPFMIB2 MINGW64 ~/git-katas/basic-commits/exercise (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

6:
Yuya@DESKTOP-CPFMIB2 MINGW64 ~/git-katas/basic-commits/exercise (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

8/10:I edited README between step 6-8 so shows README as modified
Yuya@DESKTOP-CPFMIB2 MINGW64 ~/git-katas/basic-commits/exercise (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

12:
Yuya@DESKTOP-CPFMIB2 MINGW64 ~/git-katas/basic-commits/exercise (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

15:
Yuya@DESKTOP-CPFMIB2 MINGW64 ~/git-katas/basic-commits/exercise (master)
$ git status
On branch master
nothing to commit, working tree clean

Yuya@DESKTOP-CPFMIB2 MINGW64 ~/git-katas/basic-commits/exercise (master)
$ git log
commit 18cdc2e37da506bd9bac59c5418e78355c2f58ba (HEAD -> master)
Author: yuyat1 <yuyat@uci.edu>
Date:   Fri Jan 24 20:45:48 2020 -0800

    Modified README

commit 675c51260117eb9b392c73bd018ed1427f3f1aa6
Author: yuyat1 <yuyat@uci.edu>
Date:   Fri Jan 24 20:39:57 2020 -0800

    Adding README file

