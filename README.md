<!DOCTYPE html>
<html>
<head>
  <title>Solo RP Whitelist</title>

  <style>
    body {
      margin: 0;
      font-family: Arial;
      background: url("https://images.unsplash.com/photo-1508057198894-247b23fe5ade") no-repeat center/cover;
      color: white;
    }

    body::before {
      content: "";
      position: fixed;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.7);
    }

    h1 {
      text-align: center;
      margin-top: 40px;
      position: relative;
      z-index: 1;
      color: red;
    }

    form {
      position: relative;
      z-index: 1;
      background: rgba(0,0,0,0.6);
      padding: 20px;
      width: 300px;
      margin: 50px auto;
      border-radius: 10px;
    }

    input, textarea {
      width: 90%;
      margin: 10px;
      padding: 8px;
      border: none;
      border-radius: 5px;
    }

    button {
      padding: 10px;
      background: red;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>

<body>

<h1>Solo RP Whitelist 🔥</h1>

<form action="send.php" method="POST">
  <input type="text" name="name" placeholder="Name RP" required><br>
  <input type="number" name="age" placeholder="Age RP" required><br>
  <textarea name="story" placeholder="Story RP..." required></textarea><br>
  <button type="submit">Send</button>
</form>

</body>
</html>
