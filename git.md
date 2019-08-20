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
