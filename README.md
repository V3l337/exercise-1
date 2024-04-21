# Домашнее задание к занятию "GIT" - Матвеев Валентин

## Задание 1
Ответ: <https://github.com/V3l337/exercise-1/commit/60794e5c7c9b3fff22bbcbe3483621f1af8f65af>

## Задание 2
Решение: 

Создал файл - `touch .gitignore`

Добавил в индекс - `git add`

Создал коммит - `git commit -m "Добавлен файл .gitignore"`

Внес перечесления инорирующих файлов - `vim .gitignore -> 	*.pyc , cache/`

Добавил в индекс - `git add`

Создал коммит - `git commit -m "Добавил правила игнорирования в файл .gitignore"`

Отправил изменения из ветки в удаленный реп. - `git push origin main`

Ответ: <https://github.com/V3l337/exercise-1/commit/main>

## Задание 3
Решение:

Из предыдущих заданий у меня такой вывод

![Скриншот-1](https://github.com/V3l337/exercise-1/blob/main/1.png)

Решение: 

Вернулся к предыдущему комитту, удалив все последующие `git reset --hard 0a825c1`

Создал Новую ветку - `git checkout -b dev`

Создал файл - `touch test.sh`

Добавил в индекс - `git add test.sh`

Создал коммит - `git commit -m "Создал файл test.sh в dev"`

Изменил файл - `vim test.sh`

Добавил в индекс - `git add test.sh` 

Создал коммит - `git commit -m "Commit one in fil test.sh"`

Изменил файл - `vim test.sh`

Добавил в индекс - `git add test.sh` 

Создал коммит - `git commit -m "Commit two in file test.sh"`

Перешел в основную ветку - `git checkout main`

Создал файл - `touch main.sh`

Добавил в индекс - `git add main.sh`

Создал коммит - `git commit -m "Creat file main.sh in branch main"`

Сделал слияние двух веток - `git merge dev`

Просмотр статуса - `git status`

Просмотр графика `git log --graph `

Отправил изменения из ветки в удаленный реп. - `git push origin main `

Ответ: 

![Скриншот-1](https://github.com/V3l337/exercise-1/blob/main/2.png)

<https://github.com/V3l337/exercise-1/network>
