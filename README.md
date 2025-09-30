# Advanced-git-exercise-solutions

## Terminal code for the part 2

```bash

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)        
$ git pull
Already up to date.

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)        
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        rhh.js

nothing added to commit but untracked files present (use "git add" to track)

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)        
$ git commit -m'test commit after pc format
> '
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        rhh.js

nothing added to commit but untracked files present (use "git add" to track)

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)        
$ git commit -m'test commit after pc format
'
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        rhh.js

nothing added to commit but untracked files present (use "git add" to track)

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)        
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config set advice.addEmptyPathspec false"

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)        
$ git add .

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)        
$ git commit -m'test commit after pc format
'
[main caad08d] test commit after pc format
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 rhh.js

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)        
$ git push
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 253 bytes | 253.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions.git
   f94ed90..caad08d  main -> main

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)        
$ git add .

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)        
$ git commit -m'finish test commit'
[main a370161] finish test commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 rhh.js

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)        
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 236 bytes | 236.00 KiB/s, done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 236 bytes | 236.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions.git
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 236 bytes | 236.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 236 bytes | 236.00 KiB/s, done.
Writing objects: 100% (2/2), 236 bytes | 236.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions.git
   caad08d..a370161  main -> main
To https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions.git
   caad08d..a370161  main -> main
   caad08d..a370161  main -> main

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git checkout -b ft/newfeature
Switched to a new branch 'ft/newfeature'

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/newfeature)
$ git add feature.txt 

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/newfeature)
$ git commit -m'Implemented core functionality for new feature'
[ft/newfeature 6429d85] Implemented core functionality for new feature
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 feature.txt

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/newfeature)
$ git push origin main
fatal: unable to access 'https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions.git/': Recv failure: Connection was reset

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/newfeature)
$ git push origin main
Everything up-to-date

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/newfeature)
$ git push origin ft/newfeature
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 275 bytes | 275.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/newfeature' on GitHub by visiting:
remote:      https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions/pull/new/ft/newfeature
remote:
To https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions.git
 * [new branch]      ft/newfeature -> ft/newfeature

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/newfeature)
$ git checkout main
M       test5.md
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git add readme.txt 

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git commit -m'Updated project readme'
[main 2184bde] Updated project readme
 1 file changed, 1 insertion(+)
 create mode 100644 readme.txt

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 317 bytes | 317.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions.git
   a370161..2184bde  main -> main

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git merge ft/newfeature
Merge made by the 'ort' strategy.
 feature.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 feature.txt

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 289 bytes | 289.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions.git
   2184bde..170fb90  main -> main

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git branch -D ft/newfeature 
Deleted branch ft/newfeature (was 6429d85).

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git branch -r ft/newfeature
fatal: the -a, and -r, options to 'git branch' do not take a branch name.
Did you mean to use: -a|-r --list <pattern>?

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git branch -d ft/newfeature
error: branch 'ft/newfeature' not found

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git push origin --delete ft/newfeature
To https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions.git
 - [deleted]         ft/newfeature

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git push orgin main
fatal: 'orgin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test5.md

no changes added to commit (use "git add" and/or "git commit -a")

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git add .

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git commit -m'.'
[main f448cc8] .
 1 file changed, 1 insertion(+)

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 274 bytes | 274.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions.git
   170fb90..f448cc8  main -> main

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git log --oneline
f448cc8 (HEAD -> main, origin/main, origin/HEAD) .
170fb90 Merge branch 'ft/newfeature'
2184bde Updated project readme
6429d85 Implemented core functionality for new feature
a370161 finish test commit
caad08d test commit after pc format
f94ed90 Implemented test 5
032065c Merge branch 'main' of https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions
7d6a70f Create Thrid and Fourth file
d364654 Merge branch 'main' of https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions
b431249 Create Fourth file
db75364 Create Thrid File
c27dcb7 Merge branch 'main' of https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions
8886cd9 Create fourth file
e46c0d2 Create Third File
941f148 Merge branch 'main' of https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions
a7bea0a corrected by adding test4 file
48b8964 chore: Create intial and second  files
dfa6136 .
3ec44fd corrected by adding test4 file
65c9ebe chore: Create thrid and fouth file
f06651b chore: Create another file
2821813 chore: Create intial file
81d7154 Initial commit

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git checkout -b ft/new-branch-from-commit 2184bde
Switched to a new branch 'ft/new-branch-from-commit'

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/new-branch-from-commit)   
$ git log --oneline
2184bde (HEAD -> ft/new-branch-from-commit) Updated project readme
a370161 finish test commit
caad08d test commit after pc format
f94ed90 Implemented test 5
032065c Merge branch 'main' of https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions
7d6a70f Create Thrid and Fourth file

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/new-branch-from-commit)   
$ git add .

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/new-branch-from-commit)   
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git merge ft/new-branch-from-commit 
Already up to date.

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (main)
$ git checkout ft/new-branch-from-commit 
Switched to branch 'ft/new-branch-from-commit'

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/new-branch-from-commit)   
$ git rebase main
Successfully rebased and updated refs/heads/ft/new-branch-from-commit.

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/new-branch-from-commit)   
$ git branch -m ft/new-branch-from-commit ft/improved-branch-name 

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/improved-branch-name)     
$ git checkout <commit-hash>
bash: syntax error near unexpected token `newline'

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/improved-branch-name)     
$ git checkout <commit-hash>
bash: syntax error near unexpected token `newline'

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/improved-branch-name)     
$ git checkout <ft/improved-branch-name>
bash: syntax error near unexpected token `newline'

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/improved-branch-name)     
$ git add .

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/improved-branch-name)     
$ git commit -m'finishing the last challenge to exercises part 2'
On branch ft/improved-branch-name
nothing to commit, working tree clean

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/improved-branch-name)     
$ git status
On branch ft/improved-branch-name
nothing to commit, working tree clean

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/improved-branch-name)     
$ git push
fatal: The current branch ft/improved-branch-name has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/improved-branch-name

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/improved-branch-name)     
$     git push --set-upstream origin ft/improved-branch-name
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'ft/improved-branch-name' on GitHub by visiting:
remote:      https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions/pull/new/ft/improved-branch-name       
remote:
To https://github.com/emmanuel-niyonsaba/Advanced-git-exercise-solutions.git
 * [new branch]      ft/improved-branch-name -> ft/improved-branch-name
branch 'ft/improved-branch-name' set up to track 'origin/ft/improved-branch-name'.

Emmanuel Niyonsaba@DESKTOP-011VBOI MINGW64 /d/CodingRelated/Advanced-git-exercise-solutions (ft/improved-branch-name)     
$
```