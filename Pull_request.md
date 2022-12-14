# Инструкция Pull-request с другого профиля

1. Для того чтобы сделать pull-request с другого профиля, необходимо зайти в этот репозиторий на GitHub и в правом верхнем углу нажать на значек вилки (1) затем нажать на зеленую кнопку **Create fork** (2).

![](screen/2022-08-14_17-18-05.png)

2. После чего нас перекидывает на свой профиль в GitHub с копией этого репозитория, нажимаем на зелуную кнопку **Code** и копируем ссылку.

![](screen/2022-08-14_17-33-07.png)

3. Затем открываем заранее подготовленную папку с помощью программы **Visual Studio Code**, создаем терминал и клонируем этот репозиторий с помощью команды: *git clone ссылка* 

![](screen/2022-08-14_17-56-23.png)

4. После того как в вашей папке появилась новая папка с названием клонируемого репозитория, необходимо в нее перейти с помощью команды: *cd имя папки*

![](screen/2022-08-14_18-05-45.png)

5. Обязательно создаем новую ветку с помощью команды: *git checkout -b имя ветки* и проверяем командой *git branch*

![](screen/2022-08-14_18-21-22.png)

6. Вносим все необхобимые изменения только в этой ветке! Сохраняемся и делаем коммит.

![](screen/2022-08-14_18-41-20.png)

7. Отлично!!! Теперь необходимо сделать пуш на удаленный репозиторий. И в этом поможет команда:*git push -u origin название ветки* 

![](screen/2022-08-14_18-49-15.png)

8. Заходим на свой профиль в GitHub с названием этого репозитория и нажимаем на зеленую кнопку *Compare & pull request*

 ![](screen/2022-08-14_18-52-31.png)

 9. И у нас автоматически открывается новый *pull-request* или запрос на слияние, здесь можно откоректировать данные по неоходимости и нажимаем зеленую кнопку *Create pull request* создаётся новый объект репозитория который доступен только на сервисе *GitHub*.

 ![](screen/2022-08-14_18-59-57.png)

 10. Любой человек участвующий в разработке этого программного обеспечения может зайти в раздел 
 *pull request*, увидеть, что есть открытый *pull request* под нужным названием, зайти в него и посмотреть какие коммиты были сделаны,какие файлы были изменены и посмотреть, что конкретно в них изменилось.Если его что-то не устраивает он может оставить комментарий зайди во вкладку *Conversation* затем *write*, написать комментарий и нажать кнопку *Comment*

 ![](screen/2022-08-14_19-07-44.png)



