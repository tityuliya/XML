Как отправить ДЗ на проверку.
 1. Создайте текстоовый файл как в первом ДЗ по Terminal.
 2. Сценарий перенесите в этот файл.
 3. На против каждого действия - напишите команду в GitBash
Файл со сценарием и ссылку на свой гит хаб отправляйте менторам на проверку.


__XML__

1. Создать внешний репозиторий c названием XML.

2. Клонировать репозиторий XML на локальный компьютер.
```
    - git clone https://github.com/tityuliya/XML.git
```
3. Внутри локального XML создать файл “new.xml”.
```
    - cd XML
    - vim new.xml
```
4. Добавить файл под гит.
```
    - git add new.xml
```
5. Закоммитить файл.
```
    - git commit -m "add new.xml"
```
6. Отправить файл на внешний GitHub репозиторий.
```
    - git push
```
7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```
    - vim new.xml
```
8. Отправить изменения на внешний репозиторий.
``` 
    - git commit -am "change new.xml"
    - git push
```
9. Создать файл preferences.xml
```
    - vim preferences.xml
```
10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```
    - vim skills.xml
```
12. Сделать коммит в одну строку.
```
    - git add . | git commit -m "add files preferences and skills"
    или
    - git add . ; git commit -m "add files preferences and skills"
    или
    - git add . && git commit -m "add files preferences and skills"
```
13. Отправить сразу 2 файла на внешний репозиторий.
```
    - git push
```
14. На веб интерфейсе создать файл bug_report.xml.

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

18. Синхронизировать внешний и локальный репозиторий XML
```
    - git pull
```

