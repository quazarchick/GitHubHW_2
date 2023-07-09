# GitHub. HW_2

GitHub. HW_2

1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing

```bash
$ git branch Postman && git branch Jmeter && git branch CheckLists && git branch BagReports && git branch SQL && git branch Charles && git branch MobileTesting
```

1. Запушить все ветки на внешний репозиторий

```bash
$ git push origin --all
```

1. В ветке Bag Reports сделать текстовый документ со структурой баг репорта

```bash
$ git checkout BagReports
$ nano bugReport.txt
```

1. Запушить структуру багрепорта на внешний репозиторий

```bash
$ git add bugReport.txt
$ git commit -m "bug report"
$ git config push.autoSetupRemote true
$ git push
```

1. Вмержить ветку Bag Reports в Main

```bash
$ git merge BagReports
```

1. Запушить main на внешний репозиторий.

```bash
$ git checkout main
```

1. В ветке CheckLists набросать структуру чек листа.

```bash
$ git checkout CheckLists
$ nano checkList.txt
```

1. Запушить структуру на внешний репозиторий

```bash
$ git add checkList.txt
$ git commit -m "new checklist"
$ git push
```

1. На внешнем репозитории сделать Pull Request ветки CheckLists в main

```bash
[https://github.com/quazarchick](https://github.com/quazarchick) -> repositories -> git_hw_2 -> CheckLists -> contribute -> open pull request -> create pull request -> Merge pull request -> Confirm merge
```

1. Синхронизировать Внешнюю и Локальную ветки Main

```bash
$ git pull
```