# Test_Fork
Simple palindrome project 

Steps to fork and create pull request:

1) Click on fork
2) In the forked project, Click on clone
3) In your termical, type
git clone 
4) Create a branch
git branch sneha_work
5) Checkout the branch
git checkout sneha_work
6) Make changes
7) Commit the changes
git commit -a
8) Create pull request
9) Resolve the reviewed pull request
10) Commit the new change and push the changes
git push
11) Collaborator will merge the changes from your fork to Master
git merge
12) Delete the branch from you fork.

Commands:

# git clone https://github.com/SnehaDL/Test.git 

# cd Test/ 

/Test# ls -ltr 
total 8 
-rw-r--r-- 1 root root 387 Jul 14 12:46 test.py 
-rw-r--r-- 1 root root 520 Jul 14 12:46 README.md 

/Test# vi test.py 

/Test# git diff test.py 
diff --git a/test.py b/test.py 
index 62a63c8..a5a8470 100644 
--- a/test.py 
+++ b/test.py 
@@ -1,6 +1,7 @@ 
 # Program to check if a string 
 #  is palindrome or not 
 
+#!/usr/bin/python 
 # take input from the user 
 my_str = input("Enter a string: ") 
 
/Test# git add –all 

/Test# git commit -m "adding a line" 

/Test# git push origin origin/sneha 


root@MWPYT106:/home/sneha/Desktop/Raxak/tesfork/Test# git checkout origin/origin/sneha 

root@MWPYT106:/home/sneha/Desktop/Raxak/tesfork/Test# git checkout origin/sneha 
Switched to branch 'origin/sneha' 

root@MWPYT106:/home/sneha/Desktop/Raxak/tesfork/Test# ls -ltr 
total 8 
-rw-r--r-- 1 root root 520 Jul 14 12:46 README.md 
-rw-r--r-- 1 root root 405 Jul 14 12:51 test.py 

root@MWPYT106:/home/sneha/Desktop/Raxak/tesfork/Test# vi test.py 

root@MWPYT106:/home/sneha/Desktop/Raxak/tesfork/Test# git diff 
diff --git a/test.py b/test.py 
index a5a8470..75ae3ca 100644 
--- a/test.py 
+++ b/test.py 
@@ -1,6 +1,6 @@ 
 # Program to check if a string 
 #  is palindrome or not 
- 
+#adding the path for python 
 #!/usr/bin/python 
 # take input from the user 
 my_str = input("Enter a string: ") 

root@MWPYT106:/home/sneha/Desktop/Raxak/tesfork/Test# git add -all 

root@MWPYT106:/home/sneha/Desktop/Raxak/tesfork/Test# git commit -m "adding the comment line" 

root@MWPYT106:/home/sneha/Desktop/Raxak/tesfork/Test# git push origin origin/sneha 

