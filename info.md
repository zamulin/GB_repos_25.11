Привет, GitHub и мир
Hello, GitHub

# Инструкция по работе с Git

## Что такое Git и зачем он нужен?

> ***Git*** - это консольная утилита, для отслеживания и ведения истории изменения файлов, в вашем проекте. Чаще всего его используют для кода, но можно и для других файлов. Например, для картинок - полезно для дизайнеров.

![Логотип Git](https://media.proglib.io/wp-uploads/2018/01/e948f49dadbb4dc8af8da57a8843a635.png)

С помощью *Git* -a вы можете откатить свой проект до более старой версии, сравнивать, анализировать или сливать свои изменения в репозиторий.

>  ***Репозиторием*** называют хранилище вашего кода и историю его изменений. **Git** работает локально и все ваши репозитории хранятся в определенных папках на жестком диске.

## Основные команды 

| Название команды       | Описание       | 
| -----------------------| ---------------|
| [git init](https://www.atlassian.com/ru/git/tutorials/setting-up-a-repository/git-init)               | инициализация локального репозитория        | 
| [git status](https://www.atlassian.com/ru/git/tutorials/inspecting-a-repository)           | получить информацию от git о его текущем состоянии   |
| [git add](https://www.atlassian.com/ru/git/tutorials/saving-changes)                | добавить файл или файлы к следующему коммиту   |
| [git commit -m “message”](https://www.atlassian.com/ru/git/tutorials/saving-changes/git-commit]) | создание коммита   |
| [git log](https://www.atlassian.com/ru/git/tutorials/inspecting-a-repository)                | вывод на экран истории всех коммитов с их хеш-кодамии|
| [git checkout](https://www.atlassian.com/ru/git/tutorials/undoing-changes)           | переход от одного коммита к другому   |
| git checkout master    | вернуться к актуальному состоянию и продолжить работу|
| [git diff](https://www.atlassian.com/ru/git/tutorials/saving-changes/git-diff)               | увидеть разницу между текущим файлом и закоммиченным файлом| 

## Команды Git для работы с ветками

* **git** *branch* - посмотреть список веток в репозитории.

    >Больше информации смотри в [Материалах о Git branch](https://www.atlassian.com/ru/git/tutorials/using-branches).

* **git** *branch <Название ветки>* - Создание новой ветки.

      Создание новой ветки с именем ＜ветка＞. Эта команда не выполняет переключение на эту новую ветку.

    >Больше информации смотри в [Материалах о Git branch](https://www.atlassian.com/ru/git/tutorials/using-branches).

* **git** *checkout <название ветки>* - переход к другой ветке.

    Больше информации смотри в [Материалах о Git checkout](hhttps://www.atlassian.com/ru/git/tutorials/using-branches/git-checkout).

* git branch -d <название ветки> – удалить ветку

      Если поставить большю букву "D", тогда ветка удалиться придудительно, даже если в ней есть неслитые изменения.
      При использовании маленькой "d", Git удалит ветку, только если все изменения уже слиты в другую ветку.

* **git** *merge <название ветки>* - сольет названную ветку в mater

      Команда git merge объединяет несколько последовательностей коммитов в общую историю. Чаще всего команду git merge используют для объединения двух веток.

     >Больше информации смотри в [Материалах о Git merege](https://www.atlassian.com/ru/git/tutorials/using-branches/git-merge).
