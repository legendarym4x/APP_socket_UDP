## Homework 04

### In this homework assignment, we created a simple web application with routing for two html pages: index.html and message.html.

It was implemented:
     
     Organized work with the form on the `message.html` page.
     
     If a 404 Not Found error occurs, we return the `error.html` page.
     
     Our program runs on port `3000`.
     
     A `Socket server` has been created on port `5000`. We enter data into the form, it enters your web application, which forwards it further for processing using the socket (UDP protocol) of the Socket server. The Socket server translates the received byte string into a dictionary and saves it in json file data.json in the storage folder.
    
     For our web application, we use one `main.py` file.
     
     We start the `HTTP server` and the `Socket server` in different threads.
    
     We also created a `Dockerfile` and run our application as a Docker container.
