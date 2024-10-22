index html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Simple HTML</title>
</head>
<body>
    <header>
        <h1>Jane Velarde’s Website</h1>
    </header>
    <main>
        <p>This is a simple webpage to demonstrate external CSS styling.</p>
        <button>Click Me!</button>
    </main>
</body>
</html>

style.css
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
    margin: 0;
    padding: 20px;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 15px;
    text-align: center;
}

main {
    margin-top: 20px;
}

button {
    background-color: #008CBA;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
}

button:hover {
    background-color: #005f7f;
}
