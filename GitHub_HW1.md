GIT Homework 1

JSON
 4. Создать внешний репозиторий c названием JSON.
```Github - Repositories - New - Repository Name JSON, Public - Creat Repository

 5. Клонировать репозиторий JSON на локальный компьютер.
```code - copy HTTPS
```git clone https://github.com/ElenaYushkevich/JSON.git

 6. Внутри локального JSON создать файл “new.json”.
```cd JSON
```touch new.json

 7. Добавить файл под гит.
```git add new.json

 8. Закоммитить файл.
```git commit -m "add the json file"

 9. Отправить файл на внешний GitHub репозиторий.
```git push

 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
```cat >> file.json
```{
```"FirstName" : "Lena",
```"LastName"  : "Yushkevich",
```"Age"       : "13",
```"Pet"       : "0",
```"Pay"       : "5000"
```}

 11. Отправить изменения на внешний репозиторий.
```git add file.json
```git commit -m "add the changes file json"
```git push

 12. Создать файл preferences.json
```touch preferences.json

 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```cat >> preferences.json
```{ 
```"Movie"     : "BrestFortress"
```"SoapOpera" : "Svaty"
```"Food"      : "IceCream"
```"Season"    : "Summer"
```"Country"   : "Switzerland"
```} 

 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
```touch sklls.json
```cat >> sklls.json
```{
```	"skill1" : "Json",
```	"skill2" : "JavaScript",
```	"skill3" : "AndroidStudio",
```	"skill4" : "SQL",
```	"skill5" : "VPN",
```	"skill6" : "HTTP",
```	"skill7" : "GIT",
```	"skill8" : "Postman"
```} 

 15. Отправить сразу 2 файла на внешний репозиторий.
```git add preferences.json sklls.json
```git commit -m "add two files json"
```git push
или
```git add preferences.json sklls.json && git commit -m "add two files json" && git push
или
```git add . && git commit -m "add two files json" && git push

 16. На веб интерфейсе создать файл bug_report.json.
```JSON - Add File - Create new file - file name: bug_report.json 

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```Commit new file

 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
```{
```  "id"                  : "1",
```  "Summary"             : "LoginDialog",
```  "Preconditions"       : "Win10",
```  "Steps to Reproduce"  : {
```          "Step1" : "Launch Login Dialog",
```          "Step2" : "Valid Username field",
```          "Step3" : "Valid Password",
```          "Step4" : "Click login button"
```      },
```  "Expected Result"     : "User successfully logged into the application",
```  "Actual Result"       : "Fail" 
```}

 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```Commit changes

 20. Синхронизировать внешний и локальный репозиторий JSON
```git pull

XML
 21. Создать внешний репозиторий c названием XML.
```Github - Repositories - New - Repository Name XML, Public - Creat Repository

 22. Клонировать репозиторий XML на локальный компьютер.
```code - copy HTTPS
```git clone https://github.com/ElenaYushkevich/XML.git

 23. Внутри локального XML создать файл “new.xml”.
```cd XML
```touch new.xml

 24. Добавить файл под гит.
```git add new.xml

 25. Закоммитить файл.
```git commit -m "add the file new xml"

 26. Отправить файл на внешний GitHub репозиторий.
```git push

 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```cat >> new.xml
```<?xml version="1.0" encoding="UTF-8"?>
```<root>
```  <FirstName>Lena</FirstName>
```  <LastName>Yushkevich</LastName>
```  <Age>13</Age>
```  <Pet>0</Pet>
```  <Pay>5000</Pay>
```</root>

 28. Отправить изменения на внешний репозиторий.
```git add new.xml
```git commit -m "add the changes new xml"
```git push

 29. Создать файл preferences.xml
```touch preferences.xml

 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```cat >> preferences.json
```<?xml version="1.0" encoding="UTF-8"?>
```<prefer>
```  <Movie>BrestFortress</Movie>
```  <SopaOpera>Svaty</SopaOpera>
```  <Food>IceCream</Food>
```  <Season>Summer</Season>
```  <Country>Switzerland</Country>
```</prefer>

 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```touch sklls.xml
```cat >> sklls.xml
```<?xml version="1.0" encoding="UTF-8"?>
```<sklls>
```  <skill1>Json</skill1>
```  <skill2>JavaScript</skill2>
```  <skill3>AndroidStudio</skill3>
```  <skill4>SQL</skill4>
```  <skill5>VPN</skill5>
```  <skill6>HTTP</skill6>
```  <skill7>GIT</skill7>
```  <skill8>Postman</skill8>
```</sklls>

 32. Сделать коммит в одну строку.
```git add . && git commit -m "add two files"

 33. Отправить сразу 2 файла на внешний репозиторий.
```git push

 34. На веб интерфейсе создать файл bug_report.xml.
```XML - Add File - Create new file - file name: bug_report.xml

 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```Commit new file

 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
```bug_report.xml - Edit this file
```<?xml version="1.0" encoding="UTF-8"?>
```<bugReport>
```  <id>1</id>
```  <Summary>LoginDialog</Summary>
```  <Preconditions>Win10</Preconditions>
```  <Steps to Reproduce>
```    <Step1>Launch Login Dialog</Step1>
```    <Step2>Valid Username field</Step2>
```   <Step3>Valid Password</Step3>
```    <Step4>Click login button</Step4>    
```  </Steps to Reproduce>
```  <Expected Result>User successfully logged into the application</Expected Result>
```  <Actual Result>Fail</Actual Result>
```</bugReport>

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```Commit changes

 38. Синхронизировать внешний и локальный репозиторий XML
```git pull

TXT

 1. Создать внешний репозиторий c названием TXT.
```Github - Repositories - New - Repository Name TXT, Public - Creat Repository

 2. Клонировать репозиторий TXT на локальный компьютер.
```code - copy HTTPS
```git clone https://github.com/ElenaYushkevich/TXT.git

 3. Внутри локального TXT создать файл “new.txt”.
```cd TXT
```touch new.txt

 4. Добавить файл под гит.
```git add new.txt

 5. Закоммитить файл.
```git commit -m "add the file new txt"

 6. Отправить файл на внешний GitHub репозиторий.
```git push

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
```cat >> new.txt
```FirstName Lena
```LastName Yushkevich
```Age 13
```Pet 0
```Pay 5000

 8. Отправить изменения на внешний репозиторий.
```git add new.txt
```git commit -m "add the changes new txt"
```git push

 9. Создать файл preferences.txt
```touch preferences.txt

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
```cat >> preferences.txt
```Movie BrestFortress
```SoapOpera Svaty
```Food IceCream
```Season Summer
```Country Switzerland

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
```cat >> sklls.txt
```skill1 Json
```skill2 JavaScript
```skill3 AndroidStudio
```skill4 SQL
```skill5 VPN
```skill6 HTTP
```skill7 GIT
```skill8 Postman
```skill9 Charles

 12. Сделать коммит в одну строку.
```git add . && git commit -m "add two txt files"

 13. Отправить сразу 2 файла на внешний репозиторий.
```git push

 14. На веб интерфейсе создать файл bug_report.txt.
```TXT - Add File - Create new file - file name: bug_report.txt

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```Commit new file

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
```bug_report.txt - Edit this file
```id 1
```Summary LoginDialog
```Preconditions Win10
```Steps to Reproduce
```Step1 Launch Login Dialog
```Step2 Valid Username field
```Step3 Valid Password
```Step4 Click login button
```Expected Result User successfully logged into the application
```Actual Result Fail

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```Commit changes

 18. Синхронизировать внешний и локальный репозиторий TXT
```git pull