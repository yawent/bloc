Type
```
git checkout master
git checkout -b shopping_cart_assignment
```
to create a new branch named shopping_cart_assignment.

Type
```
git rm apple.txt
```
to remove apple.txt. 

Type
```
open banana.txt
```
to open file and add the text.

Type 
```
touch lettuce.txt
```
to create a new file.

Type 
```
git diff > lettuce.txt
```
to add the output.

Type 
```
git add banana.txt
git add lettuce.txt
```
to put files under version control.

Type
```
git commit -m "rm apple.txt add text to banana.txt create and add text to lettce.txt"
```
to commit the changes.

Type
```
cat lettuce.txt
```
to print the contents
```
diff --git a/apple.txt b/apple.txt
deleted file mode 100644
index e69de29..0000000
diff --git a/banana.txt b/banana.txt
index e69de29..45d4fdb 100644
--- a/banana.txt
+++ b/banana.txt
@@ -0,0 +1 @@
+Git Checkpoint Assignment.a
\ No newline at end of file
```
