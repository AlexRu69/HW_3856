# Команды по работе GIT
# Команды GIT

* init - инициализирует репозиторий(Запуск Git).

* status - показывает состояние репозитория.

* commit - сделать комментари.

* log - журнал.

* git checkout "имя версии" - переход между версиями.

* git checkout master -  вернуться в основную версию.

* git diff - сверяет текущую версию с другими.

* git branch "название ветки" - создать ветку.

* git checkout  "название ветки" - переход между ветками.

[Источник1.](https://habr.com/ru/post/541258/)

[Источник2.](https://habr.com/ru/post/542616/)

> Далее познакомимся с MD

## Возможности MD

1. *Курсив*

2. **Полужирынй**

3. ***Жирный курсив***

4. ~~Зачеркнутый~~

[Источник: Взято из курса GB](https://habr.com/ru/post/542616/)

![GB](GB.png)

> Далее продолжим работать с GIT

что бы удалить ветку, испульзуем команду:

* git branch -d 'NAME'- удалить ветку

для слияние веток, используеим:

* git merge 'name'

Если мы добавляем такой файл, как картинку, то в git status он будет как не отслеживаемый, как исправить:

Создаем в репозитории файл **.gitignore**, далее прописываем сюда название файла которые мы не хотим отслеживать, с расширением. сохраняем и делаеим комит и теперь файл не будет отображаться в неотслеживаемых

* git log --graph - показывает работу с веткамми и где происходило слияние!

* сделаем таблицу

 цвет | количество | размер 
:-------|:--------:|--------:
красный | 1 |256
синий   | 2 |22
зеленый | 3 |356

1. отправляю текст на github

команда git push

## ДЗ №3 (Работа с удаленными репозиториями)

* Для работы с удаленными репозиториями необходимо зарегистрироваться на портале 

* GitHub

* Команды, которые будут полезны для работы с удаленными репозиториями:

* git clone (адрес удаленного репозитория на GitHub) — создание копии репозитория 
по правильному GIT

* cd.\ имя нужной папки - переход в нужную папку (при создании клона GIT требуется 

* папка в папке, поэтому сделать переход)

* git push — добавление изменений с GIT на GitHub

* git pull - добавление изменений с GitHub в Git

* fork - создание копии внешнего репозитория на собственном аккаунте в GitHub

* запрос на вытягивание - это отправление владельца репозитория своей версии 

* изменений, которую мы рассматриваем в своей конкретной ветке и загрузили ее в

* свой аккаунт в форкнутый репозиторий.