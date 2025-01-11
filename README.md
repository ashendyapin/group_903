Это проект Ильнара Шафигуллина группа 903 на гитхабе.

Мы клонировали в свою папку форк этого проекта с уже нашего репозитория
на гитхабе.
Перешли в эту папку.
Создали ветку description и далее как ниже:


...\group_903> cd 'D:\CUsers\Desktop\SkillboxMat\Git\GitExample 3\group_903\'

...\group_903> git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

...\group_903> git branch
* master

...\group_903> git branch description

...\group_903> git checkout description
Switched to branch 'description'
...\group_903> git branch
* description
  master

Теперь мы в ветке description создаем этот файл (мышкой на group_903) - README.md
Далее все сохранияем (Ctrl S),
git status,
git add README.md
git commit...

Далее, чтобы предложить изначальным разработчикам свою ветку,
мы ее сначала толкнем в свой форковый репозиторий командой `push`
Команда git push выдаст в хелпе команду
`git push --set-upstream origin description`
С ее помощью мы и обновим свой форковый гитхабовский репозиторий
На гитхабе мы ее найдем в ветке `decription`. Т.е. мы будем предлагать
авторам свои изменения не как есть, а в виде отдельной (не мастер) ветки.
И на нашем гитхаб аккаунте появляется кнопка `Compare and Pool request`
