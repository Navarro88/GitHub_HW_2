### 1. На локальном репозитории сделать ветки для Postman, Jmeter, checklists, bug-reports, SQL, Charles, Mobile testing:</br>
git branch <имя ветки></br>
### 2. Запушить все ветки на внешний репозиторий</br>
git push origin --all -u</br>
### 3. В ветке bug-reports сделать текстовый документ со структурой баг репорта</br>
git checkout bug-reports</br>
cat >> struct.txt</br>
### 4. Запушить структуру багрепорта на внешний репозиторий</br>
git add struct.txt</br>
git commit -m "структура баг-репорта"</br>
git push</br>
### 5. Вмержить ветку bug-reports в Main</br>
git checkout main</br>
git merge bug-reports</br>
### 6. Запушить main на внешний репозиторий.</br>
git push</br>
### 7. В ветке checklists набросать структуру чек листа.</br>
git checkout checklists</br>
cat >> list.txt</br>
### 8. Запушить структуру на внешний репозиторий</br>
git add list.txt</br>
git commit -m "check list"</br>
git push</br>
### 9. На внешнем репозитории сделать Pull Request ветки checklists в main</br>
pull requests-> compare and pull request-> create pull request</br>
### 10. Синхронизировать Внешнюю и Локальную ветки Main</br>
git pull</br>


