**JSON**<br>
 4. Создать внешний репозиторий c названием JSON<br> **->**`GitHub>Repositories>New "JSON" repositories`<br>
 5. Клонировать репозиторий JSON на локальный компьютер<br> **->**`git clone ssh-link`<br>
 6. Внутри локального JSON создать файл “new.json”<br> **->**`touch new.json`<br>
 7. Добавить файл под гит<br> **->**`git add new.json`<br>
 8. Закоммитить файл<br> **->**`git commit -m "new"`<br>
 9. Отправить файл на внешний GitHub репозиторий<br> **->**`git push`<br>
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON<br> **->**`vim new.json`<br>
 11. Отправить изменения на внешний репозиторий<br> **->**`git commit -am "update">git push`<br>
 12. Создать файл preferences.json<br> **->**`touch preferences.json`<br>
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON<br> **->**`vim preferences.json`<br>
 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON<br> **->**`touch skills.json`<br>
 15. Отправить сразу 2 файла на внешний репозиторий<br> **->**`git add * >git commit -m "new files">git push`<br>
 16. На веб интерфейсе создать файл bug_report.json<br> **->**`Github>Repositories>"JSON">Add file>Create new file`<br>
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе<br> **->**`Tap on the [Commit changes...]button`<br>
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON<br> **->**`bug_report.json>[Edit this file]`<br>
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе<br> **->**`Tap on the [Commit changes...]button`<br>
 20. Синхронизировать внешний и локальный репозиторий JSON<br> **->**`git pull`<br>
