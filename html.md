<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic HTML with Animation</title>
    <style>
        body {
            background-color: pink;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        h1 {
            animation: fadeIn 2s ease-in-out;
        }

        footer {
            position: fixed;
            bottom: 0;
            width: 100%;
            background-color: lightgrey;
            padding: 10px;
        }

        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Page!</h1>
    </header>

    <main>
        <p>This is a simple HTML page with a pink background.</p>
    </main>

    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>
</body>
</html>

