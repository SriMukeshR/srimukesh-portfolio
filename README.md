# srimukesh-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hi, I'm [Your Name], a passionate developer specializing in [Your Skills].</p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <ul>
                <li><a href="https://github.com/yourusername/project1" target="_blank">Project 1</a></li>
                <li><a href="https://github.com/yourusername/project2" target="_blank">Project 2</a></li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact Me</h2>
            <p>Email: <a href="mailto:your.email@example.com">your.email@example.com</a></p>
            <p>LinkedIn: <a href="https://linkedin.com/in/yourusername" target="_blank">LinkedIn Profile</a></p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>

#css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 20px;
}

section {
    margin: 20px 0;
}

footer {
    text-align: center;
    padding: 10px;
    background: #333;
    color: #fff;
}
