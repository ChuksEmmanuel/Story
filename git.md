chukw@Chuks MINGW64 ~/OneDrive/Desktop/node/gitAndGitHub/story
$ git int

<!-- We use -->git init <!-- to initialize git -->

<!-- In order to start tracking your files, you need add your files to what called a staging area -->

<!-- To see what is currently in your staging aream you can use the -->//*git status command 
chukw@Chuks MINGW64 ~/OneDrive/Desktop/node/gitAndGitHub/story
$ git status

<!-- In order to track your files and add them to the staging area, we need to use a command called -->git add  
chukw@Chuks MINGW64 ~/OneDrive/Desktop/node/gitAndGitHub/story
$ git add <file name>
 
<!-- The above command to add the specified file to the staging area-->

<!-- To commit a file, we make use of the  --> //git commit 
<!--  command, to specify a message we make use of the  --> -m
<!-- flag along side the message we want, eg given below -->
chukw@Chuks MINGW64 ~/OneDrive/Desktop/node/gitAndGitHub/story (master)   
$ git commit -m "complete chapter 1"
[master (root-commit) 2b5249b] complete chapter 1
 1 file changed, 1 insertion(+)
 create mode 100644 chapter1.txt

 <!-- The commit message is usually in present tense -->



<!-- we can also view our logs to see our previous commits -->
chukw@Chuks MINGW64 ~/OneDrive/Desktop/node/gitAndGitHub/story (master)   
$ git log
commit 2b5249b06cb8f3e0ce2df463b8ebd0ffda9b1f77 (HEAD -> master)
Author: Chukwunweike Emmanuel <chukwunweikeemmanuel3096@gmail.com>        
Date:   Wed Aug 21 00:13:50 2019 +0100

    complete chapter 1

<!-- We can use  --> git add .
<!-- To add everything inside a particular directory -->

<!-- We an use the  --> git diff
<!-- command to check the difference between our current changes and the last commit -->
<!-- The  --> git diff 
<!-- Takes the name of the fle we want to track. E.g below -->

chukw@Chuks MINGW64 ~/OneDrive/Desktop/node/gitAndGitHub/story (master)   
$ git diff chapter3.txt
diff --git a/chapter3.txt b/chapter3.txt
index 1a3bbb8..b174ee7 100644
--- a/chapter3.txt
+++ b/chapter3.txt
@@ -1 +1 @@
-I am the spring of breath, it was the winter of silence
\ No newline at end of file
+silence, did i silence, you were screaming as fuck, there was no fucking 
silence anywhere
\ No newline at end of file

<!-- To revert to the last commit of a particular file, we make use of the --> git checkout <file name>
chukw@Chuks MINGW64 ~/OneDrive/Desktop/node/gitAndGitHub/story (master)
$ git checkout chapter3.txt
Updated 1 path from the index

<!-- pushing local repository to github remove repo -->
<!-- first inform git about your remote repo by running the cmd below
 -->
 chukw@Chuks MINGW64 ~/OneDrive/Desktop/node/gitAndGitHub/story (master)   
$ git remote add origin https://github.com/Chuks-dev/Story.git

Push your local repo to ur remote re


The git ignore file are files that you do not want to move to  your public repository 