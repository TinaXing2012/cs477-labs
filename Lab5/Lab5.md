# Lab 5 - REST
1. Download the start-up project lesson05-server and lesson05-client projects
    or you create everything from scrtach.
2. Run "npm install" under lesson05-server to get express package installed.
3. Implement the features below inside lesson05-server REST applicaiton
    1. CRUD(create, read, update, delete) books: make sure you use the proper URLs and HTTP Methods 
    2. A book has properties: id, title, ISBN, publishedDate, author
    3. make proper changes in js files to implement the step 1 features
    4. Use Postman to test your REST APIs
4. Implement the features below inside lesson05-client project. This project acts as SPA which make calls to lesson05-server APIs. You must have strong knowledge on JavaScript DOM APIs to complete the tasks. I highly recommand you to do this part if you have time.
    1. Modify index.html, carousel.css to match your design
    2. Write JS code in main.js to implement the feature:
        1. List all books in index.html when open index.html in browser
        2. Click "Submit" button to add a new book with properties: title, ISBN, publishedDate, author (id is auto generated)
        3. Click "Update" button to Edit a book and save to server side
        4. Click "Delete" button to remove a book from server side
