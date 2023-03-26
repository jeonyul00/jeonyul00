<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>My GitHub Page</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      background-color: #f9f9f9;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #000;
      color: #fff;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px;
    }

    #logo {
      font-size: 24px;
      font-weight: bold;
      margin: 0 10px;
    }

    nav {
      display: flex;
      align-items: center;
      justify-content: flex-end;
      margin: 0 10px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 10px;
      transition: all 0.3s ease;
    }

    nav a:hover {
      color: #b1b1b1;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 30px;
    }

    .card {
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
      margin-bottom: 30px;
      overflow: hidden;
    }

    .card img {
      max-width: 100%;
    }

    .card-body {
      padding: 20px;
    }

    .card-title {
      font-size: 24px;
      font-weight: bold;
      margin: 0;
      color: #000;
    }

    .card-text {
      color: #444;
      margin-top: 10px;
      line-height: 1.5;
    }

    .btn {
      background-color: #000;
      color: #fff;
      border: none;
      padding: 10px 20px;
      border-radius: 4px;
      font-size: 16px;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .btn:hover {
      background-color: #b1b1b1;
    }

    footer {
      background-color: #000;
      color: #fff;
      height: 50px;
      display: flex;
      align-items: center;
      justify-content: center;
    }
  </style>
</head>
<body>
  <header>
    <div id="logo">My GitHub Page</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <div class="container">
    <div class="card">
      <img src="https://picsum.photos/800/400" alt="Card Image">
      <div class="card-body">
        <h2 class="card-title">Card Title</h2>
        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris in risus ac risus lobortis tincidunt.</p>
        <button class="btn">Learn More</button>
      </div>
    </div>
 <div class="card">
      <img src="https://picsum.photos/800/400" alt="Card Image">
      <div class="card-body">
        <h2 class="card-title">Card Title</h2>
        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris in risus ac risus lobortis tincidunt.</p>
        <button class="btn">Learn More</button>
      </div>
    </div>
  </div>
  <footer>
    © My GitHub Page
  </footer>
</body>
</html>
