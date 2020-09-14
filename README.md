
API example in MongoDB and Nodejs

Remember:
* Install mongoDB.
* For testing purposes install mongoDB dev tools so u can use mongoimport and mongoexport in cmd(It's mandatory if u want to test the API).
* The database for testing is in cervezas.json (It's mandatory if u want to test the API)
```
mongoimport --db (Databasename) --collection (Collection name) --drop --file (file dir \cervezas.json) --jsonArray
```

Get into the project dir and install all the project dependencies
```
 npm i
```

Run the api
```
 npm start 
```

If u want to try it out it PostMan agent in desktop or with the web extension u can try, for example:
```
http://localhost:8080/api/cervezas/search?q=moritz
```


This is result API of the explanation of [this web tutorial](https://juanda.gitbooks.io/webapps/content/api/creacion_de_una_api_con_nodejs.html)
