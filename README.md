React + Redux  

Фронт часть мегахакатона. Задание - написать web приложение по парсингу новостей с различных ресурсов в одном месте.  
  
Функционал: 
  1) страница Admin (доступ только у пользователей с правами главного редактора):
     - добавление пользователя
     - проверка прав доступа, если у пользователя нет статуса главный редактор, будет переброшен на другую страницу
     - получение данных с серверв
     - просмотр списка пользователей
     - изменение  email / password / прав доступа / аватарки любого пользователя
     - изменение списка сайтов и тегов для каждого сайта. Главный редактор отбирает сайты и теги, по которым на странице user будут отображаться новости.
  3) страница user (доступ у всех залогиненных пользователей):
     - отобранные главным редактором новости и теги можно дополнительно изменять, создавая фильтр под себя. Фильтр хранится в браузере пользователя.
     - поиск новостей по тексту
     - отображение новостей + пагинация + выбор желаемого количества отображаемых новостей
     - добавление новостей в избранное
  5) страница login:
     - собственно, ввод почты и пароля, проверка данных на сервере, если удачно то редирект на страницу user
