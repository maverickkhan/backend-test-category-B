# backend test category B

Instructions: Please complete the following tasks to the best of your ability. You may use any online resources or documentation that you find necessary. Feel free to ask any clarifying questions if needed.

Task 1: Create a simple Express server

Task 2: Create a basic API for a todo list

Create a Node.js script that sets up a basic API for a todo list using Express. The API should have the following routes:

-   `GET /todos`: Return a JSON array of todo objects.
-   `POST /todos`: Create a new todo item. The request body should contain a JSON object with the todo's title and description.
-   `PUT /todos/:id`: Update an existing todo item by its ID. The request body should contain a JSON object with the updated todo's title and description.
-   `DELETE /todos/:id`: Delete a todo item by its ID.

Use an in-memory data structure (e.g., an array) to store the todo items.

Task 3: Handle errors and implement error middleware

Enhance your Express server to handle errors gracefully. Implement error middleware that catches any unhandled errors and returns appropriate error responses to clients.

Task 4: Implement input validation

Add input validation to your todo list API. Validate the request body for the `POST /todos` and `PUT /todos/:id` routes to ensure that the required fields are present and have the correct data types. Return appropriate error responses if the input is invalid.
