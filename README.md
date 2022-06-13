# XML
XML
 1. Создать внешний репозиторий c названием XML.
New Repository
 2. Клонировать репозиторий XML на локальный компьютер.
mkdir XML
cd XML
git clone git@github.com:viachK/XML.git
 3. Внутри локального XML создать файл “new.xml”.
touch new.xml
 4. Добавить файл под гит.
git add new.xml
 5. Закоммитить файл.
git commit -m "add XML file"
 6. Отправить файл на внешний GitHub репозиторий.
git push
7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
nano new.xml
<?xml version="1.0" encoding="utf-8"?>
<general>
        <name>
                <first_name>Viacheslav</first_name>
                <last_name>Kovryzhnykh</last_name>
        </name>
        <age>38</age>
        <number_of_pets>1</number_of_pets>
        <salary>450</salary>
</general>
 8. Отправить изменения на внешний репозиторий.
git commit -m "update XML file"
git push
 9. Создать файл preferences.xml
touch preferences.xml
 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
nano preferences.xml
<?xml version="1.0" encoding="utf-8"?>
<favorite>
        <movie>Matrix</movie>
        <series>Walking Death</series>
        <food>Pasta</food>
        <season>spring</season>
        <country>Australia</country>
</favorite>
 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
touch skills.xml
<?xml version="1.0" encoding="UTF-8"?>
<skills>
        <skill id="1" type="terminal"></skill>
        <skill id="2" type="client server model"></skill>
        <skill id="3" type="GitHub"></skill>
        <skill id="4" type="API testing">
                <tool>Postman</tool>
        </skill>
    </skills>
 12. Сделать коммит в одну строку.
git commit -m "create two new XML files"
 13. Отправить сразу 2 файла на внешний репозиторий.
git add .
git push --all
 14. На веб интерфейсе создать файл bug_report.xml.
Add File
Create New File
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Open File
Go to The Pencil Button
Edit This File
Commit Changes
 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
Open File
Go to The Pencil Button “Edit This File”
<bug_report>
<Bug_id>12345</Bug_id>
<Tit1e>Missing white lines on widgets</Tit1e>
<Severity>
<type>Moderate</type>
</Severity>
<Priority>
<type>Medium</type>
</Priority>
<Environment>Xiaomi Redmi 8A, MIUI Global 12.5.2, 10 QKQ1.191014.001</Environment>
<Precondition>Desktop grid 5x5, font size Medium, zoom Medium</Precondition>
<STR>
<step id="1" type="Add 5 widgets"/>
<step id="2" type="Arrange widgets as in the attachment"/>
</STR>
<AR>Square widget on the left has a missing white bottom line. The longest widget on the right has a missing white bottom line</AR>
<ER>All widgets have four white lines</ER>
<Attachments>https://bit.ly/3HfHhuL</Attachments>
</bug_report>

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit Changes
 18. Синхронизировать внешний и локальный репозиторий XML
git pull
