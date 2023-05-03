# GIT_lesson_2 (branches)
1. На локальном репозитории сделать ветки для:  
- Postman - Jmeter - CheckLists - Bag Reports - SQL - Charles - Mobile testing  
- 
    Git clone https://github.com/atrf87/GIT_lesson_2_branches.git
    
    Cd GIT_lesson_2_branches
    
    Git branch
    
    Git branch Postman
    
    Git branch Jmeter
    
    Git branch CheckList
    
    Git branch Bag_Reports
    
    Git branch SQL
    
    Git branch Charles
    
    Git branch Mobile testing  
    
2. Запушить все ветки на внешний репозиторий 

    Git push -u origin Postman
    
    Git push -u origin Jmeter
    
    Git push -u origin CheckLists
    
    Git push -u origin – Bug_Reports
    
    Git push -u origin SQL
    
    Git push -u origin Charles
    
  	Git push -u origin Mobile_testing 
    
3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта  

    Git checkout Bug Reports
    
    Cat > bag_reports.txt
    
4. Запушить структуру багрепорта на внешний репозиторий  

    Git add .
    
    Git commit -m “bug_report”
    
    Git push
    
5. Вмержить ветку Bag Reports в Main  
    Git checkout main
    Git merge Bug_Reports
6. Запушить main на внешний репозиторий.
    Git push
7. В ветке CheckLists набросать структуру чек листа.  
    Git checkout CheckLists
    Cat > CheckLists.txt
8. Запушить структуру на внешний репозиторий  
    Git add .
    Git commit -m “CheckLists_new2”
    Git push
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main  
    Заходим в ветку Main
    
    Жмём Compare & pull request
    
    Выбираем compare: CheckLists
    
    Жмём Create pull request
    
    Жмём merge pull request
    
    Жмём confirm merge
    
10. Синхронизировать Внешнюю и Локальную ветки Main
    Git checkout CheckLists
   	Git pull
