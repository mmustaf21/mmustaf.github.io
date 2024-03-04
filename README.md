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
        <h1>Your Website</h1>
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
        <p>&copy; 2024 Your Website</p>
    </footer>

    <script src="scripts.js"></script>
</body>

</html> body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px;
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
// You can add your JavaScript for interactivity here

// Example: Form validation
function validateForm() {
    var name = document.getElementById('name').value;
    var email = document.getElementById('email').value;

    if (name === '' || email === '') {
        alert('Please fill out all fields.');
        return false;
    }

    return true;
}

// Example: Toggling elements
function toggleVisibility(elementId) {
    var element = document.getElementById(elementId);
    if (element.style.display === 'none' || element.style.display === '') {
        element.style.display = 'block';
    } else {
        element.style.display = 'none';
    }
}

