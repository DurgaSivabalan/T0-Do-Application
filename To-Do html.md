To-Do App

Html code for to-do App

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>To-Do App</title>
  <link rel="stylesheet" href="todo.css">
</head>
<body>
  <div class="todo-container">
    <h1>To-Do List</h1>
    <form id="todo-form">
      <input type="text" id="todo-input" placeholder="Enter a new task">
      <button type="submit">Add</button>
    </form>
    <ul id="todo-list"></ul>
  </div>
  <script src="todo.js"></script>
</body>
</html>