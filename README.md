**МОЙ DOCKER-ПРОЕКТ**
=====================

Задача: заверунть какую-либо программу в контейнер, используя Docker и создать CI/CD пайплан.

Как запустить DOCKER
=====================
Чтобы начать сборку, я использовал Терминал. Ввел команду cd + путь до папки в которой лежал Dockerfile.
Далее следуем инструкции:
1. **Собрать образ:**

   docker build -t kostas-app .
3. **Запустить:**

   docker run -d -p 8000:8000 --name net. kostas-app 

Имена kostas-app и net. можете заменить на свои

Как работает CI/CD pipeline?.
=====================
Инструкция:
1. **Создать какие-либо изменения**

     Добавляем изменения в проект, создаем коммит
3. **Пуш**

   Пушим эти изменения и следим за выполнением "джобы"
5. **Docker Hub**

   Если джобы выполнены, то заходим на Docker Hub и смотрим, выполнилась ли задача или нет.


В **main.yml** в конце нужно заменить имя пользователя и пароль от своего DockerHub аккаунта/

#### Contact me:
[![Telegram](https://img.shields.io/badge/Telegram-262424?style=for-the-badge&logo=Telegram)](https://t.me/ffraud)
