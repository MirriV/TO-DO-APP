# TO-DO-APP
  <h1>To-Do App</h1>
    <!-- Buttons for dates start-->
    <div class="d-grid gap-2 d-md-block">
        <button class="btn btn-primary" type="button">Monday</button>
        <button class="btn btn-primary" type="button">Tuesday</button>
        <button class="btn btn-primary" type="button">Wednesday</button>
        <button class="btn btn-primary" type="button">Thursday</button>
        <button class="btn btn-primary" type="button">Friday</button>
        <button class="btn btn-primary" type="button">Saturday</button>
        <button class="btn btn-primary" type="button">Sunday</button>
    </div>
    <!-- Buttons for dates end-->
    <!-- Work List & Personal List cards start-->
    <p>
        <a class="btn btn-primary" data-bs-toggle="collapse" href="#multiCollapseExample1" role="button" aria-expanded="false" aria-controls="multiCollapseExample1">Work To-Do List</a>
        <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target="#multiCollapseExample2" aria-expanded="false" aria-controls="multiCollapseExample2">Personal To-Do List</button>
        <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target=".multi-collapse" aria-expanded="false" aria-controls="multiCollapseExample1 multiCollapseExample2">All To-Do Lists</button>
      </p>
     
      <div class="row">
        <div class="col">
          <div class="collapse multi-collapse" id="multiCollapseExample1">
            <div class="card card-body">
            <h1>Work</h1>
              <li>task</li>
              <li>task</li>
              <li>task</li>
              <li>task</li>
              <li>task</li>
              <li>task</li>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="collapse multi-collapse" id="multiCollapseExample2">
            <div class="card card-body">
                <h1>Personal</h1>
                <li>task</li>
                <li>task</li>
                <li>task</li>
                <li>task</li>
                <li>task</li>
                <li>task</li>
            </div>
          </div>
        </div>
      </div>
    
    <!-- Work List & Personal List cards end-->

    <!--Completed Tasks section starts here-->
    <div class="card text-center">
        
        <div class="card-body">
          <h5 class="card-title">Completed Tasks</h5>
          <p class="card-text">
            <li> Task Done</li>
            <li> Task Done</li>
            <li> Task Done</li>
            <li> Task Done</li>
            <li> Task Done</li>
          </p>
      
        </div>
        
      </div>
      <!--Completed Tasks section ends here-->

      SECOND ATTEMPT:
      <!doctype html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>To-Do App</title>
  <link href="/CSS/stylesheet.css" rel="stylesheet" type="text/css">
  <!--<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">-->

</head>

<body>
<div class="heading">
  <h1>My To Do List</h1>
</div>
 <div class="form">
  <form>
    <input type="text" id="newTask" name="newTask">
    <button type="button">New Task</button>
  </form>
</div>

  <script src="/JS/index.js"></script>
  <!--<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>-->
 
</body>

</html>