# Github
## TXT

1. Создать внешний репозиторий c названием TXT.
- на сайте github.com необходимо нажать `New`
  - в поле `Repository name` ввести `TXT`
  - выбрать следующие параметры: `Public` и  `Add a README file`
  - нажать `Create repository`

2. Клонировать репозиторий TXT на локальный компьютер.
- во вкладке `Code` необходимо скопировать HTTPS ссылку `https://github.com/katrin55/TXT.git`
- запустить GitBash, с помощью `pwd` проверить, что находимся в необходимой директории
- ввести команду `git clone https://github.com/katrin55/TXT.git`

3. Внутри локального TXT создать файл “new.txt”.
- зайти в папку созданного репозитория `cd TXT`
- в терминале ввести: `cat > new.txt`
- выйти из режима редактирования: `Ctrl+C`

4. Добавить файл под гит. \
`git add . `

5. Закоммитить файл. \
`git commit -m "add 1 txt file"`

6. Отправить файл на внешний GitHub репозиторий. \
`git push`

7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.

 - в терминале ввести `vim new.txt`
 - добавить:
```
name - Uglovskaia Ekaterina Evgenevna
age - 25
pets - 0
futureSalary - 50000
```
- для сохранения нажать esc :wq

8. Отправить изменения на внешний репозиторий. \
`git commit -am "change file new.txt` \
`git push`

9. Создать файл preferences.txt.
10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
- ввести `vim preferences.txt`
- добавить:
```
country i would like to visit - Switzerland
favorite movie - "1+1"
favorite series - "La casa de papel"
favorite time of the year - summer
```
- для сохранения нажать esc :wq

11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
- ввести `vim skills.txt`
 - добавить:
```
Skills:
1. The theory of software testing
2. Client server arhitecture
3. Structures of HTTP requests and responses
4. Structure of JSON, XML formats</fourth>
5. API testing with Postman (JS, API autotests)
6. Removing and reading logs from an external server
7. Sniffing http web traffic with Charles and Fiddler
8. Dev Tools of web browsers Google Chrome and FireFox
9. VPN, Proxy
10. Mobile testing
11. Building Android Applications with Android Studio
12. ADB
13. Setting up proxy and vpn on iOS and Android
14. Intercepting mobile traffic with Charles and Fiddler
15. Linux terminal
16. Access to remote servers
17. SQL Basics. Create, Delete, Drop, Insert Into, Select, From, Where, Join
18. Postgres database
19. Redis non-relational database
20. Load Testing with Jmeter
```
- для сохранения нажать esc :wq

12. Сделать коммит в одну строку. \
` git add . && git commit -m "add 2 files txt"`

13. Отправить сразу 2 файла на внешний репозиторий. \
`git push`

OB14. На веб интерфейсе создать файл bug_report.txt.
- в репозитории нажимаем на кнопку `Add file`, далее `Create new file`
- в названии ввести `bug_report.txt`

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. \
 нажать кнопку `Commit new file`

OB16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
- в файл bug_report.txt добавить:
```
Sammary : Application crash on clicking the SAVE button while creating a new user
Reported_by : Ekaterina U
Build Number : Version Number 5.0.1
Enviroment : Windows 7, Chrome 31.0.1650.63 m
Severity : HIGH
Priority : HIGH
Description : Application crashes upon clicking the SAVE button while creating a new the user, hence unable to create a new user

Steps to Reproduce :
1. Login into the Application.
2. Navigate to the Users Menu -> click "New User".
3. Filled out all the user information fields.
4. Clicked on the ‘Save’ button.
5. Seen an error page ORA1090 Exception: Insert values Error.
6. See the attached logs for more information.
7. Also see the attached screenshot of the error page.

Expected Result : On clicking the SAVE button you should be prompted to a successful message: "New User has been created successfully".
```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. \
- нажать кнопку `Commit new file`
18. Синхронизировать внешний и локальный репозиторий TXT. \
- в терминале GitBash ввести `git pull`




