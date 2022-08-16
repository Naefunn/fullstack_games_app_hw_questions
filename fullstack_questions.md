What is responsible for defining the routes of the games resource?

The createRouter.js file


What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible 
for?

Client is for front end - how the page looks to the user and server is for backend - handling requests to the server and responding with that information


What are the the responsibilities of server.js?

To set up express and to listen to the port/ server to use restful routes to interact with the database


What are the responsibilities of the gamesRouter?

To set up a generic router so we can delegate routes for our games array add addtional ones later on

What process does the the client (front-end) use to communicate with the server?

HTTP


What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs

an init options object such as method, headers, body and mode



Which of the games API routes does the front-end application consume (i.e. make requests to)?



What are we using the MongoDB Driver for?

To allow the games app to connect to the database and interact with it
