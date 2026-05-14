
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Harry Ngeno Portfolio</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial, sans-serif;
        }

        body{
            background:#f4f4f4;
            color:#333;
        }

        header{
            background:#0f172a;
            color:white;
            padding:20px;
            text-align:center;
        }

        header h1{
            font-size:40px;
        }

        header p{
            margin-top:10px;
            font-size:18px;
        }

        nav{
            background:#1e293b;
            padding:15px;
            text-align:center;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:0 15px;
            font-weight:bold;
        }

        section{
            padding:50px 20px;
            max-width:1000px;
            margin:auto;
        }

        .about, .skills, .projects, .contact{
            background:white;
            margin-bottom:20px;
            padding:30px;
            border-radius:10px;
            box-shadow:0 2px 8px rgba(0,0,0,0.1);
        }

        h2{
            margin-bottom:20px;
            color:#0f172a;
        }

        ul{
            list-style:none;
        }

        ul li{
            padding:10px 0;
        }

        .project-card{
            background:#e2e8f0;
            padding:20px;
            margin-top:15px;
            border-radius:8px;
        }

        footer{
            background:#0f172a;
            color:white;
            text-align:center;
            padding:20px;
        }

        .btn{
            display:inline-block;
            margin-top:20px;
            padding:12px 25px;
            background:#2563eb;
            color:white;
            text-decoration:none;
            border-radius:5px;
        }

        .btn:hover{
            background:#1d4ed8;
        }
    </style>
</head>

<body>

    <header>
        <h1>Harry Ngeno</h1>
        <p>Software Engineering Student | Full Stack Developer | Cyber Security Enthusiast</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <div class="about">
            <h2>About Me</h2>
            <p>
                Hello! My name is Harry Ngeno from Kenya.
                I am passionate about software engineering,
                web development, mobile app development,
                and cyber security.
                I enjoy creating modern websites and learning
                new technologies to improve my skills.
            </p>

            <a href="#" class="btn">Download CV</a>
        </div>
    </section>

    <section id="skills">
        <div class="skills">
            <h2>Skills</h2>

            <ul>
                <li>HTML & CSS</li>
                <li>JavaScript</li>
                <li>Flutter & Dart</li>
                <li>Python Programming</li>
                <li>Full Stack Development</li>
                <li>Cyber Security Basics</li>
                <li>Responsive Web Design</li>
            </ul>
        </div>
    </section>

    <section id="projects">
        <div class="projects">
            <h2>Projects</h2>

            <div class="project-card">
                <h3>Portfolio Website</h3>
                <p>
                    Personal portfolio website showcasing my skills,
                    projects, and contact information.
                </p>
            </div>

            <div class="project-card">
                <h3>Business Website</h3>
                <p>
                    Responsive website developed for a local business
                    using HTML, CSS, and JavaScript.
                </p>
            </div>

            <div class="project-card">
                <h3>Flutter Mobile App</h3>
                <p>
                    Mobile application built using Flutter and Dart
                    for Android devices.
                </p>
            </div>

        </div>
    </section>

    <section id="contact">
        <div class="contact">
            <h2>Contact Me</h2>

            <p>Email: harryngeno@example.com</p>
            <p>Phone: +254 700 000000</p>
            <p>Location: Nairobi, Kenya</p>

            <a href="https://linkedin.com" class="btn">
                Visit My LinkedIn
            </a>
        </div>
    </section>

    <footer>
        <p>© 2026 Harry Ngeno Portfolio. All Rights Reserved.</p>
    </footer>

</body>
</html>
