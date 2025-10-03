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
### Home.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Home | Aadhi</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <nav>
    <ul>
      <li><a href="home.html">Home</a></li>
      <li><a href="about.html">About Me</a></li>
      <li><a href="projects.html">Projects</a></li>
    </ul>
  </nav>
  <section class="hero">
    <h1>Hi, I'm Aadhi 👋</h1>
    <p>Welcome to my portfolio. I blend tech, design, and tradition.</p>
  </section>
</body>
</html>
~~~
### Projects.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Projects | Aadhi</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <nav>
    <ul>
      <li><a href="home.html">Home</a></li>
      <li><a href="about.html">About Me</a></li>
      <li><a href="projects.html">Projects</a></li>
    </ul>
  </nav>
  <section class="projects">
    <h2>My Projects</h2>
    <div class="project-card">
      <h3>Smart Attendance System</h3>
      <p>IoT-based face recognition with cloud sync.</p>
    </div>
    <div class="project-card">
      <h3>Secure IoT Framework</h3>
      <p>IEEE paper with patent-ready architecture.</p>
    </div>
    <div class="project-card">
      <h3>Responsive Quiz App</h3>
      <p>Built with JavaScript and Python backend.</p>
    </div>
  </section>
</body>
</html>
~~~
### About.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>About Me | Aadhi</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <nav>
    <ul>
      <li><a href="home.html">Home</a></li>
      <li><a href="about.html">About Me</a></li>
      <li><a href="projects.html">Projects</a></li>
    </ul>
  </nav>
  <section class="about">
    <h2>About Me</h2>
    <p>I'm a tech enthusiast from Tenkasi, passionate about networking, programming, and visual design. I love solving real-world problems and creating clean, functional interfaces.</p>
  </section>
</body>
</html>
~~~
### Style.css
~~~
body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  background: linear-gradient(to right, #fceabb, #f8b500);
  color: #333;
}

nav {
  background-color: #ff6f61;
  padding: 15px;
  text-align: center;
}

nav ul {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: center;
  gap: 30px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s;
}

nav ul li a:hover {
  color: #333;
}

.hero, .about, .projects {
  padding: 60px 20px;
  max-width: 800px;
  margin: auto;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.project-card {
  background-color: #f9f9f9;
  margin: 20px 0;
  padding: 20px;
  border-left: 5px solid #ff6f61;
  border-radius: 5px;
}
~~~

## OUTPUT
<img width="2879" height="1549" alt="image" src="https://github.com/user-attachments/assets/4443c1fc-6b9d-4b97-b302-c87fb067b0de" />

<img width="2868" height="1647" alt="image" src="https://github.com/user-attachments/assets/ab526a0e-a5de-431c-91d9-2b3996b80a33" />

<img width="2863" height="1642" alt="image" src="https://github.com/user-attachments/assets/833ec39e-e922-4220-8aa4-257423e3a146" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
