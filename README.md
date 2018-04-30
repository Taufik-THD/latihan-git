# My Rest API App

Demo app with basic REST API.

## REST API

List of basic routes:

|           Route        | HTTP|      Description     |
|------------------------|-----|----------------------|
| /api/hello?name={name} | GET | Print hello, {name} !|

List of user routes:

|           Route        |  HTTP  |      Description     |
|------------------------|--------|----------------------|
|        /api/users      | GET    |   Get all the users  |
|        /api/users/:id  | GET    |   Get all the users  |
|        /api/users      | POST   |   Get all the users  |
|        /api/users/:id  | DELETE |   Get all the users  |
|        /api/users/:id  | PUT    |   Get all the users  |
|        /api/users/:id  | PATCH  |   Get all the users  |

List of filter routes:

|             Route           |   HTTP  |      Description     |
|-----------------------------|---------|----------------------|
|   /api/users?name="{name}"  |   GET   |   Get all the users  |
|   /api/users?name="{na}"    |   GET   |   Get all the users  |
