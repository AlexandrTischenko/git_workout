

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

## Squash нескольких локальных коммитов: 

`git cherry -v <branch>` - список коммитов в текущей ветке, которые были добавлены относительно ветки `<branch>`

`git cherry -v  <branch> | wc -l` - кол-во добавленных коммитов


`git commit --amend -m "Новое название"` - переименовать последний коммит
`git commit --amend` - дописать последний коммит
fg - вернуться в интерактивный ребейз 