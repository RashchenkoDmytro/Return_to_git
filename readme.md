# Git and Github course

Crash course for Git

Terminal comands:
git —version   - версія git
git —help   - список команд які підтримуються
ls  - що знаходиться в цій папці
cd Documents  - перехід в папку Documents 
git init   - створення системної папки для git
cd ..  - вихід з папки назад
git status  - на якій гілці знаходиться і які файли не записані чи записані
git add (назва файлу) - щоб додати файл на гілку або оновити зміни у файлі 
git rm —cashed index.html(-назва файлу) - щоб відмінити додавання або зміни файлу
clear - очистити термінал
git add .  - додати кілька документів або внести всі зміни які були зроблені 
git commit -m “first commit” - додавання commit з його назвою 
git branch  - огляд дерева на якій гілці знаходимось
git branch test - створення новоі гілки test
git branch -D test - видалення гілки test
git checout readme  - прехід на гілку readme
git checout -b new - створення новоі гілки readme і одразу перехід на неі
git merge new  - додавання (обєднання) інформаціі між головною гілкою (треба бути на головній гілці)
git remote add origin <link> 
git push -u origin main 