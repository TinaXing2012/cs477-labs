# Lab 6 - Authentication & Authorization
1. Continue Lab 6 based on Lab 5 to implement the features below for RESTful Application:
    1. Add a login feature which username and password. If logged in successfully, return JWT, otherwise, error message.
    2. For all CRUD operations on Books, they have to be authenticated. If call APIs withou JTW, return 401 unauthorized. With incorrect JWT, return 403 Forbidden. Only with correct, return JSON data
    3. Use Postman test all APIs
3. You can also download the server and client project to continue. Make sure you change all products APIs to books.
