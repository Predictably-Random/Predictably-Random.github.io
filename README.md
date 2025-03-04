# Predictably-Random.github.io
title: Predictably Random's homepage
description: Bookmark this to keep an eye on my project updates!
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Awesome Website</title>
  <style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    /* Global Styles */
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      margin-top: 10px;
    }
    nav ul li {
      margin: 0 15px;
    }
    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    main {
      max-width: 800px;
      margin: 20px auto;
      padding: 20px;
      background-color: #fff;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    button {
      background-color: #333;
      color: #fff;
      border: none;
      padding: 10px 20px;
      cursor: pointer;
      margin-top: 20px;
    }
    button:hover {
      background-color: #555;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Website</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h2>About Me</h2>
    <p>
      This is a sample website template. Replace this content with your own
      la la la 
    </p>
    <button id="clickMe">Click Me!</button>
  </main>

  <footer>
    <p>&copy; 2025 My Website</p>
  </footer>

  <script>
    // Simple JavaScript for button interaction
    document.getElementById("clickMe").addEventListener("click", function () {
      alert("Hello, welcome to my website!");
    });
  </script>
</body>
</html>
