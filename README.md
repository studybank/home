<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>School Department - Home</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f0f4f8;
    }

    header {
      background-color: #003366;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      display: flex;
      justify-content: center;
      background-color: #005599;
    }

    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: inline-block;
    }

    nav a:hover {
      background-color: #0077cc;
    }

    .main {
      padding: 30px;
      text-align: center;
    }

    .main h2 {
      color: #003366;
    }

    .cards {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      margin-top: 30px;
    }

    .card {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
      width: 250px;
      margin: 15px;
      padding: 20px;
    }

    .card h3 {
      color: #005599;
    }

    .login-section {
      background-color: #ffffff;
      max-width: 400px;
      margin: 40px auto;
      padding: 30px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      border-radius: 10px;
    }

    .login-section h2 {
      text-align: center;
      color: #003366;
    }

    .login-section input[type="text"],
    .login-section input[type="password"] {
      width: 100%;
      padding: 10px;
      margin: 12px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .login-section input[type="submit"] {
      background-color: #005599;
      color: white;
      border: none;
      padding: 10px;
      width: 100%;
      border-radius: 5px;
      cursor: pointer;
    }

    .login-section input[type="submit"]:hover {
      background-color: #0077cc;
    }

    footer {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to GHSS BAMHORI KALAN School Department</h1>
    <p>Empowering Future Through Quality Education</p>
  </header>

  <nav>
    <a href="https://sites.google.com/view/ghssbamhorikalans/home">Home</a>
    <a href="#">Faculty</a>
    <a href="#">Courses</a>
    <a href="#">Events</a>
    <a href="https://sites.google.com/view/ghssbamhorikalans/contect-us?authuser=0">Contact</a>
  </nav>

  <div class="main">
    <h2>About Our Department</h2>
    <p>We provide academic excellence, skilled faculty, and a vibrant learning environment to shape the future of our students.</p>

    <div class="cards">
      <div class="card">
        <h3>Our Faculty</h3>
        <p>Meet our experienced and dedicated teaching staff.</p>
      </div>
      <div class="card">
        <h3>Courses Offered</h3>
        <p>Explore a wide range of subjects and programs we offer.</p>
      </div>
      <div class="card">
        <h3>Upcoming Events</h3>
        <p>Stay updated with seminars, competitions, and workshops.</p>
      </div>
      <div class="card">
        <h3>Contact Us</h3>
        <p>Get in touch with us for inquiries or support.</p>
      </div>
    </div>
  </div>

  <div class="login-section">
    <h2>Login</h2>
    <form action="#" method="post">
      <input type="text" name="username" placeholder="Enter Username" required>
      <input type="password" name="password" placeholder="Enter Password" required>
      <input type="submit" value="Login">
    </form>
  </div>

  <footer>
    &copy; 2025 XYZ School Department | All Rights Reserved
  </footer>

</body>
</html>
