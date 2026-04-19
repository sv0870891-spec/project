# project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel = "stylesheet"href = "web.css">
</head>
<body>
    <div class="container">
        <div class="todo-app">
            <h2>To-Do List<img src="https://cdn-icons-png.flaticon.com/512/6286/6286665.png"></h2>
            <div class = "row">
                <input type="text" id="input-box" placeholder="Add your text">
                <button onclick="addTask()">Add</button>
            </div>
            <ul id="list-container">
                <!--<li class="checked"> task1</li>
                <li>task2</li>
                <li>task3</li>-->
            </ul>
        </div>
    </div>
    <script src="web.js"></script>
</body>
</html>
