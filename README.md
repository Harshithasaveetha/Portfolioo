# Ex01 Portfolio
## Date:31/10/2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Harshitha D | Portfolio</title>

    <link rel="stylesheet" href="style.css">

    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Roboto+Mono&display=swap" rel="stylesheet">

</head>

<body>

    <!-- NAVBAR -->
    <header>
        <nav class="navbar">

            <h2 class="logo">Portfolio.</h2>

            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#certifications">Certifications</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>

        </nav>
    </header>


    <!-- HOME -->
    <section class="hero" id="home">

        <div class="hero-content">

            <h1>Hi, I'm <span>Harshitha D</span></h1>

            <h3>Computer Science Engineering Student</h3>

            <p>
                Passionate about software development,
                Java programming, problem-solving and
                Artificial Intelligence. I enjoy learning
                new technologies and building practical
                solutions.
            </p>

            <div class="buttons">
                <a href="#projects" class="btn">View My Work</a>
                <a href="#contact" class="btn outline">Contact Me</a>
            </div>

        </div>

        <div class="profile">
            <img src="c:\Users\admin\OneDrive\画像\harshu.jpeg" alt="My Profile">
        </div>

    </section>


    <!-- ABOUT -->
    <section id="about">

        <h2>About <span>Me</span></h2>

        <p>
            I am a Computer Science and Engineering student
            interested in software development and emerging
            technologies.

            I am currently strengthening my programming skills
            in Java, Data Structures and Algorithms, Database
            Management Systems and Artificial Intelligence.

            My goal is to become a skilled software engineer
            and contribute to real-world technology solutions.
        </p>

    </section>


    <!-- SKILLS -->
    <section id="skills">

        <h2>Technical <span>Skills</span></h2>

        <div class="skill-container">

            <div class="skill">Java</div>
            <div class="skill">Python</div>
            <div class="skill">C Programming</div>
            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">SQL</div>
            <div class="skill">Data Structures</div>
            <div class="skill">OOP</div>
            <div class="skill">DBMS</div>
            <div class="skill">Git & GitHub</div>

        </div>

    </section>


    <!-- PROJECTS -->
    <section id="projects">

        <h2>My <span>Projects</span></h2>

        <div class="project-container">

            <div class="project-card">
                <h3>Portfolio Website</h3>
                <p>
                    A responsive personal portfolio website
                    developed using HTML and CSS to showcase
                    my skills and projects.
                </p>
                <p class="tech">HTML | CSS</p>
                <a href="#">View Project →</a>
            </div>

            <div class="project-card">
                <h3>AI-Based Prediction System</h3>
                <p>
                    An academic project exploring machine
                    learning techniques for predictive
                    analysis.
                </p>
                <p class="tech">Python | Machine Learning</p>
                <a href="#">View Project →</a>
            </div>

            <div class="project-card">
                <h3>Java Application</h3>
                <p>
                    A Java-based application demonstrating
                    object-oriented programming and
                    problem-solving concepts.
                </p>
                <p class="tech">Java | OOP | SQL</p>
                <a href="#">View Project →</a>
            </div>

        </div>

    </section>


    <!-- EXPERIENCE -->
    <section id="experience">

        <h2>Internship & <span>Experience</span></h2>

        <div class="project-card">
            <h3>Full Stack Development Intern</h3>
            <h4>VelanDev Solutions Pvt. Ltd.</h4>
            <p>July 2025</p>
            <p>
                Gained practical exposure to full-stack
                development and worked on an Intern
                Management System.
            </p>
        </div>

    </section>


    <!-- CERTIFICATIONS -->
    <section id="certifications">

        <h2>Certifications & <span>Achievements</span></h2>

        <div class="project-container">

            <div class="project-card">
                <h3>Technical Certifications</h3>
                <p>Add your Java, Python, AI and other course certificates.</p>
            </div>

            <div class="project-card">
                <h3>Achievements</h3>
                <p>Add coding contests, hackathons, workshops and club achievements.</p>
            </div>

        </div>

    </section>


    <!-- CONTACT -->
    <section id="contact">

        <h2>Get In <span>Touch</span></h2>

        <p>Email: yourmail@example.com</p>

        <div class="social">
            <a href="https://linkedin.com/">LinkedIn</a>
            <a href="https://github.com/">GitHub</a>
        </div>

    </section>


    <!-- FOOTER -->
    <footer>
        <p>© 2026 Harshitha D | Designed with HTML & CSS</p>
    </footer>

</body>
</html>
```
style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    background: #080808;
    color: white;
    font-family: 'Poppins', sans-serif;
}

/* NAVBAR */

header {
    width: 90%;
    margin: auto;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 22px 35px;
    background: #1c1c1c;
    border-radius: 0 0 6px 6px;
}

.logo {
    color: #42a900;
}

.navbar ul {
    display: flex;
    list-style: none;
    gap: 25px;
}

.navbar a {
    text-decoration: none;
    color: #aaa;
    font-size: 12px;
    transition: 0.3s;
}

.navbar a:hover {
    color: #42a900;
}

/* HERO */

.hero {
    width: 80%;
    margin: 100px auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 50px;
}

.hero-content {
    max-width: 550px;
}

.hero h1 {
    font-size: 38px;
    margin-bottom: 10px;
}

.hero h1 span,
section h2 span {
    color: #42a900;
}

.hero h3 {
    color: #aaa;
    margin-bottom: 20px;
}

.hero p {
    color: #999;
    font-size: 14px;
    line-height: 1.8;
}

.profile img {
    width: 270px;
    height: 270px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid #42a900;
}

/* BUTTONS */

.buttons {
    margin-top: 30px;
}

.btn {
    display: inline-block;
    padding: 13px 25px;
    background: #42a900;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    margin-right: 10px;
    font-size: 13px;
    transition: 0.3s;
}

.btn:hover {
    background: #358b00;
    transform: translateY(-3px);
}

.outline {
    background: transparent;
    border: 1px solid #42a900;
}

/* SECTIONS */

section:not(.hero) {
    width: 80%;
    margin: 80px auto;
    padding: 40px 0;
}

section h2 {
    font-size: 28px;
    margin-bottom: 30px;
}

section:not(.hero) p {
    color: #aaa;
    line-height: 1.8;
    font-size: 14px;
}

/* SKILLS */

.skill-container {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
}

.skill {
    background: #191919;
    border: 1px solid #292929;
    padding: 15px 25px;
    border-radius: 5px;
    color: #ccc;
    transition: 0.3s;
}

.skill:hover {
    border-color: #42a900;
    color: #42a900;
}

/* PROJECTS */

.project-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.project-card {
    background: #151515;
    border: 1px solid #252525;
    padding: 25px;
    border-radius: 8px;
    transition: 0.3s;
}

.project-card:hover {
    transform: translateY(-6px);
    border-color: #42a900;
}

.project-card h3 {
    margin-bottom: 15px;
}

.project-card h4 {
    color: #42a900;
    margin-bottom: 10px;
}

.project-card .tech {
    color: #42a900;
    margin: 15px 0;
}

.project-card a {
    color: #42a900;
    text-decoration: none;
    font-size: 13px;
}

/* EXPERIENCE */

#experience .project-card {
    max-width: 500px;
}

/* CONTACT */

.social {
    display: flex;
    gap: 25px;
    margin-top: 20px;
}

.social a {
    color: #42a900;
    text-decoration: none;
}

/* FOOTER */

footer {
    background: #151515;
    padding: 25px;
    text-align: center;
    color: #777;
    font-size: 12px;
}

/* RESPONSIVE */

@media(max-width: 900px) {

    .navbar {
        flex-direction: column;
        gap: 20px;
    }

    .navbar ul {
        flex-wrap: wrap;
        justify-content: center;
    }

    .hero {
        flex-direction: column-reverse;
        text-align: center;
    }

    .project-container {
        grid-template-columns: repeat(2, 1fr);
    }

}

@media(max-width: 600px) {

    .hero h1 {
        font-size: 28px;
    }

    .profile img {
        width: 200px;
        height: 200px;
    }

    .project-container {
        grid-template-columns: 1fr;
    }

    section:not(.hero) {
        width: 90%;
    }

    .hero {
        width: 90%;
    }

}
```


## OUTPUT
<img width="1871" height="1022" alt="image" src="https://github.com/user-attachments/assets/0734887d-706a-4bad-a701-1404fd550583" />
<img width="1891" height="1016" alt="image" src="https://github.com/user-attachments/assets/a462731f-c975-42fc-be0d-01eb3d5c6201" />
<img width="1900" height="1020" alt="image" src="https://github.com/user-attachments/assets/2265b769-ad1f-4f7a-979c-ec313cc572ea" />





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
