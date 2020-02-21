# Task \#13 - Git Branching: 

## Requeriments:
- All commits must be done using convention.
- Create a `parser-structure-fix` branch from `master` branch
- Switch to `parser-structure-fix` branch and start working from it
- Do [Task \#14](task-practice-java14-refactor.md)
- Add comment to DataBase.java with `/* I wrote complete wrong method here*/` and commit it `feat: add firstMethod`
- Add comment to DataBase.java with `/* I wrote extremely great method here*/` and commit it `feat: add secondMethod`
- Then you realized the commit with `feat: add firstMethod` was totaly wrong and you decided to create a new branch containing all the changes `parser-structure-fix-firstMethod`, but remove this wrong commit from you current branch. Do not change the code by yourself - do removal using git functionality.
- Create pull request `parser-structure-fix` -> `master`.  https://github.blog/2015-01-21-how-to-write-the-perfect-pull-request/

## Git commit naming convention:

    Названия коммитов должны быть согласно гайдлайна - https://www.conventionalcommits.org/en/v1.0.0-beta.2/
    Должен использоваться present tense ("add feature" not "added feature")
    Должен использоваться imperative mood ("move cursor to..." not "moves cursor to...")

Примеры имен коммитов

    init: - используется для начала проекта/таска. Примеры:

    init: start youtube-task
    init: start mentor-dashboard task

    feat: - это реализованная новая функциональность из технического задания (добавил поддержку зумирования, добавил footer, добавил карточку продукта). Примеры:

    feat: add basic page layout
    feat: implement search box 
    feat: implement request to youtube API
    feat: implement swipe for horizontal list
    feat: add additional navigation button
    feat: add banner
    feat: add social links
    feat: add physical security section
    feat: add real social icons

    fix: - исправил ошибку в ранее реализованной функциональности. Примеры:

    fix: implement correct loading data from youtube
    fix: change layout for video items to fix bugs
    fix: relayout header for firefox
    fix: adjust social links for mobile

    refactor: - новой функциональности не добавлял / поведения не менял. Файлы в другие места положил, удалил, добавил. Изменил форматирование кода (white-space, formatting, missing semi-colons, etc). Улучшил алгоритм, без изменения функциональности. Примеры:

    refactor: change structure of the project
    refactor: rename vars for better readability
    refactor: apply eslint
    refactor: apply prettier

    docs: - используется при работе с документацией/readme проекта. Примеры:

    docs: update readme with additional information
    docs: update description of run() method

## Useful Links:
https://learn.javascript.ru/screencast/git
