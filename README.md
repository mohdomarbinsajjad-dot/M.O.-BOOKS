<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MO Books</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* आप CSS यहीं भी जोड़ सकते हो, लेकिन अभी हम अलग फाइल रखेंगे */
    </style>
</head>
<body>
    <header>
        <h1>MO Books</h1>
        <p>अपनी पसंद की किताबें अपलोड करें</p>
    </header>
    <main>
        <section>
            <h2>अपलोड करें</h2>
            <form action="#" method="POST" enctype="multipart/form-data">
                <input type="file" name="book" accept="application/pdf" required>
                <button type="submit">अपलोड करें</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2026 MO Books. सभी अधिकार सुरक्षित।</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    margin: 0;
    padding: 0;
}

header {
    background-color: #d8cfc4;
    color: #333;
    text-align: center;
    padding: 2rem;
}

h1 {
    margin: 0;
    font-size: 2.5rem;
}

main {
    padding: 2rem;
    text-align: center;
}

form {
    background-color: white;
    padding: 2rem;
    display: inline-block;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

button {
    margin-top: 1rem;
    padding: 0.5rem 1rem;
    background-color: #333;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #555;
}

footer {
    text-align: center;
    padding: 1rem;
    background-color: #d8cfc4;
    color: #333;
    font-size: 0.9rem;
}