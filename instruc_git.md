# ИНСТРУКЦИЯ ПО РАБОТЕ С GIT.

GIT - Программа контроля версий

*КОМАНДЫ GIT=*
1. git --version - проверка установленной текущей версии программы
2. git init - инициализация папки
3. git status - показывает текущее состояние гита
4. git add - добавляет содержимое рабочего каталога для последующего комита
5. git commit - фиксирует и сохраняет все введенные данные
6. git log - журнал сохранений версий
7. git checkout - переключение между версиями
8. git diff - показывает разницу между сохраненным и текущим файлом
9. git merge - слияние двух веток
10. git branch - удаление ветки.

**Для работы используется синтаксис языка Markdown**
* Курсивный текст - * (в начале и конце текста)
* Полужирный текст - ** (в начале и конце текста)
* Ненумерованные списки обозначаются знаками * в начале строки
* Нумерованные списки обозначаются цифрами 1,2,3... 
* Выделяют заголовки - # (в начале строки)

**Порядок действий**
* Установка Git и Visual Studio Code
* Настраиваем Visual Studio Code (привязываем через проводник свободную папку)
* Настраиваем Git (git --version, git init,...)
* Создаем файл с расширением
* Знакомимся с командами Git и синтаксисом языка Markdown

Нажатие клавиши -Q возвращает в исходное окно терминал

**Работа с черновиками**
* Создать ветку можно командой git branch
* Если потребуется переключиться с одной ветки на другую, то необходимо использовать git checkout
* Чтобы слить ветку с текущей вызываем команду git merge


## Ссылки в тексте

Ссылка на работу в программе [GitHub](https://github.com)

Ссылка для изучения команд git [Git] (https://habr.com/ru/post/541258/)

## Как сделать pull request
Делаем   (ответвление) репозитория fork.
Делаем git clone своей версии репозитория.
Создаем новую ветку и в нее вносим свои изменения. Фиксируем изменения (делаем коммиты). Отправляем свою версию в свой GitHub. На сайте GitHub нажимаем кнопку pull request.

*Команды работы с удаленными репозитариями, как настроить совместную работу*

1. git push - отправляет свою версию репозитария во внешний репозитарий
2. git clone - загружает все ветки и сливает в локальном и внешнем репозитарии
3. git pull - используется для извлечения и загрузки содержимого из удаленного репозитория и немедленного обновления локального репозитория этим содержимым

1. Создать аккаунт на GitHub.com. 
2. Создать локальный репозиторий.
3. "Подружить" ваш локальный и удаленный репозитарии.
4. Отправить (push) ваш локальный репозиторий в удаленный (на GitHub), при этом, возможно нужно будет авторизоваться на удаленном репозитории.
5. Провести изменения с "другого компьютера".
6. Выкачать (pull) актуальное состояние из удаленного репозитария.

Окончание 
