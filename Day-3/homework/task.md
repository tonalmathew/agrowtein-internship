# Homework Task: Interactive To-Do List

Create a simple interactive to-do list using HTML and JavaScript. This project will help you practice working with variables, functions, DOM manipulation, and event handling.

### Requirements:

1. Create an HTML file with a form to add new tasks and a list to display tasks.
2. Use JavaScript to add functionality to the to-do list.
3. Implement the following features:

    - Add new tasks to the list
    - Mark tasks as completed (by clicking on them)
    - Delete tasks from the list
    - Display the total number of tasks and completed tasks


Here's a starting point for your project:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive To-Do List</title>
    <style>
        .completed {
            text-decoration: line-through;
            color: gray;
        }
    </style>
</head>
<body>
    <h1>My To-Do List</h1>
    <form id="todo-form">
        <input type="text" id="todo-input" placeholder="Enter a new task" required>
        <button type="submit">Add Task</button>
    </form>
    <ul id="todo-list"></ul>
    <p id="todo-stats"></p>

    <script>
        // Your JavaScript code here
        
        // 1. Select necessary DOM elements
        
        // 2. Create an array to store tasks
        
        // 3. Function to add a new task
        
        // 4. Function to render the task list
        
        // 5. Function to toggle task completion
        
        // 6. Function to delete a task
        
        // 7. Function to update stats
        
        // 8. Event listener for form submission
        
        // 9. Event delegation for task list (clicking to complete or delete)
        
    </script>
</body>
</html>
```

Your task is to complete the JavaScript code to make the to-do list functional. Here are some hints to help you get started:

1. Use `document.getElementById()` to select DOM elements.
2. Create an array to store the tasks. Each task can be an object with properties like `id`, `text`, and `completed`.
3. Use `addEventListener()` to handle form submission and clicks on the task list.
4. Use `innerHTML` or `createElement()` to add new elements to the DOM.
5. Use array methods like `push()`, `filter()`, and `map()` to manipulate the tasks array.
6. Remember to update the stats whenever the task list changes.


### Bonus Challenges:

1. Add the ability to edit existing tasks.
2. Implement local storage to save tasks between page reloads.
3. Add categories or priority levels to tasks.
4. Create a filter to show only completed or uncompleted tasks.


### Submission Instructions:

1. Complete the JavaScript code in the provided HTML file.
2. Test your to-do list to ensure all features are working correctly.
3. Add comments to your code explaining what each part does.
4. Save your file as `todo-list.html`.
5. Submit your completed HTML file before the next class.
