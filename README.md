# HW_GitBash_Branch


**1. На локальном репозитории сделать ветки для Postman, Jmeter, CheckLists, Bag Reports, SQL, Charles, Mobile testing:**
- git branch Postman
- git branch Jmeter
- git branch CheckLists
- git branch Bag_Reports
- git branch SQL
- git branch Charles
- git branch Mobile_testing

**2. Запушить все ветки на внешний репозиторий** 
- git push -u origin --all

**3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта**
- git checkout BagReports
- vim bag_report.txt
- баг репорт 
- жмем i чтобы перейти в режим набора текста, после нажимаем esc и пишем :wq, жмем enter

**4. Запушить структуру багрепорта на внешний репозиторий**
- git add bag_report.txt
- git commit - m "Создал bag_report.txt" 
- git push

**5. Вмержить ветку Bag Reports в Main** 
- git checkout main
- git merge Bag_Reports

**6. Запушить main на внешний репозиторий**
- git add .
- git push -u origin main

**7. В ветке CheckLists набросать структуру чек листа** 
- git checkout Checklists
- vim checklist.txt
- чек-лист
- жмем i чтобы перейти в режим набора текста, после нажимаем esc и пишем :wq, жмем enter

**8. Запушить структуру на внешний репозиторий** 
- git add checklist.txt
- git commit -m "Создал checklist.txt"
- git push

**9. На внешнем репозитории сделать Pull Request ветки CheckLists в main**
 сделал

**10. Синхронизировать Внешнюю и Локальную ветки Main**
- git pull
