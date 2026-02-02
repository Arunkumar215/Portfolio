# Ex01 Portfolio
## Date:2/2/2026

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
#index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    
    <meta charset="UTF-8">
    <title>Arunkumar S A | Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Arunkumar S A</h1>
    <p>Information Technology Student | Programmer</p>
</header>

<section class="about">
    <h2>About Me</h2>
    <p>
        I am a Information Technology student interested in C programming,
        Java, and problem solving. I enjoy learning new technologies
        and building simple projects.
    </p>
</section>

<section class="skills">
    <h2>Skills</h2>
    <ul>
        <li>C Programming</li>
        <li>Java</li>
        <li>Python</li>
        <li>HTML & CSS</li>
        <li>Problem Solving</li>
    </ul>
</section>

<section class="projects">
    <h2>Projects</h2>

    <div class="project-card">
        <h3>Sports Club Management System</h3>
        <p>Developed using php to manage sports records.</p>
    </div>

    </section>

<section class="contact">
    <h2>Contact</h2>
    <p>Email: arunkumar20050515@gmail.com</p>
    <p>Contact:9042773295</p>
    
</section>

<footer>
    <p>© 2026 Arunkumar S A</p>
</footer>

</body>
</html>


```
#style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f4f4f4;
    color: #333;
}

/* Header */
header {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 30px 10px;
}

header h1 {
    font-size: 36px;
}

header p {
    font-size: 18px;
    margin-top: 10px;
}

/* Sections */
section {
    background: white;
    margin: 20px auto;
    padding: 20px;
    width: 80%;
    border-radius: 8px;
}

section h2 {
    margin-bottom: 15px;
    color: #222;
}

/* Skills */
.skills ul {
    list-style-type: square;
    margin-left: 20px;
}

/* Projects */
.project-card {
    background-color: #eee;
    padding: 15px;
    margin-bottom: 10px;
    border-left: 5px solid #222;
}

/* Contact */
.contact p {
    margin: 5px 0;
}

/* Footer */
footer {
    text-align: center;
    padding: 15px;
    background-color: #222;
    color: white;
}


```
## OUTPUT
<img width="1909" height="950" alt="Screenshot 2026-02-02 091329" src="https://github.com/user-attachments/assets/6dd188bb-2840-43c5-bee3-a3d3ec70d247" />

<img width="1914" height="950" alt="Screenshot 2026-02-02 091433" src="https://github.com/user-attachments/assets/3202160d-5722-4d9b-87f3-89e6891535d1" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
