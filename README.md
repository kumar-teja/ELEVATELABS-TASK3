Initialize the project
Create a new folder and run npm init -y to generate a package.json file.

Install Express
Run npm install express to add Express as a dependency.

Create the main server file
Create a file (e.g., index.js) to write your server code.

Set up Express and middleware
Import Express, create an app instance, and use express.json() to handle JSON data.

Create a mock data array
Define a temporary array to store your data (acts like a simple database).

Implement the Read (GET) route
Create a route to fetch and return all items from your data array.

Implement the Create (POST) route
Create a route to add a new item to your data array.

Implement the Update (PUT) route
Create a route to update an existing item based on its ID.

Implement the Delete (DELETE) route
Create a route to remove an item from the array by ID.

Start the server
Use app.listen() to start your server on a specific port (e.g., 3000).

