To-Do App

Css code for to-do app

body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #f7f7f7;
  }
  
  .todo-container {
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    width: 300px;
  }
  
  h1 {
    margin: 0 0 20px;
    text-align: center;
  }
  
  form {
    display: flex;
  }
  
  input[type="text"] {
    flex: 1;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
    margin-right: 10px;
  }
  
  button {
    padding: 10px 20px;
    border: none;
    background-color: #5cb85c;
    color: white;
    border-radius: 5px;
    cursor: pointer;
  }
  
  button:hover {
    background-color: #4cae4c;
  }
  
  ul {
    list-style: none;
    padding: 0;
    margin: 20px 0 0;
  }
  
  li {
    background: #f9f9f9;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
    margin-bottom: 10px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  li button {
    background: none;
    border: none;
    color: #d9534f;
    cursor: pointer;
  }
  
  li button:hover {
    color: #c9302c;
  }