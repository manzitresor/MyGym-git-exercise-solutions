# MyGym-git-exercise-solutions

## Bundle 1

### exercise 1

```bash
H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions
$ git init
Initialized empty Git repository in E:/theGym/Git/MyGym-git-exercise-solutions/.git/

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (master)
$ git branch -M main

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (main)
$ git add .

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (main)
$ git commit -m  "Create readme file"
[main (root-commit) 17d6511] Create readme file
 1 file changed, 5 insertions(+)
 create mode 100644 README.md

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (main)
$ git remote add origin https://github.com/manzitresor/MyGym-git-exercise-solutions.git

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 281 bytes | 281.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/manzitresor/MyGym-git-exercise-solutions.git
 * [new branch]      main -> main
H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (main)
$ git checkout -b dev
Switched to a new branch 'dev'

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/manzitresor/MyGym-git-exercise-solutions/pull/new/dev
remote:
To https://github.com/manzitresor/MyGym-git-exercise-solutions.git
 * [new branch]      dev -> dev

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git checkout -b test
Switched to a new branch 'test'

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/manzitresor/MyGym-git-exercise-solutions/pull/new/test
remote:
To https://github.com/manzitresor/MyGym-git-exercise-solutions.git
 * [new branch]      test -> test

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (main)
$ git checkout -b dev
Switched to a new branch 'dev'

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/manzitresor/MyGym-git-exercise-solutions/pull/new/dev
remote:
To https://github.com/manzitresor/MyGym-git-exercise-solutions.git
 * [new branch]      dev -> dev

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git checkout -b test 
Switched to a new branch 'test'

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/manzitresor/MyGym-git-exercise-solutions/pull/new/test
remote:
To https://github.com/manzitresor/MyGym-git-exercise-solutions.git
 * [new branch]      test -> test

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (test)
$ git checkout dev
Switched to branch 'dev'

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git branch -d test
Deleted branch test (was 17d6511).


H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (main)
$ git checkout -b dev
Switched to a new branch 'dev'

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/manzitresor/MyGym-git-exercise-solutions/pull/new/dev
remote:
To https://github.com/manzitresor/MyGym-git-exercise-solutions.git
 * [new branch]      dev -> dev

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git checkout -b test 
Switched to a new branch 'test'

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/manzitresor/MyGym-git-exercise-solutions/pull/new/test
remote:
To https://github.com/manzitresor/MyGym-git-exercise-solutions.git
 * [new branch]      test -> test

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (test)
$ git checkout dev
Switched to branch 'dev'

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git branch -d test
Deleted branch test (was 17d6511).

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git push origin --delete test
To https://github.com/manzitresor/MyGym-git-exercise-solutions.git
 - [deleted]         test
```

### exercise 2
```bash

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git add home.html

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git stash
Saved working directory and index state WIP on dev: 17d6511 Create readme file


H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git add about.html

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git stash
Saved working directory and index state WIP on dev: 17d6511 Create readme file

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git stash list
stash@{0}: WIP on dev: 17d6511 Create readme file
stash@{1}: WIP on dev: 17d6511 Create readme file

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git add team.html

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git stash list
stash@{0}: WIP on dev: 17d6511 Create readme file
stash@{1}: WIP on dev: 17d6511 Create readme file

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git stash
Saved working directory and index state WIP on dev: 17d6511 Create readme file

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git stash list
stash@{0}: WIP on dev: 17d6511 Create readme file
stash@{1}: WIP on dev: 17d6511 Create readme file
stash@{2}: WIP on dev: 17d6511 Create readme file

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (13247aba419a605c179ab68d93e9fa4499bec431)

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git stash list
stash@{0}: WIP on dev: 17d6511 Create readme file
stash@{1}: WIP on dev: 17d6511 Create readme file

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (8f5c5057e8f7e61175ed0ed124b318b1bdf90024)

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git add .

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git commit -m "Add home and about html pages"
[dev f387658] Add home and about html pages
 2 files changed, 23 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git push origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 571 bytes | 285.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/manzitresor/MyGym-git-exercise-solutions.git
   17d6511..f387658  dev -> dev

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git stash list
stash@{0}: WIP on dev: 17d6511 Create readme file

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git stash pop
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (5c8dd27fc215928c499e40bb534d365666246387)

H@DESKTOP-F8LTDIM MINGW64 /e/theGym/Git/MyGym-git-exercise-solutions (dev)
$ git reset --hard
HEAD is now at f387658 Add home and about html pages
```