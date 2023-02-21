# JSON
 4. Создать внешний репозиторий c названием JSON. 
 5. Клонировать репозиторий JSON на локальный компьютер. 
`mkdir JSON
cd JSON`
git clone https://github.com/krllfdrv/JSON.git
 6. Внутри локального JSON создать файл “new.json”. 
cd JSON
touch new.json
git status
 7. Добавить файл под гит. 
git add new.json
git status
 8. Закоммитить файл.
git commit -m "Json" 
 9. Отправить файл на внешний GitHub репозиторий. 
git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
vim new.json
cat new.json 
 11. Отправить изменения на внешний репозиторий. 
git status
git commit -am "added main info"
git push
 12. Создать файл preferences.json 
touch preferences.json
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON. 
vim preferences.json
cat new.json 
 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON 
touch preferences.json
vim sklls.json
cat sklls.json
 15. Отправить сразу 2 файла на внешний репозиторий.
git status
git add  preferences.json sklls.json
git status
git commit -m "added skills and preferences"
git push
 16. На веб интерфейсе создать файл bug_report.json. 
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. 
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
 20. Синхронизировать внешний и локальный репозиторий JSON 
git pull
