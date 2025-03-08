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

![gitCommit](photos/commit.PNG)

## Посмотреть список коммитов
* `git log` - стандартный вид
* `git log --graph` - вид с графическим отображением веток
![gitLog](photos/log.PNG)
!


## Перейти к сохранению
 ```git checkout```
* ```git checkout <номер коммита, первые 4 символа>``` - перейти к определенному изменению 
* ```git checkout master``` - перейти к изменению последнего коммита 
## Посмотреть есть ли не сохранненные изменения репозитория (файлов)
![gitCheckout](photos/checkout.PNG)
* ```get status```
![gitStatus](photos/status.PNG)

## Работа с ветками
* ```git branch``` - посмотреть список веток ![gitBranch](photos/branch.PNG)
* ```git branch <название ветки>``` - создать ветку (новая ветка унаследует коммиты родительской ветки) ![gitBranch](photos/branch1.PNG)
* ```git checkout <название ветки>``` - перейти на ветку ![gitBranch](photos/branch2.PNG)
* ```git branch -d <название ветки>``` - удалить ветку после merge ![gitBranch](photos/branch3.PNG)
* ```git branch -D <название ветки>``` - удалить ветку принудительно ![gitBranch](photos/branch4.PNG)

