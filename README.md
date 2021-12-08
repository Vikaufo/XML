# XML
1. **Создать внешний репозиторий c названием XML.**

Зайти в раздел Repositories на Github. Нажать "NEW". Создать репозиторий "XML"

 2. **Клонировать репозиторий XML на локальный компьютер.**
 
Перейти в репозиторий "JSON", вкладка "Code", скопировать HTTPS. В терминале вызвать команду git clone https://github.com/Vikaufo/XML.git

 3. **Внутри локального XML создать файл “new.xml”.**
 
touch new.xml

 4. **Добавить файл под гит.**
 
git add new.xml

 5. **Закоммитить файл.**
 
git commit -m "Add new file"

 6. **Отправить файл на внешний GitHub репозиторий.**
 
git push

 7. **Отредактировать содержание файла “new.xml” - написать информацию о себе. Всё написать в формате XML.**
 
vim new.xml (i - инфа о себе) esc :wq

 8. **Отправить изменения на внешний репозиторий.**
 
git add .

git commit -m "Modifided file"

git push

 9. **Создать файл preferences.xml**
 
touch preferences.xml

 10. **В файл preferences.xml добавить информацию о своих предпочтениях в формате XML.**
 
vim preferences.json (i - предпочтения) esc :wq

 11. **Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML**
 
touch skills.xml

vim (i - навыки) esc :wq

 12. **Сделать коммит в одну строку.**
 
git add . && git commit -m "Add preferences and skills" 

 13. **Отправить сразу 2 файла на внешний репозиторий.**
 
git push

 14. **На веб интерфейсе создать файл bug_report.xml.**

Вкладка "Add file - Create new file". Указать комментарий.

 15. **На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.**
 
Нажать "Edit this file"

 16. **Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
 
Нажать "Commit changes"

 17. **Синхронизировать внешний и локальный репозиторий XML**
 
git pull
