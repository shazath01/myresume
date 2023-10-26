<!DOCTYPE html>
<html>
<head>
    <title>Shazath - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 2rem 0;
            position: relative;
        }

        .header-content h1 {
            font-size: 2.5rem;
        }

        .profile-picture {
            width: 100px;
            height: 100px;
            border-radius: 75%; 
            object-fit: cover;
            position: absolute;
            top: 75px;
            left: 75px;
        }

        nav {
            background-color: #333;
            color: #fff;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
        }

        .section-content {
            background-color: #fff;
            padding: 2rem;
            margin: 1rem;
            border-radius: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: justify;
        }

        .download-button {
            background-color: #333;
            color: #fff;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 20px;
            display: inline-block;
            margin-top: 10px;
            align-self: center;
        }

        .download-button:hover {
            background-color: #555;
        }

        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #333;
            color: #fff;
        }

        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <img src="./mypic.jpeg" alt="Your Profile Picture" class="profile-picture">
            <h1>SHAZATH AHAMED M</h1>
            <p>Shazam Tech Solutions</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#resume">Resume</a></li>
        </ul>
    </nav>

    <section id="about">
        <div class="section-content">
            <h2>About Me</h2>
            <p>I'm a Data Mining expert and Technology enthusiast who is passionate about helping organizations field to develop their data and create secure and sophisticated online environments. I'm driven by the desire to put technology to work for the greater good and empower individuals and businesses to benefit from the digital revolution. With over 4 years of experience in the field, I'm dedicated to staying up to date with the latest trends and innovations in the Data Mining landscape. I'm also committed to helping others learn more about the importance of online security and how to stay safe online..</p>
        </div>
    </section>

    <section id="education">
        <div class="section-content">
            <h2>Education</h2>
            <p>SSLC - Louis Levail Matricuation Higher Secondary School</p>
            <p>HSC - Louis Levail Matricuation Higher Secondary School</p>
            <p>UG - Syed Hameeda Arts & Science College [Anna University]</p>
        </div>
    </section>

    <section id="skills">
        <div class="section-content">
            <h2>Skills</h2>
            <ul>
                <li>Data Mining</li>
                <li>CyberSecurity</li>
                <li>Internet of Things</li>
                <li>Cloud Computing</li>
            </ul>
        </div>
    </section>

    <section id="projects">
        <div class="section-content">
            <h2>Projects</h2>
            <ul>
                <li>AI Based alternator control system</a></li>
                <li>Cloud Security IBM</a></li>
                <li>Virtual Guide for Travel & Tourism</li>
            </ul>
        </div>
    </section>

    <section id="resume">
    
        <div class="section-content">
            <center>
            <h2>Resume</h2>
            <a href="https://drive.google.com/file/d/19xnirmHRbBDm3gUeJ9ybjrO9IPYyP2cM/view?usp=drivesdk" target="_blank" class="download-button">Download CV</a>
        </center>
        </div>
        
    </section>

    <footer>
        <p>&copy; 2023 Shazath Ahamed M</p>
    </footer>

    <script>
        // Smooth scrolling to section when clicking on navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();

                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);

                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>
