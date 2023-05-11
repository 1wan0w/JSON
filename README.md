**JSON
 4. Создать внешний репозиторий c названием JSON -> GitHub>Repositories>New "JSON" repositories
 5. Клонировать репозиторий JSON на локальный компьютер -> git clone ssh-link
 6. Внутри локального JSON создать файл “new.json” -> touch new.json
 7. Добавить файл под гит -> git add new.json
 8. Закоммитить файл - git commit -m "new"
 9. Отправить файл на внешний GitHub репозиторий -> git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON -> vim new.json
 11. Отправить изменения на внешний репозиторий -> git commit -am "update">git push
 12. Создать файл preferences.json -> touch preferences.json
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON -> vim preferences.json
 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON -> touch skills.json
 15. Отправить сразу 2 файла на внешний репозиторий -> git add * >git commit -m "new files">git push
 16. На веб интерфейсе создать файл bug_report.json -> Github>Repositories>"JSON">Add file>Create new file
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе > Tap on the [Commit changes...]button
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON -> bug_report.json>[Edit this file]
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе -> Tap on the [Commit changes...]button
 20. Синхронизировать внешний и локальный репозиторий JSON -> git pull
