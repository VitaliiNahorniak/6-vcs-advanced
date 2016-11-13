# 6-vcs-advanced

Task1:  1)git branch architecture;
	2)git checkout architecture;
	3) create files - touch(створити файл) and foldes - mkdir(створити папку);
	4) git commit -m "added file and folders";
	5) added files at assets/ and added empty file at uploads/;
	6) commit and push;
	7) created .gitignore , and edited him -> "uploads/*.*";
	8) commit and push;
	9) pull request in master with architecture;
	9) git push origin :architecture.

Task2:  1)touch test1.txt & commit (master);
	2)git branch Vitalii;
	3)touch test2.txt & commit (master);
	4)git checkout Vitalii;
	5)git rebase master
	6)edited test1.txt та test2.txt & commit;
	7)git checkout master
	8)git merge vitalii
	9)git branch -b vitalii

Task3:  1)touch test.txt
	2)git add .
	3)git commit -m "..."
	4)git tag v1.1
	5)git push origin v1.1 
	6)git tag
	7)git checkout v1.1

Task4:  1)git submodule add |link| |folder|
	2)git add .
	3)git commit -m "..."
	
Task5:  1)git branch gh-pages
	2)git checkout gh-pages
	3)echo "Homework" > index.html
	4)git add .
	5)git commit -m "homework"
	6)git push origin gh-pages
	http://VitaliiNahorniak.github.io/HW-4/

Task6:  1) created file test1.txt
	2) git add .
	3) git commit -m "add file test1.txt"
	4) git branch proba
	5) edited test1
	6) git add .
	7) git commit -m "mod test1.txt"
	8) git checkout proba
	9) edited test1
	10)git add .
	11)git commit -m "mod again test1.txt"
	12)git checkout master
	13)git merge proba (conflict)
	14)git merge --abort
	15)no conflict
	16)git merge proba