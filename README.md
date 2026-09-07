# Ex01 Portfolio
## Date:

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

    html>
    <head>
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    </head>
    <body>
    <header>
        <nav>
            <h2 class="logo">My Portfolio</h2>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="home" class="hero">
        <h1>Hello</h1>
        <h3>AI & ML Student @ Saveetha Engineering College</h3>
        <p>
            Welcome to my portfolio! I'm a passionate B.Tech student specializing in Artificial Intelligence and Machine Learning. I love exploring new technologies, building projects, and continuously learning to enhance my skills.              This portfolio showcases my work, skills, and achievements in the field of technology.
        </p>

        <a href="#" class="btn">Download Resume</a>

    </section>
    <section id="about">
        <h2>About Me</h2>
        <p>
            I'm Dharshini K, a B.Tech Artificial Intelligence and Machine Learning student driven by curiosity and innovation. My interests lie in machine learning, deep learning, and data-driven applications that solve real-world challenges. I enjoy experimenting with algorithms, building intelligent systems, and exploring how AI can transform industries. With a strong commitment to growth and creativity, I aim to become a versatile AI professional contributing to impactful solutions.
        </p>
    </section>
    <section id="skills">
        <h2>Skills</h2>
        <div class="skill-box">HTML</div>
        <div class="skill-box">CSS</div>
        <div class="skill-box">Python</div>
        <div class="skill-box">C Programming</div>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <div class="project-card">
            <h3>Portfolio Website</h3>
            <p>Designed using HTML and CSS.</p>
        </div>
        <div class="project-card">
            <h3>Student Registration Form</h3>
            <p>Created using HTML and CSS.</p>
        </div>
        <div class="project-card">
            <h3>Restaurant Website</h3>
            <p>Created using simple HTML and CSS.</p>
        </div>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Email : abc@gmail.com</p>
        <p>Phone : +91 0123456789</p>
        <p>GitHub : github.com/DharshiniK</p>
    </section>
    <footer>
        © 2026 Dharshini K | All Rights Reserved
    </footer>
     </body>
     </html>

  styles.css

  
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Segoe UI", Arial, sans-serif;
    }


    header {
    background: #222;
    color: #fff;
    padding: 15px 0;
    position: sticky;
    top: 0;
    z-index: 1000;
    }

    nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 90%;
    margin: auto;
    }

    .logo {
    font-size: 24px;
    font-weight: bold;
    color: #fff;
    }

    nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
    }

    nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: 500;
    transition: color 0.3s ease;
    }

    nav ul li a:hover {
    color: #00bcd4;
    }

    /* Hero Section */
    .hero {
    background: linear-gradient(to right, #00bcd4, #3f51b5);
    color: #fff;
    text-align: center;
    padding: 100px 20px;
    }

    .hero h1 {
    font-size: 48px;
    margin-bottom: 10px;
    }

    .hero h3 {
    font-size: 20px;
    margin-bottom: 20px;
    }

    .hero p {
    max-width: 700px;
    margin: auto;
    line-height: 1.6;
    font-size: 16px;
    }

    .btn {
    display: inline-block;
    margin-top: 20px;
    padding: 12px 25px;
    background: #fff;
    color: #3f51b5;
    font-weight: bold;
    text-decoration: none;
    border-radius: 5px;
    transition: background 0.3s ease, color 0.3s ease;
    }

    .btn:hover {
    background: #3f51b5;
    color: #fff;
    }


    section {
    padding: 60px 20px;
    text-align: center;
    }

    section h2 {
    font-size: 32px;
    margin-bottom: 20px;
    color: #3f51b5;
    }

    section p {
    max-width: 800px;
    margin: auto;
    line-height: 1.6;
    font-size: 16px;
    }


    .skill-box {
    display: inline-block;
    background: #f4f4f4;
    padding: 15px 25px;
    margin: 10px;
    border-radius: 8px;
    font-weight: bold;
    color: #333;
    transition: transform 0.3s ease, background 0.3s ease;
    }

    .skill-box:hover {
    transform: scale(1.05);
    background: #00bcd4;
    color: #fff;
    }


    .project-card {
    background: #f9f9f9;
    padding: 20px;
    margin: 15px auto;
    max-width: 600px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
    }

    .project-card:hover {
    transform: translateY(-5px);
    }

    .project-card h3 {
    color: #3f51b5;
    margin-bottom: 10px;
    }


    #contact p {
    font-size: 16px;
    margin: 8px 0;
    }


    footer {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 15px 0;
    margin-top: 30px;
    font-size: 14px;
    }


## OUTPUT


<img width="1522" height="907" alt="image" src="https://github.com/user-attachments/assets/9f539f08-ea47-441e-ba1a-7c932cf29f0c" />




## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
