# Коммиты

## Создание коммитов
Git add

Для добавления изменений в коммит используется команда `git add` и имя
![gitAdd](photos/image.png)


## Отправить коммит
```bash
git commit -m "your_message"
```
> git commit - обращение к GIT
>
>-m - добавить сообщение (комментарий)
>
>"your_message" - комментарий (в кавычках)

![gitCommit](photos/commit.png)

## Посмотреть список коммитов
* `git log` - стандартный вид
* `git log --graph` - вид с графическим отображением веток
![gitLog](photos/log.png)
!


## Перейти к сохранению
 ```git checkout```
* ```git checkout <номер коммита, первые 4 символа>``` - перейти к определенному изменению 
* ```git checkout master``` - перейти к изменению последнего коммита 
## Посмотреть есть ли не сохранненные изменения репозитория (файлов)
![gitCheckout](photos/checkout.png)
* ```get status```
![gitStatus](photos/status.png)

## Работа с ветками
* ```git branch``` - посмотреть список веток 
* ```git branch <название ветки>``` - создать ветку (новая ветка унаследует коммиты родительской ветки) 
* ```git checkout <название ветки>``` - перейти на ветку 
* ```git branch -d <название ветки>``` - удалить ветку после merge 
* ```git branch -D <название ветки>``` - удалить ветку принудительно 
* ```git merge <название сливаемой ветки>``` - сливание веток 
![gitBranch](photos/branch.png)
![gitBranch](photos/branch 1.png)
![gitBranch](photos/branch 2.png)
![gitBranch](photos/branch 3.png)
![gitBranch](photos/branch 4.png)
