<!DOCTYPE html>
<html>
<head>
  <title>Wattpad Style Login Form</title>
  
  <style>

     
    body {
      font-family: Arial, sans-serif;
      background-color: white;
    }
 
   
    .box {
      width: 220px;
      height: 300px;
      margin: 0 auto;
      margin-top: 100px;
      bañckground-color:white;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
      border:3px solid black;
      font-family:sans-serif;
      color:black;
      background-image:url(Wattpad.jpg);
      background-size:cover;
      text-align: center;
      
    }
    
    .box h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    
    .box input[type="text"],
    .box input[type="password"]{
      width: 95%;
      padding: 10px;
      border: 0px solid #ccc;
      border-radius: 3px;
      margin-bottom: 15px;
     
    }
    
    .box input[type="submit"] {
      width: 100%;
      padding: 10px;
      background-color: darkorange;
      color: black;
      border: none;
      border-radius: 10px;
      cursor: pointer; 
    }
 
  </style>
</head>
<body>
  <div class="box">
    <h2>Login</h2>
    
    <form>
      <input type="text" placeholder="Username" required>
      <input type="password" placeholder="Password" required>
      <input type="submit" value="Log In">
    </form>
  </div>
</body>
</html>
