# REST based JSON mock server :clipboard:
This is a REST based JSON mock server to easily add, update, delete and access data from a JSON file.

Tools/Technologies: JavaScript, NodeJS, ExpressJS

## Steps to Run Locally :scroll:
```sh
1. Clone this repository
2. Open the terminal where this repository is downloaded.
3. Make sure you have javascript compiler and npm installed in your system.
4. Now run this command npm install
5. Open the browser with this link http://localhost:3000/post
```

## Full Problem Statement
```sh
Build a REST based JSON mock server to easily add, update, delete and access data from a JSON file.

1. Every data set should have a parent identifier (entity type), which will be used in the GET APIs.
2. Every data set should have an ID (Primary key)
3. ID should be immutable, error needs to be thrown if ID is tried to be mutated.
4. If you make POST, PUT, PATCH or DELETE requests, changes have to be automatically saved to store.json.
5. The store.json file should support multiple entity types.
```
