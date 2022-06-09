# TXT
1. Создать внешний репозиторий c названием TXT.
click new for creating repository
 2. Клонировать репозиторий TXT на локальный компьютер.
git clone link  
cd TXT
 3. Внутри локального TXT создать файл “new.txt”.
touch new.txt
 4. Добавить файл под гит.
git add new.txt
 5. Закоммитить файл.
git commit -m "add txt file"
 6. Отправить файл на внешний GitHub репозиторий.
git push
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
cat >> new.txt
First and Last name: Pavlo Mandiuk
Age: 36
Number of pets: 0
Salary: 400$
 8. Отправить изменения на внешний репозиторий.
git add new.txt
git commit -m "add changes"
git push

 9. Создать файл preferences.txt
touch preferences.txt
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
cat >> references.txt
Film: Star Wars
Serial: Star Treck
Food: Pizza
Season: Winter
Coutry: USA
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
cat >> skills.txt
skill: Bash
skill: Git
skill: Postman
skill: SQL
skill: Manual testing
 12. Сделать коммит в одну строку.
git add preferences.txt skills.txt ; git commit -m "add two more files"
 13. Отправить сразу 2 файла на внешний репозиторий.
git push
 14. На веб интерфейсе создать файл bug_report.txt.
add file 
create new file
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit new file
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
Edit this file
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes
 18. Синхронизировать внешний и локальный репозиторий TXT
git fetch
git pull
