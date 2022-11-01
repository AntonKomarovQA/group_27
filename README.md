## GitHub.
# HW 2.1

1. На локальном репозитории сделать ветки для:
Postman, Checklists, SQL

```
git branch Postman
git branch Checklists
git branch SQL
```
2. Запушить все ветки на внешний репозиторий
```
git push -u origin Postman, Checklists, SQL
```
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
```
git checkout BagReports
vim Bag_report_1.txt
```
4. В ветке CheckLists набросать структуру чек листа.
```
git checkout CheckLists
vim CheckLists.txt
```
5. Запушить структуру на внешний репозиторий
```
git add ./
git commit -m "Check List"
git push -u origin Checklists
```
6. На внешнем репозитории сделать Pull Request ветки CheckLists в main
```
Compare $ pull request. 
Выбираем из Checklists в main
Добавляем комментарий (опционально)
Merge pull request
Статус: "Pull request successfully merged and closed"
```
7. Синхронизировать Внешнюю и Локальную ветки Main
```
git checkout main
git pull

