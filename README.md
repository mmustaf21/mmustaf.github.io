<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Mohamed's Website</title>
</head>

<body>
    <header>
        <h1>Mohamed's Website</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Content specific to each page goes here -->
    </main>

    <footer>
        <p>&copy; 2024 Mohamed's Website</p>
    </footer>

    <script src="scripts.js"></script>
</body>

</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
}

header {
    background-color: #333;
    color: white;
    padding: 15px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: white;
    font-weight: bold;
    font-size: 18px;
}

main {
    padding: 20px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}

/* Add additional styling as needed */

/* User-friendly design */
form {
    max-width: 400px;
    margin: 20px auto;
    padding: 15px;
    background-color: white;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

label {
    display: block;
    margin-bottom: 8px;
}

input {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    box-sizing: border-box;
}

button {
    background-color: #333;
    color: white;
    padding: 10px 15px;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #555;
}

#hiddenContent {
    background-color: #f8f8f8;
    padding: 15px;
    margin-top: 20px;
    display: none;
}
