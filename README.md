1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bug Reports
- SQL
- Charles
- Mobile_testing

1.1 Открыть GitHub создать new repository “GitHubHW2”
1.2 Скопировать http или ssh repository ссылку
1.3 Открыть Terminal, ввести команду git clone "repository link"
1.4 Зайти в directory to "GitHubHW2" cd GitHubHW2
1.5 git branch Postman | git branch Jmeter | git branch CheckLists 
git branch Bug_Reports | git branch SQL | git branch Charles | git branch Mobile_testing

2. Запушить все ветки на внешний репозиторий
2.1 git push —-all —-set-upstream или git push —- all -u

3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта
3.1 Перейти в ветку BugReports branch : git checkout Bug_Reports
3.2 Cоздать текстовый файл touch bug_reports.txt
3.3 vim bug_reports.txt

4. Запушить структуру багрепорта на внешний репозиторий
4.1 git add bug_reports.txt
4.2 git commit -m «add bugreport»
4.3 git push 

5. Вмержить ветку Bug Reports в Main
5.1 Перейти в ветку main branch: git checkout main
5.2 git merge Bug_Reports

6. Запушить main на внешний репозиторий.
6.1 git push

7. В ветке CheckLists набросать структуру чек листа.
7.1 Jump into CheckLists branch: git checkout CheckLists
7.2 Создать файл txt touch checkLists.txt
7.3 Добавить данные в файл через vim 

8. Запушить структуру на внешний репозиторий
8.1 git add chechlIst.txt
8.2 git commit -m “add chechlist”
8.3 git push 

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
9.1 открыть GitHub.com 
9.2 New pull-request from CheckLIsts branch to Main
9.3 Compare changes and confirm merge 

10. Синхронизировать внешнюю и локальную ветки Main
10.1 Jump into main branch : git checkout main
10.2 git pull







