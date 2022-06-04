# TXT

1. Создать внешний репозиторий c названием TXT.
```bash
New --> Repository name "TXT" --> Public --> add README file --> Create repository 
```
2. Клонировать репозиторий TXT на локальный компьютер.
```bash 
git clone + link repository && cd TXT
```
3. Внутри локального TXT создать файл “new.txt”.
```bash 
touch new.txt 
```
4. Добавить файл под гит.
```bash 
git add new.txt
```
5. Закоммитить файл.
```bash 
git commit -m "Version 1.0"
```
6. Отправить файл на внешний GitHub репозиторий.
```bash 
git push
```
7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
```bash 
vim new.txt --> i --> text --> ESC + :wq
```
8. Отправить изменения на внешний репозиторий.
```bash 
git add new.txt && git commit -m 'v.2' && git push
```
9. Создать файл preferences.txt
```bash 
touch preferences.txt
```
10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
```bash 
vim touch preferences.txt --> i --> text --> :wq
```
11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
```bash 
touch skills.txt && vim skills.txt
```
12. Сделать коммит в одну строку.
```bash 
git add . && git commit -m "added file: preferences and skills" 
```
13. Отправить сразу 2 файла на внешний репозиторий.
```bash 
git push	
```
14. На веб интерфейсе создать файл bug_report.txt.
```bash 
add file --> create new file --> Name your file "bug_report.txt"
```
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash 
Click the button "Commit directly to the main branch"
```
16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
```bash 
Choose bug_report.json --> Edit this file --> Text 
```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash 
Click the button "Commit changes"
```
18. Синхронизировать внешний и локальный репозиторий TXT
```bash 
git pull
```
