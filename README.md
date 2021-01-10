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

## Different API'S
```sh
** GET REQUEST
1. http://localhost:3000/post (GET Request) - This api is used to show the data that is present in JSON file

2. http://localhost:3000/:ID  (GET Request) - This api is used to show the particular json data which has id = ID

3. http://localhost:3000/?title=title1&author=CIQ (GET Request) - 
                                              This api is used to filter the json data which has title = title1 and author = CIQ

4. http://localhost:3000/?_sort=views&_order=asc (GET Request) - 
                                              This api is used to sort the json data according to the _sort parameter ascending

5. http://localhost:3000/?_sort=views&_order=des (GET Request) - 
                                              This api is used to sort the json data according to the _sort parameter descending

** Post Request
1. http://localhost:3000/post (POST Request) - This api is used to insert data in the JSON File. We have to give input in postman as
                                               BODY -> RAW -> JSON -> DATA 

** Patch Request
1. http://localhost:3000/post/:ID (PATCH Request) - This api is used to make changes in JSON data. We have to insert ID and change data in 
                                               BODY -> RAW -> JSON -> DATA
                   
** Delete Request                   
1. http://localhost:3000/post/:ID (Delete Request) - This api is used to delete the data from JSON file which has ID = ID                                                                    
```
