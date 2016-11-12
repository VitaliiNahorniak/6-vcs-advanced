# 6-vcs-advanced

Task1:  1) створив бренчу architecture - git branch architecture;
	2) переключився в architecture - git checkout architecture;
	3) створив структуру за допомогою touch(створити файл) mkdir(створити папку);
	4) закомітив - git commit -m "added file and folders";
	5) додав файли в папку assets/ за допомогою touch;
	6) commit and push;
	7) сворив .gitignore , та прописв в файлі "uploads/*.*";
	8) змерджив зміни в master за допомгою pull request;
	9) видалив репо architecture - git push origin :architecture.

Task2:  1)створив файл test1.txt та закомітив в бренчі мастер;
	2)створив бренчу "Vitalii"
	3)в бренчі мастер створив інший файл test2.txt який також закомітив
	4)git rebase master
	5)перейшов в бренчу "Vitalii" зробив зміни в test1.txt та test2.txt та закомітив
	6)перейшовши в мастер виконав git merge vitalii.
	7)та видалив репо vitalii (git branch -b vitalii)
	![](http://fs132.www.ex.ua/get/760518583289/285865796/2.png)
	![](http://fs44.www.ex.ua/get/760518583289/285866654/2-1.png)

Task3:  в любий момент створення проекту, можна зробити мітку до якої можна повернутись
	git tag v1.1 - створення мітки, git tag - список міток, git checkout v1.1 - повернутись на мітку,
	git push origin v1.1 - запушити мітку

Task4:  додав підмодуль - git submodule add (лінк)
	![](http://fs132.www.ex.ua/get/760518583289/285865812/4.png)

Task5:  стоворив файл index.html в репо gh-pages:
	http://VitaliiNahorniak.github.io/HW-4/
	![](http://fs132.www.ex.ua/get/760518583289/285865819/5.png)
	![](http://fs131.www.ex.ua/get/760518583289/285865822/5-1.png)

Task6:  Відколов гілку, зробив несумісні змінив одному і тому файлі в обох гілках, та створив конфлікт:
	![](http://fs132.www.ex.ua/get/760518583289/285865825/6.png)