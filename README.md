# Lionsheartsboxrec
<!DOCTYPE html>
<html>
<head>
  <meta charset=“utf-8”>
  <title>My Boxing Tracker</title>
  <link rel=“stylesheet” href=“style.css”>
</head>
<body>
  <header><h1>Latest Bouts</h1></header>
  <div id=“bouts”></div>
  <script src=“script.js”></script>
</body>
</html>
Style.css
Script.js
<!DOCTYPE html>
<html>
<head>
  <title>Boxing Records</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      padding: 20px;
    }

    nav {
      margin-bottom: 20px;
    }

    nav a {
      margin-right: 15px;
      text-decoration: none;
      color: blue;
    }

    h1 {
      color: #222;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background: white;
    }

    th, td {
      border: 1px solid black;
      padding: 10px;
      text-align: center;
    }

    th {
      background-color: #ddd;
    }
  </style>
</head>
<body>

  <!— Navigation Menu —>
  <nav>
    <a href=“index.html”>Home</a>
    <a href=“boxers.html”>Boxers</a>
    <a href=“rankings.html”>Rankings</a>
  </nav>

  <h1>Boxing Records</h1>

  <table>
    <tr>
      <th>Name</th>
      <th>Wins</th>
      <th>Losses</th>
      <th>Draws</th>
      <th>Weight Class</th>
    </tr>
    <tr>
      <td>Amari</td>
      <td>20</td>
      <td>2</td>
      <td>1</td>
      <td>Welterweight</td>
    </tr>
    <tr>
      <td>Jr</td>
      <td>15</td>
      <td>5</td>
      <td>0</td>
      <td>Middleweight</td>
    </tr>
    <tr>
      <td>Addonis</td>
      <td>25</td>
      <td>0</td>
      <td>0</td>
      <td>Heavyweight</td>
    </tr>
    <tr>
      <td>Armani</td>
      <td>10</td>
      <td>3</td>
      <td>2</td>
      <td>Lightweight</td>
    </tr>
  </table>

</body>
</html>