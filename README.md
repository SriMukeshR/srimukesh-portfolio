<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Srimukesh Rajkumar | Portfolio</title>
    <style>
        /* CSS Styles */
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
            margin: 0;
            padding: 0;
        }

        header {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem;
        }

        header h1 {
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
            color: white;
            text-decoration: none;
        }

        section {
            padding: 20px;
            margin: 20px 0;
            background-color: white;
            border-radius: 8px;
        }

        section h2 {
            margin-bottom: 10px;
        }

        section ul {
            list-style: none;
        }

        section ul li {
            margin-bottom: 10px;
        }

        footer {
            background: #333;
            color: white;
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
        <h1>Welcome to the Portfolio of <strong>Srimukesh Rajkumar</strong></h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- About Me Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>Hello! My name is <strong>Srimukesh Rajkumar</strong>, and I’m a passionate web developer with a love for creating interactive and visually appealing websites. I have a <strong>B.Tech in Computer Science and Engineering</strong>, and I specialize in front-end development with experience in HTML, CSS, JavaScript, and frameworks like React.</p>
        <p>I enjoy solving problems, learning new technologies, and collaborating with others to bring ideas to life. When I’m not coding, I enjoy reading tech blogs, exploring new tools, and working on personal projects to sharpen my skills.</p>
        <p>Feel free to explore my portfolio and reach out if you’d like to collaborate!</p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>My Projects</h2>
        <ul>
            <li>
                <a href="https://github.com/srimukesh/credit-card-detection" target="_blank"><strong>Credit Card Fraud Detection Using Machine Learning</strong></a>
                <p>This project focuses on detecting fraudulent credit card transactions using machine learning algorithms.</p>
                <p><strong>Technologies Used:</strong> Python, Scikit-Learn, Pandas, Matplotlib, Jupyter Notebook</p>
            </li>
            <li>
                <a href="https://github.com/srimukesh/blockchain-medical-data" target="_blank"><strong>Leveraging Blockchain for Secure and Transparent Medical Data</strong></a>
                <p>This project uses blockchain technology to store medical data securely and transparently using Ethereum and smart contracts.</p>
                <p><strong>Technologies Used:</strong> Ethereum, Solidity, Web3.js, JavaScript</p>
            </li>
        </ul>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills & Technologies</h2>
        <h3>Technical Skills:</h3>
        <ul>
            <li>Programming Languages: JavaScript, Python, Java</li>
            <li>Web Development: HTML, CSS, React, Angular</li>
            <li>Tools: VS Code, Git, Docker</li>
            <li>Databases: MySQL, MongoDB</li>
        </ul>
        <h3>Certifications:</h3>
        <ul>
            <li>Web Development Certificate (Coursera)</li>
            <li>Data Science and Machine Learning Certificate (edX)</li>
        </ul>
        <h3>Soft Skills:</h3>
        <ul>
            <li>Problem Solving</li>
            <li>Communication</li>
            <li>Teamwork</li>
        </ul>
    </section>

    <!-- Resume Section -->
    <section id="resume">
        <h2>Resume</h2>
        <p>You can download my resume <a href="srimukesh_resume.pdf" download>here</a>.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:srimukeshsri2002@gmail.com">srimukeshsri2002@gmail.com</a></p>
        <p>Phone: <a href="tel:+16385915743">6385915743</a></p>
        <p>LinkedIn: <a href="https://linkedin.com/in/srimukesh" target="_blank">LinkedIn Profile</a></p>
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
