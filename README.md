<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Srimukesh Rajkumar | Portfolio</title>
    <style>
        /* Resetting default margins and padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        section {
            padding: 20px;
            margin: 20px 0;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        form label {
            display: block;
            margin-bottom: 5px;
        }

        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        form button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        form button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Srimukesh Rajkumar's Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- About Me Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>Hello! My name is <strong>Srimukesh Rajkumar</strong>, and I’m a passionate web developer. I have a <strong>B.Tech in Computer Science and Engineering</strong> and specialize in front-end development with experience in HTML, CSS, JavaScript, and React.</p>
        <p>I love solving complex problems and building efficient, user-friendly applications. In my free time, I enjoy reading tech blogs, learning new tools, and working on personal projects.</p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>My Projects</h2>
        <ul>
            <li>
                <a href="https://github.com/srimukesh/credit-card-detection" target="_blank"><strong>Credit Card Fraud Detection Using ML</strong></a>
                <p>This project detects fraudulent credit card transactions using machine learning algorithms.</p>
            </li>
            <li>
                <a href="https://github.com/srimukesh/blockchain-medical-data" target="_blank"><strong>Blockchain for Secure Medical Data</strong></a>
                <p>This project uses blockchain technology to store medical data securely and transparently.</p>
            </li>
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:srimukeshsri2002@gmail.com">srimukeshsri2002@gmail.com</a></p>
        <p>Phone: <a href="tel:+16385915743">6385915743</a></p>
        <p>LinkedIn: <a href="https://linkedin.com/in/srimukesh" target="_blank">LinkedIn Profile</a></p>
        
        <!-- Contact Form -->
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br><br>

            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br><br>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Srimukesh Rajkumar. All rights reserved.</p>
    </footer>
</body>
</html>
