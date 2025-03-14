# Ex01 Portfolio
## Date:14.02.2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Susithra.B | Portfolio</title>
    <style>
        /* General Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #f5f5f5;
            color: #333;
        }

        /* Header & Navigation */
        header {
            background-color: #0073e6;
            color: white;
            padding: 15px 0;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
        }
        nav ul li a:hover {
            color: #ffcc00;
        }

        /* Sections */
        section {
            padding: 60px 20px;
            margin: 80px 20px 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            text-align: center;
        }

        /* Projects */
        .project {
            background-color: #e6f2ff;
            padding: 15px;
            border-radius: 8px;
            margin: 10px 0;
        }

        /* Contact */
        #contact a {
            color: #0073e6;
            text-decoration: none;
            font-weight: bold;
        }
        #contact a:hover {
            text-decoration: underline;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 10px;
            background-color: #0073e6;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                gap: 10px;
            }
            section {
                padding: 40px 15px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Susithra.B</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#internship">Internship</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hi, I'm Susithra.B! A 2nd-year Information Technology Student specializing in Full-Stack Java Development and Data Science.</p>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>Enhancing SAR Image Interpretation</h3>
                <p>Deep learning-based SAR image colorization using Python, TensorFlow, and OpenCV.</p>
            </div>
            <div class="project">
                <h3>Predictive Hiring with Data Science</h3>
                <p>AI-driven recruitment system for bias-free hiring decisions.</p>
            </div>
        </section>

        <section id="internship">
            <h2>Internship</h2>
            <p><strong>Arjun Vision Tech Solutions | 2024</strong></p>
            <p>Worked on predictive modeling, machine learning, and SAR image processing.</p>
        </section>

        <section id="education">
            <h2>Education</h2>
            <p><strong>B.Tech in IT </strong> - Saveetha Engineering College (2023-2027) | CGPA: 8.5</p>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>Java, Python,Ct</li>
                <li>Data Science</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Email: bsusithra05@gmail.com</p>
            <p>GitHub: <a href="#" target="_blank">github.com/Susithrab</a></p>
            <p>LinkedIn: <a href="#" target="_blank">linkedin.com/in/Susithrab</a></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Susithra.B All Rights Reserved.</p>
    </footer>

</body>
</html>


## OUTPUT
![{81B98434-0309-4A54-B1CF-EF39F671D0D1}](https://github.com/user-attachments/assets/de2eb6b7-17f2-44ad-90ef-cf89586bb1a8)
![{5551A06B-AF30-4CF6-9F91-4D6439600A5C}](https://github.com/user-attachments/assets/f8a482e4-c5b7-4e6a-ad93-9e42f6bcc411)
![{5861E1CF-462E-4C73-9F87-B636636FF9E5}](https://github.com/user-attachments/assets/abd34cfe-5c6b-42d0-8d92-56a73be43101)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
