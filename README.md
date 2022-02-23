# git_HW_branch

1. **На локальном репозитории сделать ветки для:**   

- Postman 
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing  
****     
 + В github создаем репозиторий "git_HW_branch"  
   Клонируем в гитбаш - git clone [Ссылка](https://github.com/Pitsenko/git_HW_branch.git) 
 - В git bash :
   mkdir git_hw_branch && cd git_hw_branch  
   git unit  
   git branch Postman  
   git branch Jmeter  
   git branch CheckLists  
   git branch Bag_Reports  
   git branch SQL  
   git branch Charles  
   git branch Mobile_testing  

2. **Запушить все ветки на внешний репозиторий**  

 - git push origin --all 

3. **В ветке Bag Reports сделать текстовый документ со структурой баг репорта**  
   
 - git checkout Bag_Reports
 - vim b_rep.txt (Пишем репорт) 
 - ESC -> :wq -> enter

4. **Запушить структуру багрепорта на внешний репозиторий**  
 - git add b_rep.txt
 - git commit -m "Add bag_report"
 - git push --set-upstream origin Bag_Reports

5. **Вмержить ветку Bag Reports в Main**  
 - git checkout main
 - git merge Bag_Reports

6. **Запушить main на внешний репозиторий.**  

 - git push

7. **В ветке CheckLists набросать структуру чек листа.**  

 - git checkout CheckList
 - vim bagrep.txt (Пишем репорт) 
 - ESC -> :wq -> enter

8. **Запушить структуру на внешний репозиторий**  
 
 - git add bagrep.txt
 - git commit -m "Add bagrep file"
 - git push --set-upstream origin CheckLists 

9. **На внешнем репозитории сделать Pull Request ветки CheckLists в main**  

 - new pull request
 - Добавляем текст 
 - Create pull request
 - Merge pull request
 - Confirm pull request

10. **Синхронизировать Внешнюю и Локальную ветки Main**  

 - git pull

