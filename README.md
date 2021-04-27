# caninnnovation-exam-todolist-api
Todo list server side base on [json-server](https://github.com/typicode/json-server)


## Getting started
Install JSON Server 

```
npm install -g json-server
```

## Running server-side
```
1. json-server db.json --port=PORT_NUMBER
```

## API Document
```
GET    /todolist
POST   /todolist -> JSON Body { title:string }
PUT    /todolist/{id} -> JSON Body { title:string }
DELETE /todolist/{id}
```
