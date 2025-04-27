# Ex01 Portfolio
## Name: Praveena M
## Reg no: 21222040153
## Date:04/03/2025
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
## HTML


```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio</title>
  <link rel="stylesheet" href="index.css" />
</head>
<body>

    <nav>
        <div class="logo">Hii I'm Praveena</div>
        <div class="nav-links">
          <a href="#skills">Skills</a>
          <a href="#experience">Experience</a>
          <a href="#contact">Contact</a>
          <a href="#about me">About me</a>
        </div>
      </nav>
      

  <header class="hero">
    <div class="hero-content">
      <h1>HI, I AM<br><strong>PRAVEENA</strong></h1>
      <a class="btn" href="file:///C:/Users/DELL/Documents/CERTIFICATES/RESUME.pdf">Download Resume</a>
    </div>
  </header>
  <section id="about">
    <h2 class="section-title">About Me</h2>
    <div class="about-container">
      <div class="about-text">
        <ul>
          <li><strong>Engineering Student:</strong> Passionate about technology and design.</li>
          <li><strong>Web Development:</strong> Proficient in HTML and CSS, focusing on user-friendly interfaces.</li>
          <li><strong>3D Modeling:</strong> Experience with Fusion 360, blending creativity with technical skills.</li>
          <li><strong>Continuous Learning:</strong> Constantly expanding my knowledge in programming and design.</li>
        </ul>
      </div>
      <div class="about-image">
        <img src="me.jpg" alt="Praveena Profile" />
      </div>
    </div>
  </section>
  
  
  <section id="skills">
    <h2 class="section-title">Skills</h2>
    <ul class="skills-list">
      <li>HTML & CSS (BASICS)</li>
      <li>C Programming</li>
      <li>Teamwork</li>
      <li>Time Management</li>
      <li>Leadership</li>
      <li>Effective Communication</li>
      <li>Critical Thinking</li>
    </ul>
  </section>
  
  
  <section id="experience">
    <h2 class="section-title">Experience</h2>
 
  
  
    <ul class="experience-list">
      <li>I recently attended an industrial visit to an image creation company, which gave me valuable insights into the digital design process.</li>
      <li>I observed how advanced technologies are used to create high-quality images, from initial concepts to final production.</li>
      <li>The visit enhanced my understanding of industry practices and the importance of both creativity and precision.</li>
      <li>It also inspired me to further explore the intersection of technology and design in my studies.</li>
      <li>Trios Technologies PVT LTD – Inplant Training in Web Development: Developed a web page and learned HTML and tools like NetBeans, Apache Tomcat, and JDK.</li>
    </ul>

  </section>
  <section id="contact">
    <h2 class="section-title">Contact Me</h2>
    <div class="contact-container">
      <form class="contact-form">
        <input type="text" placeholder="Name*" required />
        <input type="email" placeholder="Email*" required />
        <input type="text" placeholder="Subject" />
        <textarea placeholder="Message"></textarea>
        <button type="submit">Submit</button>
      </form>
  
      <div class="contact-info">
        <p><strong>Phone</strong><br>987-123-6547</p>
        <p><strong>Email</strong><br>praveena@gmail.com</p>
        <p><strong>Website</strong><br><a href="https://www.brownsine.com" target="_blank">www.brownsine.com</a></p>

      </div>
    </div>
  </section>
  
  <!-- Font Awesome (Place this before closing </body> if not added already) -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  
</body>
</html>





```


#Style.css

```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
  }
  
  body, html {
    font-family: Arial, sans-serif;
  }
  
  nav {
    position: fixed;
    top: 0;
    width: 100%;
    background: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 40px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    z-index: 1000;
  }
  
  .logo {
    font-weight: bold;
    color: #5d2351;
    font-size: 1.2rem;
  }
  
  .nav-links a {
    margin-left: 20px;
    text-decoration: none;
    color: #444;
    font-weight: 500;
  }
  
  .hero {
    background: url('home.jpeg') no-repeat center center/cover;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: white;
    padding: 20px;
  }
  
  .hero-content h1 {
    font-size: 3rem;
    margin-bottom: 10px;
  }
  
  .hero-content h2 {
    font-size: 2rem;
    font-weight: 300;
  }
  
  .btn {
    margin-top: 30px;
    padding: 12px 30px;
    background: #a100ff;
    color: white;
    text-decoration: none;
    border-radius: 30px;
    display: inline-block;
  }
  
  section {
    padding: 100px 20px;
    min-height: 100vh;
  }
  
  #skills, #experience {
    background: #f7f7f7;
  }
  
  .section-title {
    font-size: 2rem;
    margin-bottom: 30px;
    color: #333;
    text-align: center;
  }
  
  section p {
    text-align: center;
    color: #666;
  }
  /* === Contact Section === */
#contact {
    background-color: #f9f9f9;
    padding: 100px 20px;
  }
  
  .contact-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    max-width: 1000px;
    margin: auto;
    gap: 30px;
  }
  
  .contact-form {
    flex: 1;
    min-width: 300px;
    display: flex;
    flex-direction: column;
    gap: 15px;
  }
  
  .contact-form input,
  .contact-form textarea {
    padding: 15px;
    border: none;
    background: #fff;
    border-radius: 5px;
    font-size: 1rem;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  }
  
  .contact-form textarea {
    height: 150px;
    resize: none;
  }
  
  .contact-form button {
    background: linear-gradient(45deg, #a100ff, #6de7db);
    color: white;
    padding: 14px;
    border: none;
    border-radius: 5px;
    font-size: 1rem;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    cursor: pointer;
    transition: all 0.3s ease;
  }
  
  .contact-form button:hover {
    opacity: 0.9;
  }
  
  .contact-info {
    flex: 1;
    min-width: 250px;
  }
  
  .contact-info h3 {
    font-size: 1.5rem;
    margin-bottom: 10px;
  }
  
  .contact-info p {
    margin-bottom: 15px;
    color: #555;
  }
  
  .contact-info a {
    color: #555;
    text-decoration: none;
  }
  
  .social-icons {
    display: flex;
    gap: 15px;
    margin-top: 20px;
  }
  
  .social-icons a {
    font-size: 1.2rem;
    color: #333;
    transition: color 0.3s ease;
  }
  
  .social-icons a:hover {
    color: #a100ff;
  }
  
  /* === About Section === */
#about {
    padding: 100px 20px;
    background-color: #fff;
    text-align: center;
  }
  
  #about {
    background-color: #6aebeb; /* Light blue background color */
    padding: 40px 20px;
  }
  
  .about-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    max-width: 1000px;
    margin: auto;
    gap: 40px;
  }
  
  .about-text {
    flex: 1 1 300px;
    font-size: 1.1rem;
    color: #444;
    text-align: left;
  }
  
  .about-text p {
    margin-bottom: 20px;
  }
  
  .about-image {
    flex: 1 1 250px;
    text-align: center;
  }
  
  .about-image img {
    width: 300px;
    height: 250px;
    object-fit: cover;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
}

  #skills {
    background-image: url('skills.jpeg');
    background-size: cover;
    background-position: center;
    padding: 50px 20px;
    color: white;
  }
  #experience {
    font-size: large;
    background-image: url('exp.jpg'); /* Make sure file name and extension are correct */
    background-size: cover;
    background-position: center;
    padding: 50px 20px;
    color: rgb(9, 8, 8);
  }
  #skills {
    background-color: #f0f8ff; /* Light blue background color */
    padding: 40px 20px;
  }
  
  .skills-list {
    list-style-type: none;
    padding-left: 0;
    font-size: 1.2rem;
    line-height: 1.8;
  }
  
  .skills-list li {
    margin-bottom: 10px;
    padding-left: 20px;
    position: relative;
  }
  
  .skills-list li::before {
    content: "\2022"; /* Unicode for bullet point */
    position: absolute;
    left: 0;
    color: #007bff; /* Blue color for bullet points */
    font-size: 1.5rem;
  }
  



```
## OUTPUT

![Screenshot 2025-04-27 160535](https://github.com/user-attachments/assets/c43dd7e5-9b30-4995-8ce0-7a3097763c5d)

![Screenshot 2025-04-27 160543](https://github.com/user-attachments/assets/85e95604-2e60-416f-83c2-7e31fb9b4da3)



![Screenshot 2025-04-27 160552](https://github.com/user-attachments/assets/dd3cf527-1a0d-4fe1-9c44-f7911eee1151)

![Screenshot 2025-04-27 160605](https://github.com/user-attachments/assets/ddca2cff-d6d9-4dad-b802-50c053d7f7f9)


![Screenshot 2025-04-27 160619](https://github.com/user-attachments/assets/89a95a72-dab0-477d-8517-08b7531f757e)



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
