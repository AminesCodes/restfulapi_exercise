# Todos API

### Root https://fsw62-todos-api.herokuapp.com/api

### Resources
* users
* todos

### Endpoints

#### Users
| Method | Endpoint           |
|--------|--------------------|
| `GET`  | `/users`           |
| `GET`  | `/users/<username>` |
| `POST`  | `/users/signup`   |


* Fill in the blanks above :arrow_up: 

#### Todos
| Method   | Endpoint           | Possible Query Params |
|----------|--------------------|-----------------------|
| `GET`    | `/todos`           | `owner=<username>`, `completed=<true\|false> `|
| `POST`   | `/todos`           ||
| `GET`    | `/todos/<todo-id>` ||
| `PUT`    | `/todos/<todo-id>` ||
| `PATCH`  | `/todos/<todo-id>` ||
| `DELETE` | `/todos/<todo-id>` ||

* Fill in the blanks above :arrow_up: 

## Tasks
1. Try out all the requests that are possible with this API. For all the possible requests Create a list like the following.
Separate requests by a long line of underscores.
    * **Request**: METHOD - ENDPOINT
    * **Body** (if applicable POST/PUT/PATCH)
    ```json
      {
        "owner": "alejo4373",
        "text": "1st Todo"
      }
    ```
    * **Response**:
    ```json
    {
      "userId": 1,
      "id": 1,
      "title": "delectus aut autem",
      "completed": false
    }
    ```
    * **What does it do?**: EXPLAIN WHAT THE REQUEST DID/DO IN PLAIN ENGLISH

2. Find as much status codes as possible. I will tell you how many there are by the end.

### Bonuses
1. Take a look at the next lesson. To learn how to make make network requests with Javascript
Since you previously had build a simple Todos APP with HTML try to connect that app to this
API so that todos you enter in the page are save to the API. Marking a todo as complete or uncompleted
should work.
2. Find the easter egg.
