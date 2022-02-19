## GitHub.
# HW 2.1

1. На локальном репозитории сделать ветки для:
Postman, Jmeter, Checklists, BagReports, SQL, Charles, MobileTesting

```
git branch Postman
git branch Jmeter
git branch Checklists
git branch BagReportts
git branch SQL
git branch Charles
git branch MobileTesting
```
2. Запушить все ветки на внешний репозиторий
```
git push -u origin Postman, Jmeter, Checklists, BagReports, SQL, Charles, MobileTesting
```
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
```
git checkout BagReports
vim Bag_report_1.txt
```
4. Запушить структуру багрепорта на внешний репозиторий
```
git add ./
git commit -m "Bag"
git push
```
5. Вмержить ветку Bag Reports в Main
```
git checkout main
git merge BagReports
```
6.  Запушить main на внешний репозиторий
```
git push -u origin main
```
7. В ветке CheckLists набросать структуру чек листа.
```
git checkout CheckLists
vim CheckLists.txt
```
8. Запушить структуру на внешний репозиторий
```
git add ./
git commit -m "Check List"
git push -u origin Checklists
```
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
```
Статус: "Pull request successfully merged and closed"
```
10. Синхронизировать Внешнюю и Локальную ветки Main
```
git checkout main
git pull
```

