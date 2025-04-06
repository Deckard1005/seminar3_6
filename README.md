
1. Настрой имя и email (нужно сделать один раз):

git config --global user.name "Ваше имя"
git config --global user.email "ваш.email@example.com"

2. Создай папку и перейди в неё:

mkdir my-project
cd my-project

3. Инициализируй репозиторий Git:

git init

4. Посмотри, что происходит в репозитории

git status

5. Добавить конкретный файл:

git add название_файла.txt

Или добавить сразу все изменения в папке:

git add .

6. Закоммитить добавленные файлы с пояснением:

git commit -m "Ваш комментарий о том, что изменено"

7. Чтобы подключить удалённый репозиторий (ссылку можно получить на GitHub после создания пустого репозитория):

git remote add origin https://github.com/ваше_имя/имя_репозитория.git

Отправить изменения на удалённый репозиторий (на GitHub):

git push -u origin main

8. Если кто-то внес изменения на GitHub, ты можешь подтянуть их:

git pull origin main
