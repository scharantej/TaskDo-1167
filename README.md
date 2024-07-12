## Flask Application Design for Todo List

### HTML Files

- **index.html**: Main page of the application, where users can view, add, and delete tasks.
- **about.html**: Simple page describing the application and its purpose.

### Routes

- **route /**: Redirects to index.html
- **route /index**: Displays the index page
- **route /about**: Displays the about page
- **route /add_task**: Adds a new task to the database and redirects to index page.
- **route /delete_task**: Deletes the task with given `id` from the database, then redirects to index page.