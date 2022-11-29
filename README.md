# QA_project06
API Testing
 ---
 
 Educational project from organization «School 21 and the National Research Tomsk State University, TSU.
 
 <h1>Tasks</h1>
 
| No. | File name | Task | Status |
| --- | ----------------------| --------------------------------------------------------------------------- | ------ |
| **1** |  | **API** | |
| | «API» | Информация об API.                                                          | ✅ |
| **2** |  | **REST. URL** | |
| | «REST-URL»  | Информация о REST и URL, а также о структуре HTTP запроса и ответа. | ✅ |
| **3** |  | **Postman** | |
| | «Postman» | Информация о том, что такое endpoint, pre-request script, body, test. | ✅ |
| | «01.postman_workspace»| Скрин личного кабинета Workspace в Postman. | ✅ |

Для проведения API тестирования в Postman используется API и документация https://reqres.in/.

Представим такой сценарий :
- Пользователь регистрируется на сайте,
- Его данные сохраняются в бэк-енд,
- Затем данные передаются в систему, чтобы пользователь мог сделать log in без повторной регистрации.

| No. | File name | Task | Status |
| --- | ----------------------| --------------------------------------------------------------------------- | ------ |
| **4** | | **API Testing** | |
| | «02.register_user_body» | Создать коллекцию User_registration в Postman. В созданную коллекцию добавить POST запрос Register User. Запустить в Postman запрос Register User (информация для URL запроса и его Body взята с https://reqres.in/) | ✅ |
| | «03.environment» | Добавить сохранение пользователя. Добавить в блок Tests проверку статуса кода. Запустить запрос Register User. Создайте GET запрос Get User с переменной userId. Запустить запрос Get User. Добавить Environment: userId.| ✅ |
| | «04.register_user_test» | Создать POST запрос Login User. В Body cкопируйте данные из запроса Register User. Реализовать последовательность запуска коллекции. Запустить запрос Register User. | ✅ |
| | «05.login_user_test» | Запустить запрос Login User. | ✅ |
| | «06.get_user_test» | Указать в GET запросе Get User, что он последний. | ✅ |
| | «07.all_tests» | Запустить весь набор тестов. | ✅ |
