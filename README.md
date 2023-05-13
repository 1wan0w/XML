**XML<br>
 4. Создать внешний репозиторий c названием XML -> `GitHub>Repositories>New "XML" repositories`<br>
 5. Клонировать репозиторий XML на локальный компьютер -> `git clone ssh-link`<br>
 6. Внутри локального XML создать файл “new.xml” -> `touch new.xml`<br>
 7. Добавить файл под гит -> `git add new.xml`<br>
 8. Закоммитить файл -> `git commit -m "new"`<br>
 9. Отправить файл на внешний GitHub репозиторий -> `git push`<br>
 10. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML -> `vim new.xml`<br>
 11. Отправить изменения на внешний репозиторий -> `git commit -am "update">git push`<br>
 12. Создать файл preferences.xml -> `touch preferences.xml`<br>
 13. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML -> `vim preferences.xml`<br>
 14. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML<br> -> `touch skills.xml`<br>
 15. Отправить сразу 2 файла на внешний репозиторий -> `git add * >git commit -m "new files">git push`<br>
 16. На веб интерфейсе создать файл bug_report.xml<br> -> `Github>Repositories>"XML">Add file>Create new file`<br>
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе -> `Tap on the [Commit changes...]button`<br>
 18. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML -> `bug_report.xml>[Edit this file]`<br>
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе -> `Tap on the [Commit changes...]button`<br>
 20. Синхронизировать внешний и локальный репозиторий XML -> `git pull`<br>
