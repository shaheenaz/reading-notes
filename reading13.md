# read 13
In your own words, describe what each group of status code represents:
100’s =that the header part of the request has been received  (informational)
200’s =They tell the client that its request was accepted (success)
300’s =resource you are requesting isn’t available at the expected location (redirection )
400’s = invalid requests a client sent to a server(client error codes)
500’s =indicate problems with overwhelmed servers or unreachable servers behind proxies(server error codes)
What is a status code 202?client request was valid
What is a status code 308? tells the client to use another URL 
What code would you use if an update didn’t return data to a client?204 No Content
What code would you use if a resource used to exist but no longer does?204 No Content 
What is the ‘Forbidden’ status code? the client is authorized but  has no permissions to access the resource.




Why do we need to pull our MongoDB database string out of our server and put it into our .env? becusse we will use databasr url from atlas
What is middleware?
What does app.use(express.json()) do?let our server accept json insted of a post element

What does the /:id mean in a route? that needs a parameter and thats for setting id
What is the difference beween PUT and PATCH? patch only updates for user entry only  put will update all the informations
How do you make a defalut value in a schema? write default : 
What does a 500 error status code mean? that there is an error in your server 
What is the difference between a status 200 and a status 201? 201 succfully created an object 200 everything was succsfull