<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Chalo Pani Puri Khate Hai</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Pacifico&family=Poppins:wght@400;600&display=swap');

    body {
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
      text-align: center;
      color: #fff;
      background: url('https://i.imgur.com/pG6e2u5.jpg') no-repeat center center fixed;
      background-size: cover;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .container {
      background-color: rgba(0, 0, 0, 0.7);
      padding: 30px;
      border-radius: 20px;
      max-width: 480px;
      margin: 20px;
      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.4);
    }

    h1 {
      font-size: 2.2rem;
      margin-bottom: 15px;
    }

    p {
      font-size: 1.1rem;
      margin-bottom: 20px;
    }

    .btn {
      margin: 10px 8px;
      padding: 12px 20px;
      background-color: #ffffff;
      color: #ff4e50;
      font-weight: bold;
      text-decoration: none;
      border-radius: 10px;
      display: inline-block;
      transition: background 0.3s ease;
    }

    .btn:hover {
      background-color: #ffe7e7;
    }

    .special-offer {
      font-family: 'Pacifico', cursive;
      color: #ffff00;
      background: #ff0066;
      padding: 10px 15px;
      border-radius: 10px;
      font-size: 1.4rem;
      margin-bottom: 25px;
      display: inline-block;
      animation: pop 1s ease infinite alternate;
    }

    @keyframes pop {
      from { transform: scale(1); }
      to { transform: scale(1.05); }
    }

    @media (max-width: 500px) {
      .container {
        padding: 20px;
      }
      h1 {
        font-size: 1.7rem;
      }
      .special-offer {
        font-size: 1.2rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Chalo Pani Puri Khate Hai 😋</h1>
    <p>Taste ka Naya Tadka!<br>Thanks for scanning the QR code.</p>

    <div class="special-offer" id="reward-text">
      🎉 Checking your luck...
    </div>

    <a class="btn" href="https://wa.me/91XXXXXXXXXX" target="_blank">Order on WhatsApp</a>
    <a class="btn" href="https://instagram.com/yourpage" target="_blank">Follow on Instagram</a>
  </div>

  <script>
    const randomPuris = Math.floor(Math.random() * 8) + 1;
    document.getElementById('reward-text').textContent =
      `🎉 Congratulations! You got ${randomPuris} pani puri FREE!`;
  </script>
</body>
</html>
