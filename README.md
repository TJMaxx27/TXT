# TXT
1. Создать внешний репозиторий c названием TXT.
``` New --> Repository name "TXT" --> Public --> add README file --> Create repository ```
2. Клонировать репозиторий TXT на локальный компьютер.
```git clone + link repository && cd TXT```
3. Внутри локального TXT создать файл “new.txt”.
``` touch new.txt ```
4. Добавить файл под гит.
``` git add new.txt```
5. Закоммитить файл.
```git commit -m "Version 1.0"```
6. Отправить файл на внешний GitHub репозиторий.
```git push```
7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в ```формате TXT.
vim new.txt --> i --> text --> ESC + :wq```
8. Отправить изменения на внешний репозиторий.
```git add new.txt && git commit -m 'v.2' && git push```
9. Создать файл preferences.txt
```touch preferences.txt```
10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
```vim touch preferences.txt --> i --> text --> :wq```
11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
```touch skills.txt && vim skills.txt```
12. Сделать коммит в одну строку.
```git add . && git commit -m "added file: preferences and skills" ```
13. Отправить сразу 2 файла на внешний репозиторий.
```git push	```
14. На веб интерфейсе создать файл bug_report.txt.
```add file --> create new file --> Name your file "bug_report.txt"```
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```Click the button "Commit directly to the main branch"```
16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
```Choose bug_report.json --> Edit this file --> Text ```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```Click the button "Commit changes"```
18. Синхронизировать внешний и локальный репозиторий TXT
```git pull```
