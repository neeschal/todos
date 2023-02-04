## Description

Simple todo app.

## Database

It uses postgresql database to store the todos.

# Create a todo

When the client sends a post request to the url(http://server:3000/todos) with the todo body it will store that todo body in the database.

# Read a todo

When the client sends a get request to the url(http://server:3000/todos) send all todos stored in the database as json.

# Update a todo by id

When the client sends a patch request to the url(http://server:3000/todos:id) with the todo body it will update the body of a matching todo contains the id in the parameter of the url with the received body in the database.

# Delete a todo by id

When the client sends a delete request to the url(http://server:3000/todos:id) it will delete the matching todo contains the id in the parameter of the url from the database.
