# PLPBasicGitAssignment
assignment
kenya@DESKTOP-6TJC9RQ MINGW64 /
$ cd c:/

kenya@DESKTOP-6TJC9RQ MINGW64 /c
$ cd Users/kenya/OneDrive/Documents/PLP\ Academy/PLPBasicGitAssignment/

kenya@DESKTOP-6TJC9RQ MINGW64 ~/OneDrive/Documents/PLP Academy/PLPBasicGitAssignment (master)
$ git init
Initialized empty Git repository in C:/Users/kenya/OneDrive/Documents/PLP Academy/PLPBasicGitAssignment/.git/

kenya@DESKTOP-6TJC9RQ MINGW64 ~/OneDrive/Documents/PLP Academy/PLPBasicGitAssignment (master)
$ git remote add origin https://github.com/01Laurent/PLPBasicGitAssignment.git

kenya@DESKTOP-6TJC9RQ MINGW64 ~/OneDrive/Documents/PLP Academy/PLPBasicGitAssignment (master)
$ git add hello.txt

kenya@DESKTOP-6TJC9RQ MINGW64 ~/OneDrive/Documents/PLP Academy/PLPBasicGitAssignment (master)
$ git commit -m "Add hello.txt with a greeting"
[master (root-commit) dae0d05] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt

kenya@DESKTOP-6TJC9RQ MINGW64 ~/OneDrive/Documents/PLP Academy/PLPBasicGitAssignment (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/01Laurent/PLPBasicGitAssignment.git'

kenya@DESKTOP-6TJC9RQ MINGW64 ~/OneDrive/Documents/PLP Academy/PLPBasicGitAssignment (master)
$ git commit -m "Hello"
On branch master
nothing to commit, working tree clean

kenya@DESKTOP-6TJC9RQ MINGW64 ~/OneDrive/Documents/PLP Academy/PLPBasicGitAssignment (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/01Laurent/PLPBasicGitAssignment.git'

kenya@DESKTOP-6TJC9RQ MINGW64 ~/OneDrive/Documents/PLP Academy/PLPBasicGitAssignment (master)
$ git branch
* master

kenya@DESKTOP-6TJC9RQ MINGW64 ~/OneDrive/Documents/PLP Academy/PLPBasicGitAssignment (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 238 bytes | 119.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/01Laurent/PLPBasicGitAssignment/pull/new/master
remote:
To https://github.com/01Laurent/PLPBasicGitAssignment.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

kenya@DESKTOP-6TJC9RQ MINGW64 ~/OneDrive/Documents/PLP Academy/PLPBasicGitAssignment (master)
