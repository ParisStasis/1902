# lesson#1

**git --version**
*git status*
* git add name
1. git commit -m(messeg)"name commit"
2. git log -журнал изменений
+ git checkout num commit -переход между сохранениями
_git checkout master - переход в актуальное состояние_
__git diff -разница между текущим файлом и сохраненным__

## lesson#2
git branch
git branch name
git branch -d name -удаление ветки
git merge name - слияние веток
git log --graph -визуализация изменения коммитов ветвей
git checkout -b name -создать/перейти ветку
git cherry-pick 5589877 -скопировать на активную ветку изменения из указанного коммита
git rm name - удалить отслеживаемый неизменённый файл и проиндексировать это изменение
git show HEAD - показать данные о предыдущем коммите в активной ветке
git branch --merged        # показать ветки, уже слитые с активной
git reset --hard  # прекратить это прерванное слияние, вернуть рабочую директорию и индекс как было в момент коммита, на который указывает HEAD, а я пойду немного поплачу)))

## Lesson 3 

git clone ссылка из код гитхаб
