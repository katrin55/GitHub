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

## XML

1. Создать внешний репозиторий c названием XML.
- на сайте github.com необходимо нажать `New`
- в поле `Repository name` ввести `XML`
- выбрать следующие параметры: `Public` и  `Add a README file`
- нажать `Create repository`

2. Клонировать репозиторий XML на локальный компьютер.
- во вкладке `Code` необходимо скопировать HTTPS ссылку `https://github.com/katrin55/XML.git`
- запустить GitBash, с помощью `pwd` проверить, что находимся в необходимой директории
- ввести команду `git clone https://github.com/katrin55/XML.git`

3. Внутри локального XML создать файл “new.xml”.
- зайти в папку созданного репозитория `cd XML`
- в терминале ввести: `cat > new.xml`
- выйти из режима редактирования: `Ctrl+C`

4. Добавить файл под гит. \
`git add . `

5. Закоммитить файл. \
`git commit -m "add 1 xml file"`

6. Отправить файл на внешний GitHub репозиторий. \
`git push`

7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

 - в терминале ввести `vim new.xml`
 - добавить: 
``` 
<aboutmyself>
   <name>Uglovskaia Ekaterina Evgenevna</name>
   <age>25</age>
   <pets>0</pets>
   <futureSalary>50000</futureSalary>
</aboutmyself>
```
- для сохранения нажать esc :wq

8. Отправить изменения на внешний репозиторий. \
`git commit -am "change file new.xml` \
`git push`

9. Создать файл preferences.xml
10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

- ввести `vim preferences.xml`
- добавить: 
```
<preferences>
   <country_i_would_like_to_visit>Switzerland</country_i_would_like_to_visit>
   <favorite_food>pasta</favorite_food>
   <favorite_movie>1+1</favorite_movie>
   <favorite_series>la_casa_de_papel</favorite_series>
   <favorite_time_of_the_year>summer</favorite_time_of_the_year>
</preferences>
```
- для сохранения нажать esc :wq

11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
- ввести `vim skills.xml`
 - добавить: 
```
<skills>
      <first>The theory of software testing</first>
      <second>Client server arhitecture</second>
      <third>Structures of HTTP requests and responses</third>
      <fourth>Structure of JSON, XML formats</fourth>
      <fifth>API testing with Postman (JS, API autotests)</fifth>
      <sixth>Removing and reading logs from an external server</sixth>
      <seventh>Sniffing http web traffic with Charles and Fiddler</seventh>
      <eighth>Dev Tools of web browsers Google Chrome and FireFox</eighth>
      <ninth>VPN</ninth>
      <tenth>Mobile testing</tenth>
      <eleventh>Building Android Applications with Android Studio</eleventh>
      <twelve>ADB</twelve>
      <thirteen>Setting up proxy and vpn on iOS and Android</thirteen>
      <fourteen>Intercepting mobile traffic with Charles and Fiddler</fourteen>
      <fifteen>Linux terminal</fifteen>
      <sixteen>Access to remote servers</sixteen>
      <seventeen>SQL Basics. Create, Delete, Drop, Insert Into, Select, From, Where, Join</seventeen>
      <eighteen>Postgres database</eighteen>
      <nineteen>Redis non-relational database</nineteen>
      <twenty>Load Testing with Jmeter</twenty>
</skills>
```
- для сохранения нажать esc :wq

12. Сделать коммит в одну строку. \
` git add . && git commit -m "add 2 files xml"`

13. Отправить сразу 2 файла на внешний репозиторий. \
`git push`

14. На веб интерфейсе создать файл bug_report.xml.
- в репозитории нажимаем на кнопку `Add file`, далее `Create new file`
- в названии ввести `bug_report.xml`

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. \
 нажать кнопку `Commit new file`

16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
- в файл bug_report.xml добавить: 
```
<bug_report>
	<Sammary>Application crash on clicking the SAVE button while creating a new user</Sammary>
	<Reported_By>Ekaterina U</Reported_By>
	<Build_Number>Version Number 5.0.1</Build_Number>
	<Enviroment>Windows 7, Chrome 31.0.1650.63 m</Enviroment>
	<Severity>HIGH</Severity>
	<Priority>HIGH</Priority>
	<Description>Application crashes upon clicking the SAVE button while creating a new the user, hence unable to create a new user</Description>
	<Steps_to_Reproduce>
		<first>Login into the Application</first>
		<second>Navigate to the Users Menu -&gt; New User</second>
		<third>Filled out all the user information fields</third>
		<fourth>Clicked on the &#x2018;Save&#x2019; button</fourth>
		<fifth>Seen an error page ORA1090 Exception: Insert values Error</fifth>
		<sixth>See the attached logs for more information</sixth>
		<seventh>Also see the attached screenshot of the error page</seventh>
	</Steps_to_Reproduce>
	<Expected_Result>On clicking the SAVE button you should be prompted to a successful message New User has been created successfully</Expected_Result>
</bug_report>
```

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. \
- нажать кнопку `Commit new file`

18. Синхронизировать внешний и локальный репозиторий XML. \
- в терминале GitBash ввести `git pull`

## JSON

 4. Создать внешний репозиторий c названием JSON.
  - на сайте github.com необходимо нажать `New`
  - в поле `Repository name` ввести `JSON`
  - выбрать следующие параметры: `Public` и  `Add a README file`
  - нажать `Create repository`
  
 5. Клонировать репозиторий JSON на локальный компьютер.
 - во вкладке `Code` необходимо скопировать HTTPS ссылку `https://github.com/katrin55/JSON.git`
 - запустить GitBash, с помощью `pwd` проверить, что находимся в необходимой директории
 - ввести команду `git clone https://github.com/katrin55/JSON.git`

 6. Внутри локального JSON создать файл “new.json”
 - зайти в папку созданного репозитория `cd JSON`
 - ввести `vim new.json`
 - добавить: 
```
{ 
 "name" : "Uglovskaia Ekaterina Evgenevna", 
 "age" : 25, 
 "pets" : 0,  
 "future_salary": 50000
}
```
- для сохранения нажать esc :wq

 7. Добавить файл под гит. \
 `git add new.json`

 8. Закоммитить файл. \
 `git commit -m "add 1 file json"`

 9. Отправить файл на внешний GitHub репозиторий. \
`git push`

 10. Создать файл preferences.json.
 11. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

- ввести `vim preferences.json`
 - добавить: 
```
{
 "favorite_movie" : "1+1",
 "favorite_series": "la_casa_de_papel",
 "favorite_food": "pasta",
 "favorite_time_of_the_year": "summer",
 "country_i_would_like_to_visit": "Switzerland"
}
```
- для сохранения нажать esc :wq

 12. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

- ввести `vim skills.json`
 - добавить: 
```
{
 "skills": [
	 "The theory of software testing",
	 "Client server arhitecture",
	 "Structures of HTTP requests and responses",
	 "Structure of JSON, XML formats",
	 "API testing with Postman (JS, API autotests)",
	 "Removing and reading logs from an external server",
	 "Sniffing http web traffic with Charles and Fiddler",
	 "Dev Tools of web browsers Google Chrome and FireFox",
	 "VPN",
	 "Mobile testing",
	 "Building Android Applications with Android Studio",
	 "ADB",
	 "Setting up proxy and vpn on iOS and Android",
	 "Intercepting mobile traffic with Charles and Fiddler",
	 "Linux terminal",
	 "Access to remote servers",
	 "SQL Basics. Create, Delete, Drop, Insert Into, Select, From, Where, Join",
	 "Postgres database",
	 "Redis non-relational database",
	 "Load Testing with Jmeter",
	 "Scrum Methodology"
 	]
}
```
- для сохранения нажать esc :wq

 13. Отправить сразу 2 файла на внешний репозиторий. 
- `git add . `
- `git commit -m "add 2 files json"`
- `git push`

 14. На веб интерфейсе создать файл bug_report.json.
- в репозитории необходимо нажать на кнопку `Add file`, далее `Create new file`
- в названии ввести `bug_report.json`
- добавить: 
```
{ 
  "Sammary" : "Application crash on clicking the SAVE button while creating a new user",
  "Reported_By" : "Ekaterina U",
  "Build_Number" : "Version Number 5.0.1",
  "Enviroment" : "Windows 7, Chrome 31.0.1650.63 m",
  "Severity" : "HIGH",
  "Priority" : "HIGH",
  "Description" : "Application crashes upon clicking the SAVE button while creating a new the user, hence unable to create a new user",
  "Steps_to_Reproduce" : { "1" : "Login into the Application",
                           "2" : "Navigate to the Users Menu -> New User",
                           "3" : "Filled out all the user information fields",
                           "4" : "Clicked on the ‘Save’ button",
                           "5" : "Seen an error page ORA1090 Exception: Insert values Error",
                           "6" : "See the attached logs for more information",
                           "7" : "Also see the attached screenshot of the error page"
                         },
  "Expected Result" : "On clicking the SAVE button you should be prompted to a successful message New User has been created successfully"
}
``` 

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. \
- нажать на кнопку `Commit new file`

 17. Синхронизировать внешний и локальный репозиторий JSON \
- в терминале GitBash ввести `git pull`



