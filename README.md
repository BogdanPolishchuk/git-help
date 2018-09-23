# git-help 23.09.2018
 
для работы с гитхабом есть стандартный графический интерфейс (для windows): 
https://desktop.github.com/

для работы в терминале-консоли приложение :
https://gitforwindows.org/

при установке обязательно выбрать:
- Use Git from the Windows Command Prompt

после уствновки в контекстном меню(правая кнопка мыши) любой папки появятся два пункта, нужен "Git Bash Here".

далее откроется баш-терминал как в линуксе.

необходимо добавить глобальные настройки:

git config --global user.name 'имя_пользователя_github'
git config --global user.email 'ваша_электронная_почта'
git config --global color.diff 'auto'
git config --global color.status 'auto'
git config --global color.branch 'auto'
git config --global credential.helper store
git config --global push.default simple
git config --global core.autocrlf false
git config --global core.eol lf


далее задачи по необходимости, скачать существующий на гитхабе репозиторий, закачать в существующий репозиторий обновлённую инфу и т.д.

#рекомендация: создать локальную папку GitHub

для скачивания/клонирования существующего репозитория: открыть папку GitHub в баш-терминале:

Home@Home-PC MINGW64 ~/Desktop/GitHub
$ git clone https://github.com/BogdanPolishchuk/имя_репозитория.git - ссылка есть на странице гит-репозитория

в локальной папке GitHub появится папка с именем проэкта

при изменении файлов локально или удалённо необходимо выполнять:

Home@Home-PC MINGW64 ~/Desktop/GitHub/git-help (master)
$ git status

будет отображены отличия репозитория и локальной папки

Для загрузки в репозиторийновых одного или нескольких файлов :
для одного :
$ git add имя_файла - #для одного файла
для нескольких :
$ git add -A 

далее стандартно для обоих случаев:

$ git commit -m "комментарий что сделалось"
$ git push -f

чтобы скачать обновления с репозитория:

$ git pull



