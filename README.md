/* Global Styling */
body {
    font-family: 'Segoe UI', Arial, sans-serif;
    margin: 0;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
    scroll-behavior: smooth;
}

/* Header */
header {
    background: #0d1b2a;
    color: #fff;
    padding: 15px 0 10px;
    text-align: center;
}
.logo {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
}
.logo-img {
    width: 35px;
    height: 35px;
}
.tagline {
    font-size: 0.9em;
    margin-top: 5px;
}
nav {
    margin-top: 10px;
}
nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    margin: 0 15px;
    transition: color 0.3s ease;
}
nav a:hover {
    color: #00b4d8;
}

/* Hero Section */
.hero {
    background: #14213d;
    color: white;
    padding: 50px 20px;
}
.hero-content {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    gap: 30px;
}
.hero-text {
    flex: 1 1 300px;
    max-width: 500px;
}
.hero-photo img {
    width: 220px;
    height: 220px;
    object-fit: cover;
    border-radius: 50%;
    border: 4px solid #00b4d8;
    box-shadow: 0 4px 15px rgba(0,0,0,0.3);
}
.hero .btn {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 20px;
    background: #00b4d8;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: background 0.3s ease;
}
.hero .btn:hover {
    background: #0077b6;
}

/* Container */
.container {
    width: 85%;
    max-width: 1100px;
    margin: auto;
    padding: 20px;
}
section {
    margin-bottom: 40px;
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
}
h2 {
    color: #0d1b2a;
}

/* Skills */
.skills {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
}
.skill-card {
    background: #edf6f9;
    padding: 15px;
    border-radius: 6px;
    text-align: center;
    font-weight: bold;
    transition: transform 0.3s ease, background 0.3s ease;
}
.skill-card:hover {
    transform: translateY(-5px);
    background: #d0eff3;
}

/* Contact Links */
.contact-links a {
    color: #00b4d8;
    margin: 0 10px;
    text-decoration: none;
    font-weight: bold;
}
.contact-links a:hover {
    text-decoration: underline;
}

/* Footer */
footer {
    background: #0d1b2a;
    color: #fff;
    text-align: center;
    padding: 15px;
}

/* Animations */
.fade-in {
    opacity: 0;
    transform: translateY(20px);
    animation: fadeUp 1s ease forwards;
}
.delay-1 { animation-delay: 0.3s; }
.delay-2 { animation-delay: 0.6s; }
.delay-3 { animation-delay: 0.9s; }
.delay-4 { animation-delay: 1.2s; }
.delay-5 { animation-delay: 1.5s; }
.delay-6 { animation-delay: 1.8s; }
.delay-7 { animation-delay: 2.1s; }

@keyframes fadeUp {
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* Mobile Responsive */
@media (max-width: 768px) {
    .hero-content {
        flex-direction: column;
    }
}
/* Global Styling */
body {
    font-family: 'Segoe UI', Arial, sans-serif;
    margin: 0;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
    scroll-behavior: smooth;
}

/* Header */
header {
    background: #0d1b2a;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}
nav {
    margin-top: 10px;
}
nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    margin: 0 15px;
    transition: color 0.3s ease;
}
nav a:hover {
    color: #00b4d8;
}

/* Hero Section */
.hero {
    background: url('https://images.unsplash.com/photo-1581093448794-5c3d0402d5f0?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
    color: white;
    padding: 80px 20px;
    text-align: center;
}
.hero .btn {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 20px;
    background: #00b4d8;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: background 0.3s ease;
}
.hero .btn:hover {
    background: #0077b6;
}

/* Container */
.container {
    width: 85%;
    max-width: 1100px;
    margin: auto;
    padding: 20px;
}
section {
    margin-bottom: 40px;
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
}
h2 {
    color: #0d1b2a;
}

/* Skills */
.skills {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
}
.skill-card {
    background: #edf6f9;
    padding: 15px;
    border-radius: 6px;
    text-align: center;
    font-weight: bold;
    transition: transform 0.3s ease, background 0.3s ease;
}
.skill-card:hover {
    transform: translateY(-5px);
    background: #d0eff3;
}

/* Contact Links */
.contact-links a {
    color: #00b4d8;
    margin: 0 10px;
    text-decoration: none;
    font-weight: bold;
}
.contact-links a:hover {
    text-decoration: underline;
}

/* Footer */
footer {
    background: #0d1b2a;
    color: #fff;
    text-align: center;
    padding: 15px;
}

/* Animations */
.fade-in {
    opacity: 0;
    transform: translateY(20px);
    animation: fadeUp 1s ease forwards;
}
.delay-1 { animation-delay: 0.3s; }
.delay-2 { animation-delay: 0.6s; }
.delay-3 { animation-delay: 0.9s; }
.delay-4 { animation-delay: 1.2s; }
.delay-5 { animation-delay: 1.5s; }
.delay-6 { animation-delay: 1.8s; }
.delay-7 { animation-delay: 2.1s; }

@keyframes fadeUp {
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portfolio of Jessie L. Mina - BS Criminology Graduate, aspiring public servant, and justice advocate.">
    <title>Jessie L. Mina | Criminology Graduate</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1 class="fade-in">Jessie L. Mina</h1>
        <p class="fade-in delay-1">BS Criminology Graduate | Aspiring Public Servant</p>
        <nav>
            <a href="#about">About</a>
            <a href="#experience">Experience</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero fade-in delay-2">
        <h1>Justice. Service. Integrity.</h1>
        <p>Committed to protecting communities and upholding the rule of law.</p>
        <a href="#contact" class="btn">Get in Touch</a>
    </section>

    <div class="container">
        <section id="about" class="fade-in delay-3">
            <h2>About Me</h2>
            <p>Hello! I’m Jessie L. Mina, a graduate of the Bachelor of Science in Criminology from the University of the Cordilleras. My academic journey has equipped me with knowledge in criminal law, forensic science, and community policing. I’m passionate about justice, crime prevention, and contributing to a safer society.</p>
            <p>When I’m not studying criminal procedures or forensic evidence, you’ll find me playing basketball — a sport that has taught me teamwork, discipline, and resilience.</p>
        </section>

        <section id="experience" class="fade-in delay-4">
            <h2>Experience</h2>
            <ul>
                <li><strong>Intern - Philippine National Police (PNP)</strong> | Assisted in filing case reports, evidence documentation, and preliminary investigations.</li>
                <li><strong>Volunteer - Community Watch Program</strong> | Helped in organizing crime prevention awareness campaigns in local communities.</li>
            </ul>
        </section>

        <section id="skills" class="fade-in delay-5">
            <h2>Skills</h2>
            <div class="skills">
                <div class="skill-card">Forensic Analysis</div>
                <div class="skill-card">Criminal Profiling</div>
                <div class="skill-card">Incident Report Writing</div>
                <div class="skill-card">Conflict Resolution</div>
                <div class="skill-card">Public Speaking</div>
                <div class="skill-card">Basketball Team Leadership</div>
            </div>
        </section>

        <section id="projects" class="fade-in delay-6">
            <h2>Projects & Research</h2>
            <ul>
                <li><strong>Fingerprint Analysis Report</strong> — Conducted a detailed examination of latent prints for a mock investigation.</li>
                <li><strong>Community Crime Prevention Study</strong> — Researched and presented strategies for reducing youth-related crimes.</li>
            </ul>
        </section>

        <section id="contact" class="fade-in delay-7">
            <h2>Contact Me</h2>
            <p>If you’d like to connect, feel free to reach out via:</p>
            <div class="contact-links">
                <a href="mailto:jessie.mina@example.com">Email</a> |
                <a href="https://www.linkedin.com/" target="_blank">LinkedIn</a> |
                <a href="https://github.com/jexxghost" target="_blank">GitHub</a>
            </div>
        </section>
    </div>

    <footer>
        <p>© 2025 Jessie L. Mina. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portfolio of Jessie L. Mina - BS Criminology Graduate, aspiring public servant, and justice advocate.">
    <title>Jessie L. Mina | Criminology Graduate</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #0d1b2a;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #00b4d8;
        }
        .hero {
            background: url('https://images.unsplash.com/photo-1581093448794-5c3d0402d5f0?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
            color: white;
            padding: 80px 20px;
            text-align: center;
        }
        .hero h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        .container {
            width: 85%;
            max-width: 1100px;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        section {
            margin-bottom: 40px;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
        }
        h2 {
            color: #0d1b2a;
        }
        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }
        .skill-card {
            background: #edf6f9;
            padding: 15px;
            border-radius: 6px;
            text-align: center;
        }
        footer {
            background: #0d1b2a;
            color: #fff;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
        .contact-links a {
            color: #00b4d8;
            margin: 0 10px;
            text-decoration: none;
        }
        .contact-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Jessie L. Mina</h1>
        <p>BS Criminology Graduate | Aspiring Public Servant</p>
        <nav>
            <a href="#about">About</a>
            <a href="#experience">Experience</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h1>Justice. Service. Integrity.</h1>
        <p>Committed to protecting communities and upholding the rule of law.</p>
    </section>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! I’m Jessie L. Mina, a graduate of the Bachelor of Science in Criminology from the University of the Cordilleras. My academic journey has equipped me with knowledge in criminal law, forensic science, and community policing. I’m passionate about justice, crime prevention, and contributing to a safer society.</p>
            <p>When I’m not studying criminal procedures or forensic evidence, you’ll find me playing basketball — a sport that has taught me teamwork, discipline, and resilience.</p>
        </section>

        <section id="experience">
            <h2>Experience</h2>
            <ul>
                <li><strong>Intern - Philippine National Police (PNP)</strong> | Assisted in filing case reports, evidence documentation, and preliminary investigations.</li>
                <li><strong>Volunteer - Community Watch Program</strong> | Helped in organizing crime prevention awareness campaigns in local communities.</li>
            </ul>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <div class="skills">
                <div class="skill-card">Forensic Analysis</div>
                <div class="skill-card">Criminal Profiling</div>
                <div class="skill-card">Incident Report Writing</div>
                <div class="skill-card">Conflict Resolution</div>
                <div class="skill-card">Public Speaking</div>
                <div class="skill-card">Basketball Team Leadership</div>
            </div>
        </section>

        <section id="projects">
            <h2>Projects & Research</h2>
            <ul>
                <li><strong>Fingerprint Analysis Report</strong> — Conducted a detailed examination of latent prints for a mock investigation.</li>
                <li><strong>Community Crime Prevention Study</strong> — Researched and presented strategies for reducing youth-related crimes.</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact Me</h2>
            <p>If you’d like to connect, feel free to reach out via:</p>
            <div class="contact-links">
                <a href="mailto:jessie.mina@example.com">Email</a> |
                <a href="https://www.linkedin.com/" target="_blank">LinkedIn</a> |
                <a href="https://github.com/jexxghost" target="_blank">GitHub</a>
            </div>
        </section>
    </div>

    <footer>
        <p>© 2025 Jessie L. Mina. All rights reserved.</p>
    </footer>
</body>
</html>
