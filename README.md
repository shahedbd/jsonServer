# json Server
Get a full fake REST API with zero coding in less than 30 seconds (seriously)

### Installation
* NodeJS: https://nodejs.org/en/
* IDE/Code Editor: VS Code: https://code.visualstudio.com/

```
npm install -g json-server
```
### Check Version
$ node -v
### Format Code
* ⇧⌥F


### Create a db.json file with some data
```json
{
  "posts": [
    { "id": 1, "title": "json-server", "author": "typicode" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}
```

### Start JSON Server
* > cd db.json dir
```
json-server --watch db.json
```
### Now if you go to 
* http://localhost:3000/posts/1, you'll get
```
{ "id": 1, "title": "json-server", "author": "typicode" }
```


### Plural routes
* GET    http://localhost:3000/posts
* GET    http://localhost:3000/posts/1 
* POST   http://localhost:3000/posts
* PUT    http://localhost:3000/posts/1
* PATCH  http://localhost:3000/posts/1
* DELETE http://localhost:3000/posts/1


### Postman collection
* https://www.getpostman.com/collections/d6871944ae760fcd2b82

### Ref
* https://github.com/typicode/json-server
