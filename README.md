# Postman-Tests
This repo consists of below items which are used for API Testing. 

1. exported collection(.json file) from postman for executing at Command Line
2. List of API Endpoint to be used for the Actions like (GET, POST, PUT, PATCH, DELETE)


List All Posts: https://my-json-server.typicode.com/TejkumarKempaiah/Postman-Tests/posts/

List 1st Post: https://my-json-server.typicode.com/TejkumarKempaiah/Postman-Tests/posts/1/
List 2nd Post: https://my-json-server.typicode.com/TejkumarKempaiah/Postman-Tests/posts/2/

List All Comments: https://my-json-server.typicode.com/TejkumarKempaiah/Postman-Tests/comments/

List 1st Comment: https://my-json-server.typicode.com/TejkumarKempaiah/Postman-Tests/comments/1/
List 1st Comment: https://my-json-server.typicode.com/TejkumarKempaiah/Postman-Tests/comments/2/


Example: 

HTTP Method: GET

Auth Type: No Auth

API ENDPOINT: https://my-json-server.typicode.com/TejkumarKempaiah/Postman-Tests/comments/

Sample Respose: GET https://my-json-server.typicode.com/TejkumarKempaiah/Postman-Tests/comments/

Sample Response: 


[
    {
        "id": 1,
        "body": "some comment",
        "postId": 1
    },
    {
        "id": 2,
        "body": "some comment",
        "postId": 1
    }
]
