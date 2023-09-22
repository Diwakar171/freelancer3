# freelancer3
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Freelancer Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p>Freelance Expertise</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#testimonials">Testimonials</a></li>
            <li><a href="#contact">Contact</a></li>
            <!DOCTYPE html>
            <html lang="en">
            <head>
                <meta charset="UTF-8">
                <meta name="viewport" content="width=device-width, initial-scale=1.0">
                <title>Freelancer Portfolio</title>
                <link rel="stylesheet" href="styles.css">
            </head>
            <body>
                <header>
                    <h1>Your Name</h1>
                    <p>Freelance Expertise</p>
                </header>

                <nav>
                    <ul>
                        <li><a href="#about">About</a></li>
                        <li><a href="#portfolio">Portfolio</a></li>
                        <li><a href="#testimonials">Testimonials</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </nav>


                
body, h1, h2, p, ul, li, form, button {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

header h1 {
    font-size: 36px;
}

header p {
    font-size: 18px;
}

header img {
    max-width: 100%;
    border-radius: 50%;
    margin-top: 20px;
}

nav ul {
    list-style: none;
}

nav li {
    display: inline;
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
    font-size: 16px;
}

section {
    padding: 40px;
    background-color: #fff;
    margin: 20px;
    box-shadow: 0 0 10px rgba(0.0, 0.0, 0.0, 0.1);
}

section h2 {
    font-size: 24px;
    margin-bottom: 20px;
}

form input,
form textarea,
form button {
    display: block;
    width: 100%;
    margin-bottom: 20px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background-color: #333;
    color: #fff;
    border: none;
    padding: 15px;
    font-weight: bold;
    cursor: pointer;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: #fff;
    font-size: 14px;
}

/* Media queries for responsiveness */
@media (max-width: 768px) {
    header {
        padding: 10px;
    }

    header h1 {
        font-size: 28px;
    }

    header p {
        font-size: 14px;
    }

    nav li {
        margin-right: 10px;
    }

    section {
        padding: 20px;
        margin: 10px;
    }

    form button {
        padding: 10px;
    }
}

                <section id="about">
                    <h2>About Me</h2>
                    <p>Your brief introduction and skills should go here.</p>
                </section>

                <section id="portfolio">
                    <h2>Portfolio</h2>
                    <!-- Your portfolio items go here (e.g., images and descriptions) -->
                </section>

                <section id="testimonials">
                    <h2>Testimonials</h2>
                    <!-- Client testimonials go here -->
                </section>

                <section id="contact">
                    <h2>Contact Me</h2>
                    <form action="contact.php" method="POST">
                        <label for="name">Name:</label>
                        <input type="text" id="name" name="name" required><br>

                        <label for="email">Email:</label>
                        <input type="email" id="email" name="email" required><br>

                        <label for="message">Message:</label>
                        <textarea id="message" name="message" required></textarea><br>

                        <button type="submit">Send</button>
                    </form>
                </section>

                <footer>
                    <p>&copy; 2023 Your Name</p>
                </footer>
            </body>
        </html>
        </ul>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Your brief introduction and skills should go here.</p>
    </section>

    <section id="portfolio">
        <h2>Portfolio</h2>
        <!-- Your portfolio items go here (e.g., images and descriptions) -->
    </section>

    <section id="testimonials">
        <h2>Testimonials</h2>
        <!-- Client testimonials go here -->
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form action="contact.php" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea><br>

            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Your Name</p>
    </footer>
    
</body>
</html>
