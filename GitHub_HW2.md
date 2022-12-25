﻿GitHub. HW_2

1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bug Reports
- SQL
- Charles
- Mobile testing
```bash
Github - Repositories - New - Repository Name GitBrabch, Public - Creat Repository
```
Клонировали на локальный компьютер
```bash
code - copy HTTPS
git clone https://github.com/ElenaYushkevich/GitBranch.git
cd GitBranch
```
```bash
git branch Postman
git branch Jmeter
git branch CheckLists
git branch BugReports
git branch SQL
git branch Charles
git branch MobileTesting
```
2. Запушить все ветки на внешний репозиторий
```bash
git push -u origin Postman
git push -u origin Jmeter
git push -u origin CheckLists
git push -u origin BugReports
git push -u origin SQL
git push -u origin Charles
git push -u origin MobileTesting
```
или
```bash
git push -u origin --all
```
3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта
git checkout BugReports
```bash
cat >> bugreport.txt
Summary
Project
Component
Version
Severity
Priority
Steps to Reproduce
Actual Result
Expected ResultAdditional Information
Ctrl+C
```
4. Запушить структуру багрепорта на внешний репозиторий
```bash
git add .
git commit -m "adding bugreport file"
git push
```
5. Вмержить ветку Bug Reports в Main
```bash
git checkout main
git merge BugReports -m "merge bugreports"
```
6. Запушить main на внешний репозиторий.
```bash
git push
```
7. В ветке CheckLists набросать структуру чек листа.
```bash
git checkout CheckLists
cat >> checklist.txt
Id
Tester Actions
Actual Resalt
Comment
Ctrl+C
```
8. Запушить структуру на внешний репозиторий
```bash
git add .
git commit -m "adding checklist file"
git push
```
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
```bash
Switch branches/tags - CheckLists - Compare & pull request - Create pull request - Merge pull request - Confirm merge
```
10. Синхронизировать Внешнюю и Локальную ветки Main
```bash
git checkout main
git pull
```