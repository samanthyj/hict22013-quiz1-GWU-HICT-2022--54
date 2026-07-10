<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Colourful Box Layout</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      text-align: center;
    }

    header {
      background-color: blue;
      color: white;
      padding: 20px;
      font-size: 24px;
      font-weight: bold;
    }

    .container {
      display: flex;
      gap: 20px;
      padding: 20px;
    }

    .box {
      flex: 1;
      padding: 50px 0;
      font-size: 20px;
      font-weight: bold;
      color: black;
    }

    .box1 {
      background-color: red;
    }

    .box2 {
      background-color: green;
      color: white;
    }

    .box3 {
      background-color: yellow;
    }

    footer {
      background-color: grey;
      color: white;
      padding: 20px;
      font-size: 20px;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>My Header</header>

  <div class="container">
    <div class="box box1">Box 1</div>
    <div class="box box2">Box 2</div>
    <div class="box box3">Box 3</div>
  </div>

  <footer>My Footer</footer>

</body>
</html>