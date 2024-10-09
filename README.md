<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Richard Onyekwere's Portfolio">
    <title>Richard Onyekwere's Portfolio</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f2f5;
            color: #333;
        }
        header {
            background-color: #007BFF;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
            letter-spacing: 1px;
        }
        section {
            max-width: 1100px;
            margin: 40px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        .introduction {
            text-align: center;
            margin-bottom: 50px;
        }
        .introduction p {
            font-size: 1.1em;
            margin: 10px 0;
            color: #555;
        }
        h2 {
            color: #007BFF;
            font-size: 2em;
            border-bottom: 2px solid #007BFF;
            display: inline-block;
            padding-bottom: 10px;
        }
        .project-list {
            list-style-type: none;
            padding: 0;
        }
        .project-list li {
            background-color: #f9f9f9;
            margin-bottom: 20px;
            padding: 20px;
            border-left: 5px solid #007BFF;
            border-radius: 5px;
            transition: transform 0.2s;
        }
        .project-list li:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.1);
        }
        .project-list li h3 {
            margin: 0 0 10px;
            font-size: 1.7em;
            color: #007BFF;
        }
        .project-list li p {
            margin: 5px 0 10px;
            font-size: 1.1em;
            color: #444;
        }
        .project-list li .skills {
            font-style: italic;
            color: #777;
        }
        footer {
            background-color: #007BFF;
            color: white;
            text-align: center;
            padding: 20px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        footer a {
            color: white;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <header>
        <h1>Richard Onyekwere's Portfolio</h1>
    </header>

    <section>
        <div class="introduction">
            <h2>About Me</h2>
            <p>Hi, I'm Richard Onyekwere, an IT Engineer with over 6 years of experience in systems administration, IT operations, and enterprise applications support. I'm passionate about enhancing system efficiency and delivering innovative solutions.</p>
        </div>

        <div class="projects">
            <h2>Highlighted Projects</h2>
            <ul class="project-list">
                <li>
                    <h3>JavaScript Animation</h3>
                    <p>Developed an interactive JavaScript animation using the Canvas API at James Cook University, allowing users to control the movement of an animated animal on a canvas.</p>
                    <p class="skills"><strong>Skills:</strong> JavaScript, Canvas API</p>
                </li>
                <li>
                    <h3>Hotel Booking Web Application</h3>
                    <p>Designed a web application for Turbot House Hotel as part of my MIT capstone project. This system enables customers to book rooms online, securely handling transactions and backend operations.</p>
                    <p class="skills"><strong>Skills:</strong> PHP, HTML, CSS, APIs, MySQL, Apache, LAMP stack, secure coding</p>
                </li>
                <li>
                    <h3>Active Directory Home Lab</h3>
                    <p>Built a home lab running Active Directory on Windows Server 2019 and Windows 10 clients. The project involved configuring DNS, DHCP, and enhancing my networking skills.</p>
                    <p class="skills"><strong>Skills:</strong> Active Directory, Windows Server, Networking (DHCP, DNS)</p>
                </li>
            </ul>
        </div>
    </section>

    <footer>
        <p>Contact: +61 422 136 780 | <a href="mailto:onyekwererichardug@gmail.com">onyekwererichardug@gmail.com</a></p>
        <p><a href="https://www.linkedin.com/in/richardonyekwere">LinkedIn</a></p>
    </footer>

</body>
</html>
