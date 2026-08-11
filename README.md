<!DOCTYPE html>
<html>
<head>
    <title>Kelvin's Website</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f2f2f2;
            text-align: center;
        }

        header {
            background: #111;
            color: white;
            padding: 30px;
        }

        header h1 {
            margin: 0;
            font-size: 40px;
        }

        header p {
            font-size: 18px;
        }

        .content {
            padding: 50px 20px;
        }

        .card {
            background: white;
            max-width: 600px;
            margin: auto;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.15);
        }

        button {
            background: #111;
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background: #333;
        }

        footer {
            margin-top: 50px;
            padding: 20px;
            background: #111;
            color: white;
        }
    </style>
</head>

<body>

<header>
    <h1>Kelvin's Website</h1>
    <p>Technology • Ideas • Creativity</p>
</header>

<div class="content">

    <div class="card">
        <h2>Welcome 👋</h2>

        <p>
            Welcome to my website. This is my first project
            built with HTML and CSS.
        </p>

        <button onclick="alert('Thanks for visiting!')">
            Click Me
        </button>
    </div>

</div>

<footer>
    © 2026 Kelvin's Website
</footer>

</body>
</html>
