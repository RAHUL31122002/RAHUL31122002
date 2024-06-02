git clone https://github.com/rahul31122002/wheel-deal.git
cd wheel-deal
wheel-deal/
├── index.html
├── styles.css
├── script.js
├── images/
└── README.md
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wheel Deal</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Wheel Deal</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Welcome to Wheel Deal</h2>
            <p>Your one-stop destination for vehicle deals.</p>
        </section>
        <section id="about">
            <h2>About Us</h2>
            <p>We offer the best deals on wheels.</p>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                <button type="submit">Submit</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Wheel Deal. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1rem;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 1rem;
}

section {
    margin-bottom: 2rem;
}
document.addEventListener('DOMContentLoaded', function() {
    // Add any JavaScript functionality here
});

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    position: fixed;
    width: 100%;
    bottom: 0;
}

