# XML
## Homework

1. Создать внешний репозиторий c названием XML. `create new file`
   
2. Клонировать репозиторий XML на локальный компьютер. `git clone https://github.com/ESKovalenko/XML.git`

3. Внутри локального XML создать файл “new.xml”. `touch new.xml`

4. Добавить файл под гит. `git add new.xml`

5. Закоммитить файл. `git commit -m “new.xml”`

6. Отправить файл на внешний GitHub репозиторий. `git push`

7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML. `cat > new.xml`

`<user>`
  
  `<full_name>Kovalenko Ekaterina Sergeevna</full_name>`
  
  `<age>27</age>`
  
  `<pets>2</pets>`
  
  `<salary>100</salary>`
  
`</user>`

 8. Отправить изменения на внешний репозиторий.

`git add .`

`git commit -m “new.xml”`

`git push`

 9. Создать файл preferences.xml `touch preferences.xml`

 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML. `cat > preferences.xml`

`<preferences>`

  `<favourite movie> A Dog's Purpose </favourite movie>`
  
  `<favourite series >Friends</favourite series>`
  
  `<favourite food>Sushi</favourite food>`
  
  `<country>Australia</country>`
  
`</preferences>`

 11. Создать файл sklls.
xml добавить информацию о скиллах которые будут изучены на курсе в формате XML `cat > skills. xml`

`<skills>`

  `<skill>Terminal</skill>`
  
  `<skill>Postman</skill>`
  
  `<skill>SQL</skill>`
  
  `<skill>Charles</skill>`
  
  `<skill>Fiddler</skill>`
  
  `<skill>Android Studio</skill>`
  
  `<skill>Jmeter</skill>`
  
  `<skill>Scrum</skill>`
  
`</skills>`

 12. Сделать коммит в одну строку. `git add .| git commit -m "preference and skils"`
    
 13. Отправить сразу 2 файла на внешний репозиторий. `git push`
     
 14. На веб интерфейсе создать файл bug_report.xml. `Create new file- bug_report.xml`
     
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. `Commit changes`
     
 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

`<bug_report>`

  `<title>Bug Title</title>`
  
  `<description>Bug Description</description>`
  
  `<steps_to_reproduce>Steps to Reproduce</steps_to_reproduce>`
  
  `<expected_result>Expected Result</expected_result>`
  
  `<actual_result>Actual Result</actual_result>`
  
  `<severity>Severity Level</severity>`
  
  `<priority>Priority</priority>`
  
  `<assigned_to>Assigned To</assigned_to>`
  
  `<reported_by>Reported By</reported_by>`
  
  `<attachments>`
  
  `<attachment>attachment1.png</attachment>`
    
  `<attachment>attachment2.log</attachment>`
    
  `</attachments>`
  
`</bug_report>`

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. `Commit changes`
     
 18. Синхронизировать внешний и локальный репозиторий XML `git pull`
