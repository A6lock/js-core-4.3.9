# js-core-4.3.9

1) Создал новый аккаунт 
  https://blog.kata.academy/api/users - POST запрос
  
  body:
  
  {
  "user": {
    "username": "AndreyKhyshew",
    "email": "andreykhyshew@gmail.com",
    "password": "123456789"
  }
}
  
2) Залогинился
  https://blog.kata.academy/api/users/login - POST запрос
  
  body:
  
  {
  "user": {
    "email": "andreykhyshew@gmail.com",
    "password": "123456789"
  }
}

3) Получил  данные по user
  https://blog.kata.academy/api/user - GET запрос 
 
 Добавил Authorization, указал токен
 Убрал body
 
 ответ:

{
    "user": {
        "username": "andreykhyshew",
        "email": "andreykhyshew@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzMzA5MWI3M2NmNzA1MWIwMDgyYTg0OSIsInVzZXJuYW1lIjoiYW5kcmV5a2h5c2hldyIsImV4cCI6MTY2OTMxMzcxNSwiaWF0IjoxNjY0MTI5NzE1fQ.ovOTpFd1fiQ9pRTJ6jD5usYlwSbb3spqR-rslMEwFt0"
    }
}

Выгрузил коллекцию из postman, прикрепил json файл
