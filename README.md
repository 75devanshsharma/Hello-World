 create mode 100644 pom.xml
 create mode 100644 src/main/java/model/customer.java
 create mode 100644 src/main/java/util/ConnectionUtil.java
 create mode 100644 src/test/java/util/TestConnectionUtil.java

E:\devansh5\bookapp-core>git remote add origin https://github.com/75devanshsharm
a/bookapp1.git

E:\devansh5\bookapp-core>git push -u origin master
Username for 'https://github.com': 75devanshsharma@gmail.com
Password for 'https://75devanshsharma@gmail.com@github.com':
Counting objects: 14, done.
Delta compression using up to 24 threads.
Compressing objects: 100% (8/8), done.
Writing objects: 100% (14/14), 1.47 KiB | 0 bytes/s, done.
Total 14 (delta 0), reused 0 (delta 0)
To https://github.com/75devanshsharma/bookapp1.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

E:\devansh5\bookapp-core>git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   src/main/java/model/customer.java

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .classpath
        .project
        .settings/
        src/test/java/model/
        target/

no changes added to commit (use "git add" and/or "git commit -a")

E:\devansh5\bookapp-core>git add src

E:\devansh5\bookapp-core>git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   src/main/java/model/customer.java
        new file:   src/test/java/model/TestModel.java

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .classpath
        .project
        .settings/
        target/


E:\devansh5\bookapp-core>git commit -m "Added model"
[master 31e7def] Added model
 Committer: user-27 <user-27>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 62 insertions(+), 1 deletion(-)
 create mode 100644 src/test/java/model/TestModel.java

E:\devansh5\bookapp-core>git push
Username for 'https://github.com': 75devanshsharma@gmail.com
Password for 'https://75devanshsharma@gmail.com@github.com':
Counting objects: 11, done.
Delta compression using up to 24 threads.
Compressing objects: 100% (7/7), done.
Writing objects: 100% (11/11), 1.12 KiB | 0 bytes/s, done.
Total 11 (delta 0), reused 0 (delta 0)
To https://github.com/75devanshsharma/bookapp1.git
   e9af3b2..31e7def  master -> master

E:\devansh5\bookapp-core>cd
E:\devansh5\bookapp-core

E:\devansh5\bookapp-core>cd ..

E:\devansh5>dir
 Volume in drive E is New Volume
 Volume Serial Number is DCEB-7685

 Directory of E:\devansh5

10-03-2017  16:13    <DIR>          .
10-03-2017  16:13    <DIR>          ..
10-03-2017  13:56    <DIR>          .metadata
10-03-2017  16:14    <DIR>          .recommenders
10-03-2017  16:22    <DIR>          bookapp-core
10-03-2017  13:56    <DIR>          RemoteSystemsTempFiles
               0 File(s)              0 bytes
               6 Dir(s)  326,512,173,056 bytes free

E:\devansh5>cd..

E:\>cd..

E:\>E:\devansh1\dive7
'E:\devansh1\dive7' is not recognized as an internal or external command,
operable program or batch file.

E:\>cd devansh1\dive7

E:\devansh1\dive7>git init
Initialized empty Git repository in E:/devansh1/dive7/.git/

E:\devansh1\dive7>git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .classpath
        .project
        .settings/
        bin/
        src/

nothing added to commit but untracked files present (use "git add" to track)

E:\devansh1\dive7>gid add src
'gid' is not recognized as an internal or external command,
operable program or batch file.

E:\devansh1\dive7>git add src

E:\devansh1\dive7>git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   src/com/devansh/Book.java
        new file:   src/com/devansh/SearchApp.java
        new file:   src/com/devansh/book.sql

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .classpath
        .project
        .settings/
        bin/


E:\devansh1\dive7>git commit -m "dive 7"
[master (root-commit) 668132e] dive 7
 Committer: user-27 <user-27>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 3 files changed, 192 insertions(+)
 create mode 100644 src/com/devansh/Book.java
 create mode 100644 src/com/devansh/SearchApp.java
 create mode 100644 src/com/devansh/book.sql

E:\devansh1\dive7>git push -u origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

E:\devansh1\dive7>git remote add origin https://github.com/75devanshsharma/pubhu
b-100.git

E:\devansh1\dive7>git push -u origin master
Username for 'https://github.com': 75devanshsharma@gmail.com
Password for 'https://75devanshsharma@gmail.com@github.com':
Counting objects: 8, done.
Delta compression using up to 24 threads.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (8/8), 2.29 KiB | 0 bytes/s, done.
Total 8 (delta 0), reused 0 (delta 0)
To https://github.com/75devanshsharma/pubhub-100.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.

E:\devansh1\dive7>git status
On branch master
Your branch is up-to-date with 'origin/master'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .classpath
        .project
        .settings/
        bin/

nothing added to commit but untracked files present (use "git add" to track)

E:\devansh1\dive7>cd..

E:\devansh1>\cd..
'\cd..' is not recognized as an internal or external command,
operable program or batch file.

E:\devansh1>cd..

E:\>cd devansh5\bookapp-core

E:\devansh5\bookapp-core>git init
Reinitialized existing Git repository in E:/devansh5/bookapp-core/.git/

E:\devansh5\bookapp-core>git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   src/main/java/model/customer.java
        deleted:    src/test/java/model/TestModel.java

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .classpath
        .project
        .settings/
        src/main/java/model/Book.java
        src/main/java/model/Order.java
        src/test/java/model/TestBook.java
        src/test/java/model/TestCustomer.java
        src/test/java/model/TestOrder.java
        target/

no changes added to commit (use "git add" and/or "git commit -a")

E:\devansh5\bookapp-core>git add src

E:\devansh5\bookapp-core>git commit -m "Added extra models"
[master abcced8] Added extra models
 Committer: user-27 <user-27>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 6 files changed, 121 insertions(+), 2 deletions(-)
 create mode 100644 src/main/java/model/Book.java
 create mode 100644 src/main/java/model/Order.java
 create mode 100644 src/test/java/model/TestBook.java
 rename src/test/java/model/{TestModel.java => TestCustomer.java} (57%)
 create mode 100644 src/test/java/model/TestOrder.java

E:\devansh5\bookapp-core>git remote add origin https://github.com/75devanshsharm
a/bookapp1.git
fatal: remote origin already exists.

E:\devansh5\bookapp-core>git push -u origin master
Username for 'https://github.com': 75devanshsharma@gmail.com
Password for 'https://75devanshsharma@gmail.com@github.com':
Counting objects: 15, done.
Delta compression using up to 24 threads.
Compressing objects: 100% (13/13), done.
Writing objects: 100% (15/15), 1.98 KiB | 0 bytes/s, done.
Total 15 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local objects.
To https://github.com/75devanshsharma/bookapp1.git
   31e7def..abcced8  master -> master
Branch master set up to track remote branch master from origin.

E:\devansh5\bookapp-core>
