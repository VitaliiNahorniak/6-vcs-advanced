# 6-vcs-advanced

Task1:  1) git branch architecture
	2) git checkout architecture
	3) mkdir uploads
	4) mkdir assets
	5) touch index.html
	6) cd assets
	7) touch all.js
	8) touch css.js
	9) cd ..
	10) touch uploads/test.txt
	11) git status
	12) git add .
	13) git commit -m "added file and folders"
	14) git push origin architecture
	15) touch .gitignore
	16) echo "uploads/*.*" > .gitignore
	17) git add .
	18) git commit -m "add .gitignore"
	19) git push origin architecture
	20) git checkout master
	21) git merge architecture
	22) git push origin :architecture

Task2:  1)touch test1.txt
	2)git add .
	3)git commit -m "added test1.txt" (master)
	4)git branch Vitalii
	5)touch test2.txt
	6)git add .
	7)git commit -m "added test2.txt"(master)
	8)git checkout Vitalii
	9)git rebase master
	10)echo "1234567890" > test1.txt
	11)echo "0987654321" > test2.txt
	12)git add .
	13)git commit -m "edited test1 & test2"
	14)git checkout master
	15)git merge vitalii
	16)git branch -b vitalii

Task3:  1)touch test.txt
	2)git add .
	3)git commit -m "new file test.txt"
	4)git tag v1.1
	5)git add .
	6)git commit -m "added tag"
	7)git push origin v1.1 
	8)git tag
	9)git checkout v1.1

Task4:  1)git submodule add |link| |folder|
	2)git add .
	3)git commit -m "added submodule"
	
Task5:  1)git branch gh-pages
	2)git checkout gh-pages
	3)echo "Homework" > index.html
	4)git add .
	5)git commit -m "homework"
	6)git push origin gh-pages
	http://VitaliiNahorniak.github.io/HW-4/

Task6:  1) touch test1.txt
	2) git add .
	3) git commit -m "add file test1.txt"
	4) git branch proba
	5) git add .
	6) git commit -m "edited test1.txt"
	7) git checkout proba
	8)git add .
	9)git commit -m "edited test1.txt in branch proba"
	10)git checkout master
	11)git merge proba (conflict)
	12)git merge --abort
	13)(no conflict)
	14)git merge proba