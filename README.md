# TXT
 1. Создать внешний репозиторий c названием TXT.
```bash
На вэбе Repositories --> New --> Repos Name:TXT --> Check "Add a README file" --> Press "Create repository"
```
 2. Клонировать репозиторий TXT на локальный компьютер.
```bash
git clone <HTTPS repo>
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
git commit -m "add txt file"
```
 6. Отправить файл на внешний GitHub репозиторий.
```bash
git push
```
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
```bash
cat > new.txt   --> ^C
or
vim new.txt
```
```bash
1. full nsme: Bragin Andrei Aleksandrovich.
2. Age: 47.
3. number of pets: 1.
4. future desired salary: 1000$
```
 8. Отправить изменения на внешний репозиторий.
```bash
git commit -am "add name in txt file"  
--> git push
```
 9. Создать файл preferences.txt
```bash
touch preferences.txt
```
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
```bash
cat > preferences.txt  --> ^C
or
vim preferences.txt
```
```bash
My preferences:

1)favorite moovies: "The Green Mile";
2)favorite serial: The Office;
3)favorite food: Vegetables;
4)favorite time of year: spring;
5)country i want to visit: Switzerland
```
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
```bash
cat > skills.txt   --> ^C
or
vim skills.txt
```
```bash
1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.
2. Что такое клиент-серверная архитектура.
3. HTTP Методы запросов на сервер.
4. Коды ответов HTTP сервера.
5. Структуры HTTP запросов и ответов.
6. Что такое JSON, XML. Их структура.
7. Тестирование API через Postman (JS, автотесты API).
8. Снятие и чтение логов c внешнего сервера.
9. Снифинг http web трафика через Charles и Fiddler.
10. Dev Tools веб браузеров (Google Chrome, FireFox).
11. VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)
12. Мобильное тестирование.
13. Особенность iOS, Android, гайдлайны.
14. Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)
15. Сборка Android приложений на Android Studio.
16. ADB (управление андройд девайсами).
17. Настройка прокси и vpn на iOS и Android.
18. Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.
19. Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)
20. Основы bash скриптинг, автоматизация рутинных задач на сервере.
21. Доступ к удалённым серверам.
22. Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).
23. База данных Postgres (установка, настройка и использование).
24. Нереляционная база данных Redis (установка, настройка и использование).
25. Нагрузочное тестирование в Jmeter.
26. Методология разработки Scrum.
27. Python. (Изучение основ. Создание клиент серверного приложения)
```
 12. Сделать коммит в одну строку.
```bash
git add --all && git commit -m "comment"
```
 13. Отправить сразу 2 файла на внешний репозиторий.
```bash
git push
```
 14. На веб интерфейсе создать файл bug_report.txt.
```bash
Add file --> Create new file --> Name: bug_report.txt
```
```bash
Environment: <your environment>
ID: 1
Summury: <What? Where? Why?>
Steps to reproduce: 1.
                    2.
                    3.
                     ....
Expected Result: 1. ...
                 2. ...
                 3. ...
Actual Result: 1. ...
               2. ...
               3. ...
Attachments: <img/video>
```
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash
Commit New File
```
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
```bash
Choose bug_report.txt --> Edit this file
```
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash
Commit changes
```
 18. Синхронизировать внешний и локальный репозиторий TXT
```bash
git pull
```
___
## Видео по вышеуказанному заданию можно посмотреть [здесь](https://youtu.be/JcyNMygBx8w)
___
