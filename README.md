# KB-Fitness-
Fitness Tips
<!-- HTML + CSS (paste this in CodePen HTML box) -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>KB Fitness</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background: #111;
      color: #fff;
    }

    header {
      background: url('https://images.unsplash.com/photo-1571019613914-85f342c1d1e9') center/cover no-repeat;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      text-align: center;
      padding: 20px;
    }

    header h1 {
      font-size: 3em;
      font-weight: bold;
      margin-bottom: 10px;
      color: #ffcc00;
    }

    header p {
      font-size: 18px;
      max-width: 600px;
      margin-bottom: 20px;
    }

    .btn {
      background: #ffcc00;
      color: #000;
      padding: 12px 25px;
      border: none;
      border-radius: 30px;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: #ffaa00;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
      text-align: center;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 30px;
      margin-top: 40px;
    }

    .feature-box {
      background: #222;
      padding: 30px;
      border-radius: 15px;
      border: 1px solid #333;
    }

    footer {
      background: #000;
      color: #888;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>

  <header>
    <h1>KB FITNESS</h1>
    <p>Your personal fitness companion — track, train, and transform your body</p>
    <button class="btn">Join Now</button>
  </header>

  <section>
    <h2>Why Choose Us?</h2>
    <div class="features">
      <div class="feature-box">
        <h3>Workout Routines</h3>
        <p>Choose from hundreds of exercises and custom plans.</p>
      </div>
      <div class="feature-box">
        <h3>Calorie Tracker</h3>
        <p>Log your meals and track daily calorie intake easily.</p>
      </div>
      <div class="feature-box">
        <h3>Progress Reports</h3>
        <p>Visualize your strength, weight, and health improvements.</p>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 KB FITNESS | Designed by Kashyap Bhai
  </footer>

</body>
</html>
