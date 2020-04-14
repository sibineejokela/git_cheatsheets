Hello Git and GitHub

Revisiting Git and commits. Adding text, in order to recommit. 
Testing git diff


Last login: Mon Apr 13 17:13:19 on ttys000
(base) GaysUponUs:~ sibinee$ mkdir git_practice
(base) GaysUponUs:~ sibinee$ cd git_practice
(base) GaysUponUs:git_practice sibinee$ pwd
/Users/sibinee/git_practice
(base) GaysUponUs:git_practice sibinee$ ls
(base) GaysUponUs:git_practice sibinee$ cs ../
-bash: cs: command not found
(base) GaysUponUs:git_practice sibinee$ cd ../
(base) GaysUponUs:~ sibinee$ ls
Applications		Library			Unity Projects
Creative Cloud Files	Movies			eclipse-workspace
Desktop			Music			git_practice
Documents		Pictures
Downloads		Public
(base) GaysUponUs:~ sibinee$ cd git_practice
(base) GaysUponUs:git_practice sibinee$ git init
Initialized empty Git repository in /Users/sibinee/git_practice/.git/
(base) GaysUponUs:git_practice sibinee$ echo "Hello Git and GitHub" >> README.txt
(base) GaysUponUs:git_practice sibinee$ git add README.txt
(base) GaysUponUs:git_practice sibinee$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.txt

(base) GaysUponUs:git_practice sibinee$ git commit -m "First commit"
[master (root-commit) df4d5da] First commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.txt
(base) GaysUponUs:git_practice sibinee$ cd
(base) GaysUponUs:~ sibinee$ pwd
/Users/sibinee
(base) GaysUponUs:~ sibinee$ ls
Applications		Library			Unity Projects
Creative Cloud Files	Movies			eclipse-workspace
Desktop			Music			git_practice
Documents		Pictures
Downloads		Public
(base) GaysUponUs:~ sibinee$ cd git_practice
(base) GaysUponUs:git_practice sibinee$ ls
README.txt
(base) GaysUponUs:git_practice sibinee$ git status
On branch master
nothing to commit, working tree clean
(base) GaysUponUs:git_practice sibinee$ git remote add origin https://github.com/sibineejokela/git_practice.git
(base) GaysUponUs:git_practice sibinee$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 231 bytes | 231.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/sibineejokela/git_practice.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
(base) GaysUponUs:git_practice sibinee$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   README.txt

no changes added to commit (use "git add" and/or "git commit -a")
(base) GaysUponUs:git_practice sibinee$ git add README.txt
(base) GaysUponUs:git_practice sibinee$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   README.txt

(base) GaysUponUs:git_practice sibinee$ git diff README.txt
(base) GaysUponUs:git_practice sibinee$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   README.txt

(base) GaysUponUs:git_practice sibinee$ git diff
(base) GaysUponUs:git_practice sibinee$ git diff README.txt
diff --git a/README.txt b/README.txt
index c62daf8..d7dc844 100644
--- a/README.txt
+++ b/README.txt
@@ -1,3 +1,4 @@
 Hello Git and GitHub
 
 Revisiting Git and commits. Adding text, in order to recommit. 
+Testing git diff
(base) GaysUponUs:git_practice sibinee$ git add README.txt
(base) GaysUponUs:git_practice sibinee$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   README.txt

(base) GaysUponUs:git_practice sibinee$ git commit
hint: Waiting for your editor to close the file... 

# Please enter the commit message for your changes. Lines starting
# with '#' will be ignored, and an empty message aborts the commit.
#
# On branch master
# Your branch is up to date with 'origin/master'.
#
# Changes to be committed:
#       modified:   README.txt
#
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
~                                                                               
"~/git_practice/.git/COMMIT_EDITMSG" 10L, 263C