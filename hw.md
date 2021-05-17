Q:What is responsible for defining the routes of the games resource?
A: create_router.js 

Q: What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?
A: Everything in the client folder is responsible for the front end, whereas everything in the server folder is for the back end.

Q: What are the the responsibilities of server.js?
A: This connects the server to the database.

Q:What are the responsibilities of the gamesRouter?
A: gamesRouter takes the collection of games stored in the database and passes it to the createRouter function, which allows basic CRUD on the db.

Q:What process does the the client (front-end) use to communicate with the server?
A: Inside GamesService.js there are fetch functions that link up the front with the back end.

Q:What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs
A: It takes a method, body, and header (specifically for adding a new game).

Q:Which of the games API routes does the front-end application consume (i.e. make requests to)?
A: Not sure...

Q: What are we using the MongoDB Driver for?
A: The driver features an asynchronous API which allows you to access method return values through Promises or specify callbacks to access them when communicating with MongoDB, and it's really cool.