Answer1. 
git version 2.28.0.windows.1



Answer2. 
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
user.email=as182219@ohio.edu
user.name=Aspelic



Answer 3. 
file:///C:/Program%20Files/Git/mingw64/share/doc/git-doc/git-add.html 
// It opens up a web browser page with information pertaining to the command on it.



Answer 4. 
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)



Answer 5.
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)



Answer 6.
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md



Answer 7.
[master (root-commit) af07662] Initial commit
 2 files changed, 42 insertions(+)
 create mode 100644 README.md
 create mode 100644 answers.md



Answer 8.
commit af076624301fdfc21cc06d7dd966a5d2c6f65f86 (HEAD -> master)
Author: Aspelic <as182219@ohio.edu>
Date:   Tue Sep 1 16:36:38 2020 -0400

    Initial commit



Answer 9.
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")



Answer 10.
//README.md looks the exact same



Answer 11.
To https://github.com/Aspelic/git-lab.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/Aspelic/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.



Answer 12.
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 759 bytes | 33.00 KiB/s, done.
From https://github.com/Aspelic/git-lab
   7305d68..e1bc114  master     -> origin/master
Updating 7305d68..e1bc114
Fast-forward
 README.md | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)
 //changes were reflected



Answer  13.


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----         9/1/2020   5:02 PM            302 .gitignore
-a----         9/1/2020   5:02 PM             11 README.md


