body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: linear-gradient(135deg, #00000070, #00000079, #0000009f, #90928b, #000000) no-repeat center center fixed;
    height: 100vh;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  h1 {
    color: #ffffff;
    font-size: 3em;
    text-align: center;
    text-shadow: 0 0 15px #000000;
  }
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background:linear-gradient(135deg, #00000070, #00000079, #0000009f, #90928b, #000000) no-repeat center center fixed;

    height: 25vh;
    margin: 100;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  h1 {
    color: #ffffff;
    font-size: 3em;
    text-align: center;
    text-shadow: 0 0 15px #000000;
  }
[Uploading index.css…]()* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: url(https://t3.ftcdn.net/jpg/02/45/14/30/240_F_245143087_fskpabOKPaDYQdFcu6JjPSKURgjcF1il.jpg) no-repeat center center fixed;
    background-size: cover;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  

  .container {
    backdrop-filter: blur(8px);
    background: rgba(255, 255, 255, 0.178);
    padding: 2rem;
    border-radius: 15px;
    box-shadow: 0 8px 32px rgba(0, 0, 0, 0.25);
    width: 100%;
    max-width: 400px;
  }
  
  .title {
    font-size: 2rem;
   
    text-align: center;
    margin-bottom: 0.5rem;
    font-family: 'Georgia', serif;
  }
  
 

    .subtitle {
      text-align: center;
      
      font-style: italic;
      margin-bottom: 1.5rem;
    }
    
   

  
 
  .login-form {
    display: flex;
    flex-direction: column;
  }
  
  .input-group {
    margin-bottom: 1rem;
  }
  
  .input-group label {
    display: block;
    color: #ddd;
    margin-bottom: 0.3rem;
  }
  
  .input-group input {
    width: 100%;
    padding: 0.6rem;
    border: none;
    border-radius: 5px;
    background-color: rgba(255, 255, 255, 0.9);
  }
  

  .btn {
    background-color: #6441a5;
    color: white;
    padding: 0.7rem;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background 0.3s ease;
  }
  
  .btn:hover {
    background-color: #3c2073;
  }
  
  .register-link {
    color: #c9b500;
    text-align: center;
    margin-top: 1rem;
  }
  
  .register-link a {
    color: #fff;
    text-decoration: underline;
  }
  

  @media (max-width: 500px) {
    .container {
      margin: 1rem;
    }
  }
  [Uploading index.html…]()!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sufi Culture | Login</title>
  <link rel="stylesheet" href="./index.css" />
</head>
<body>
  <div class="container">
    <div class="login-box">
      <h1 class="title">Sufi Culture</h1>
      <p class="subtitle">Enter the world of mysticism</p>
      <form action="#" method="POST" class="login-form">
        <div class="input-group">
          <label for="username">Username</label>
          <input type="text" id="username" name="username" required />
        </div>
        <div class="input-group">
          <label for="password">Password</label>
          <input type="password" id="password" name="password" required />
        </div>
        <button type="submit" class="btn"><a href="./2.html">Login</a></button>
        <p class="register-link">Don't have an account? <a href="#">Register</a></p>
      </form>
    </div>
  </div>
</body>
</html>

[Uploading 2.html…]()<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>sufi</title><h1>WELCOME TO OUR SPIRITUAL WORLD</h1><link rel="stylesheet" href="./2.css">
</head>
<body>

</body>
</html>

