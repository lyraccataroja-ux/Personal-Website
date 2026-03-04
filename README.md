<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Queen Angel Quiogue | Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Roboto', sans-serif; background: #f2f4f8; color: #333; }

        header {
            background: linear-gradient(135deg, #6c63ff, #3a3dff);
            color: white;
            text-align: center;
            padding: 4rem 2rem;
            clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%);
        }
        header h1 { font-size: 3rem; margin-bottom: 1rem; }
        header p { font-size: 1.2rem; }

        nav {
            display: flex;
            justify-content: center;
            gap: 2rem;
            background-color: #fff;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav a {
            color: #333;
            text-decoration: none;
            font-weight: 700;
            padding: 1rem;
            transition: color 0.3s;
        }
        nav a:hover { color: #6c63ff; }

        section { padding: 5rem 2rem; max-width: 1200px; margin: auto; }
        section h2 { text-align: center; font-size: 2.5rem; margin-bottom: 2rem; color: #6c63ff; }

        #about p { max-width: 800px; margin: auto; font-size: 1.1rem; line-height: 1.8; text-align: center; }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        .project {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.08);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .project:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 25px rgba(0,0,0,0.15);
        }
        .project h3 { margin-bottom: 1rem; color: #3a3dff; }
        .project p { line-height: 1.6; font-size: 1rem; }

        #contact p { text-align: center; margin-bottom: 1rem; font-size: 1.1rem; }
        #contact a { color: #6c63ff; text-decoration: none; font-weight: bold; }
        #contact a:hover { text-decoration: underline; }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 2rem 1rem;
            margin-top: 2rem;
        }

        /* Buttons for projects (optional) */
        .btn {
            display: inline-block;
            padding: 0.5rem 1rem;
            background: #6c63ff;
            color: white;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 1rem;
            transition: background 0.3s;
        }
        .btn:hover { background: #3a3dff; }

    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Queen Angel Quiogue</h1>
        <p>Passionate Web Developer | Designer | Problem Solver</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>Hello! My name is <strong>Queen Angel Quiogue</strong>. I am a creative and enthusiastic web developer who loves turning ideas into functional and visually appealing digital solutions. I am passionate about learning new technologies and building projects that combine creativity and practicality. My goal is to create websites and applications that leave a meaningful impact in the digital world.</p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>My Projects</h2>
        <div class="projects">
            <div class="project">
                <h3>Portfolio Website</h3>
                <p>A personal portfolio website showcasing my skills, projects, and contact information. Built with HTML, CSS, and JavaScript for interactive components.</p>
                <a href="#" class="btn">View Project</a>
            </div>
            <div class="project">
                <h3>Weather App</h3>
                <p>An interactive weather application that displays current weather information using API data. Built with HTML, CSS, JavaScript, and OpenWeatherMap API.</p>
                <a href="#" class="btn">View Project</a>
            </div>
            <div class="project">
                <h3>Task Manager</h3>
                <p>A responsive to-do list web app to manage daily tasks efficiently. Implemented with HTML, CSS, and JavaScript local storage.</p>
                <a href="#" class="btn">View Project</a>
            </div>
            <div class="project">
                <h3>Online Store Mockup</h3>
                <p>A demo e-commerce website design including product listing, shopping cart UI, and checkout mockup. Built with HTML, CSS, and JavaScript.</p>
                <a href="#" class="btn">View Project</a>
            </div>
            <div class="project">
                <h3>Blog Website</h3>
                <p>A blog platform design with responsive layout, allowing users to view posts and articles. Styled using CSS Grid and Flexbox.</p>
                <a href="#" class="btn">View Project</a>
            </div>
            <div class="project">
                <h3>Calculator App</h3>
                <p>A functional calculator web app that performs basic arithmetic operations. Built using HTML, CSS, and JavaScript.</p>
                <a href="#" class="btn">View Project</a>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>My Skills</h2>
        <p style="text-align:center;">I have developed a variety of skills through learning and building projects. Here are some of my main technical skills:</p>
        <div class="projects">
            <div class="project">
                <h3>HTML & CSS</h3>
                <p>Experienced in creating responsive web layouts using modern HTML5 and CSS3 techniques including Flexbox, Grid, and animations.</p>
            </div>
            <div class="project">
                <h3>JavaScript</h3>
                <p>Proficient in JavaScript for interactive front-end features, DOM manipulation, and API integration.</p>
            </div>
            <div class="project">
                <h3>UI/UX Design</h3>
                <p>Ability to design clean, user-friendly interfaces that provide excellent user experiences across devices.</p>
            </div>
            <div class="project">
                <h3>Version Control</h3>
                <p>Familiar with Git and GitHub for version control, collaboration, and project management.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Feel free to reach out via email: <a href="mailto:queenangel@example.com">queenangel@example.com</a></p>
        <p>Or connect with me on social media:</p>
        <p>
            <a href="#">LinkedIn</a> | 
            <a href="#">GitHub</a> | 
            <a href="#">Twitter</a>
        </p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Queen Angel Quiogue. All rights reserved.</p>
    </footer>

</body>
</html>
