<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Developer Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        h1 {
            font-size: 2.5rem;
            color: #333;
            text-align: center;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }
        .profile-pic {
            display: block;
            margin: 0 auto 20px;
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        .skills, .projects {
            margin-bottom: 20px;
        }
        .skills ul, .projects ul {
            list-style: none;
            padding: 0;
        }
        .skills li, .projects li {
            background: #f0f0f5;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }
        a {
            color: #007acc;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="container">
        <img src="profile-pic.jpg" alt="Profile Picture" class="profile-pic">
        <h1>Hello, I'm a Web Developer!</h1>
        <p>
            With 7 years of experience in web development, I specialize in building high-quality websites and applications. 
            I'm passionate about writing clean, efficient code and continuously improving my skills through projects, blogging, 
            and coding challenges.
        </p>

        <div class="skills">
            <h2>Skills</h2>
            <ul>
                <li>HTML, CSS, JavaScript</li>
                <li>React, Angular, Vue.js</li>
                <li>Node.js, Express</li>
                <li>Python, Django, Flask</li>
                <li>MySQL, MongoDB</li>
                <li>Version Control (Git/GitHub)</li>
            </ul>
        </div>

        <div class="projects">
            <h2>Projects</h2>
            <ul>
                <li><a href="https://github.com/yourusername/project1">Project 1 - E-commerce Website</a></li>
                <li><a href="https://github.com/yourusername/project2">Project 2 - Social Media App</a></li>
                <li><a href="https://github.com/yourusername/project3">Project 3 - Portfolio Website</a></li>
            </ul>
        </div>

        <p>
            You can find more of my work on <a href="https://github.com/yourusername">GitHub</a> or connect with me on 
            <a href="https://www.linkedin.com/in/yourusername">LinkedIn</a>.
        </p>
    </div>

</body>
</html>
