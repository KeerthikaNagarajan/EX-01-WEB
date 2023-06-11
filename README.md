# Ex-01:
## To create a web Portfolio/CV using HTML & CSS
### AIM:
The aim of the given code is to create a web portfolio or CV using HTML and CSS. The code includes sections such as Home, About, Skills, Education, Internship, and Contact, providing information about the person, their skills, education, and contact details.
### ALGORITHM:
1. Create an HTML file with the extension ".html" and a CSS file with the extension ".css".
2. In the HTML file, use the <!DOCTYPE html> declaration to specify that it is an HTML5 document.
3. Inside the 'head tag, set the title of the web page and link the CSS file using the link tag.
4. Inside the body tag, structure the content of the web page using HTML elements such as nav, div, p, img, hr, center, h2, ul, li, form, label, input, textarea, and button.
5. Use CSS styles defined in the CSS file to format and position the elements on the web page.
6. Use CSS classes and IDs to apply specific styles to individual elements.
7. Use the "#" symbol followed by the ID name to create anchor links for navigation within the web page.
8. Save the HTML and CSS files.
9. Open the HTML file in a web browser to see the result.
### PROGRAM:
#### port.html:
```html
<!DOCTYPE html>
<html>
<head>
  <title>KN</title>
  <link rel="stylesheet" href="style.css" >
</head>
<body>
    <p id="home"><img class="logo" src="logo.png" align="left" /></p>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#education">Education</a>
    <a href="#internship">Internship</a>
    <a href="#contact">Contact</a>
  </nav>
  <hr size="4" width="90%" style="color:#F5BEBE;"><br>

  <img class="pic" src="pic.png" align="right"/>
  <div class="name">
  <div><span class="text-with-line">Keerthika Nagarajan</span></div>
  <p style="font-size: medium; padding-top: 15px;">Artificial Intelligence and Data Science</p>
  <p style="font-size: small;">STUDENT<br><br>2nd Year</p>
  </div>
  <p class="arrow">&#8595;</p><br>
  <hr size="4" width="90%" style="color:#F5BEBE;"><br>
  
  <center>

  <u><h2 id="about">About</h2></u>
  <p class="small">Hi, my name is Keerthika and I am a student specializing in Artificial Intelligence and Data Science. 
    As an aspiring AI professional, I am passionate about leveraging the power of data to solve complex 
    problemsand create innovative solutions. I have been actively involved in various academic and 
    personal projects to hone my skills in machine learning, deep learning, data analysis, and data 
    visualization. My goal is to apply my expertise in AI and Data Science to make a positive impact
    on society and contribute to the advancement of technology.</p><br>
    <div class="text" align="left">
    <ul class="no-bullets">
        <li><p class="smallbold">Name:</p> Keerthika</li>
        <li><p class="smallbold">Date of Birth:</p> 08/06/2004</li>
        <li><p class="smallbold">Nationality:</p> Indian</li>
        <li><p class="smallbold">State:</p> Tamil Nadu</li>
    </ul>
    <ul class="no-bullets">
        <li><p class="smallbold">Age:</p> 18</li>
        <li><p class="smallbold">Phone:</p> 7094248484</li>
        <li><p class="smallbold">Email:</p> nkeerthi2004@gmail.com</li>
        <li><p class="smallbold">Address:</p> M-5,M Block,2nd Street,Agathiar Nagar,<br>Villivakkam, Chennai - 600049</li>
    </ul>
    </div><br>
    <hr size="4" width="90%" style="color:#F5BEBE;"><br>

  <u><h2 id="skills">Skills</h2></u>
  <div class="text">
    <ul>
    <li>C Programming</li>
    <li>Python</li>
    <li>Java</li>
    <li>Javascript</li>
    <li>HTML/CSS</li>
    </ul>
    <ul>
    <li>Product Development</li>
    <li>3D Printing</li>
    <li>Digital Image Processing</li>
    <li>Project Management</li>
    <li>Data Science</li>
    </ul>
  </div><br>
  <hr size="4" width="90%" style="color:#F5BEBE;"><br>

  <u><h2 id="education">Education</h2></u>
  <div>
  <ul class="no-bullets" style="padding-right: 250px;">
      <li><p class="smallbold">Saveetha Engineering College</p><br>Bachelor in Artificial Intelligence & Data Science<br>2022 - 2025</li><br>
      <li><p class="smallbold">S.B.O.A Matric. & Hr. Sec. School</p><br>SSLC<br>2018-2019</li><br>
      <li><p class="smallbold">S.B.O.A Matric. & Hr. Sec. School</p><br>HSC<br>2020-2021</li>
  </ul>
  </div><br>
  <hr size="4" width="90%" style="color:#F5BEBE;"><br>

  <u><h2 id="internship">Internship</h2></u>
  <div>
    <ul class="no-bullets" style="padding-right: 250px;">
        <li><p class="smallbold">Monolith Technologles</p><br>Virtual Reality</li><br>
        <li><p class="smallbold">Technook</p><br>Artificial Intelligence</li>
    </ul>
    </div><br>
</center>

<div class="example">
  <div class="row">
    <h2 id="contact" style="color: #433A33; padding-left: 20px; padding-top: 20px;">Contact</h2>
    <div class="column">
      <div class="small" style="color: #433A33; padding-left: 50px;">
      <p>Keerthika</p>
      <p>7094248484</p>
      <p>nkeerthi2004@gmail.com</p><br>
      <p >M-5,M Block,2nd Street,Agathiar Nagar,<br>Villivakkam, Chennai - 600049</p><br>
      <p><b>Stay Connected</b></p>
      <a href="https://www.linkedin.com/in/keerthikanagarajan/"><img src="linked.png" width="35px"/></a>&emsp;
      <a href="https://github.com/KeerthikaNagarajan"><img src="git.png" width="28px"></a>&emsp;
      <a href="https://www.facebook.com/KeerthikaNagarajan2004/"><img src="face.png" width="32px"/></a>&ensp;
      <a href="https://www.instagram.com/keerthika.nagarajan/"><img src="insta.png" width="40px"/></a>
    </div></div>

    <div class="column">
      <p>Or Leave a Message Here</p>
      <form>
        <label for="fname">Full Name:</label><br>
        <input type="text" id="fname" name="fname"><br><br>
        <label for="email">Email:</label><br>
        <input type="text" id="email" name="email"><br><br>
        <label for="sub">Subject:</label><br>
        <input type="text" id="sub" name="sub"><br><br>
      </form>      
      <div>Message Here</div>
      <textarea placeholder="Your Message..."></textarea><br>
      <button>Submit</button>
    </div>
  </div>
</div>
</body>
</html>

```
#### style.css:
```
body {
    background-color: #433A33;
    height: 125vh;  
    margin-top: 18px;  
    padding-left: 20px;
    padding-right: 20px;
    background-size: cover; 
  }  
  nav{
    padding-top: 10px;
    padding-left: 650px;
  }
    nav a {
      float: left;
      color: #EFEDE1;
      text-align: center;
      padding: 16px 18px;
      text-decoration: none;
      font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
      font-size: medium;
    }
    .container {
        position: relative;
        color: #EFEDE1;
      }
    .logo{
        padding-top: 8px;
        width:13%;
        padding-left: 18px;
    }
    .name{
        color: #EFEDE1;
        padding-top: 80px;
        padding-left: 90px;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size: xx-large;
        font:bolder;
    }
    .text{
        color: #EFEDE1;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size: medium;
    }
    .text-with-line {
        position: relative;
        display: inline-block;
        font-size: 24px;
      }
      
      .text-with-line::after {
        content: "";
        position: absolute;
        left: 0;
        bottom: -15px;
        width: 30%;
        height: 6px;
        background-color:  #F5BEBE;
      }
      .arrow {
        padding-top: 40px;
        padding-left: 90px;
        font-size: 2em;
        color: #F5BEBE;
      }
      h2{
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        color: #EFEDE1;
        padding-bottom: 12px;
        
      }
      .small{
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        color: #EFEDE1;
        font-size: medium;
        padding-left: 80px;
        padding-right: 80px;
      }
      .smallbold{
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        color: #F5BEBE;
        font-size: medium;
        font: bolder;
        display:inline;
      }
      u{
        color:#F5BEBE;
        size: 4;
      }

      ul {
        display: inline-block;
        vertical-align: top;
        padding-right: 100px;
        padding-left: 100px;
        margin: 0;
      }
      li{
        padding-bottom: 15px;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        color: #EFEDE1;

      }
      ul.no-bullets {
        list-style-type: none; 
        padding: 0;
        margin: 0; 
        padding-left: 250px;
      }
      .example { 
        background-color: #EFEDE1;
        height: 70vh;  
        background-size: cover; 
        padding: 0;
    } 

    * {
      box-sizing: border-box;
    }
    
    .column {
      float: left;
      width: 50%;
      padding-top: 0px;
      height: 300px; 
    }
    
    .row:after {
      content: "";
      display: table;
      clear: both;
    }
    button {
      float: right;
      background-color:#433A33;
      color: #EFEDE1;
      padding: 15px 20px;
      text-align: center;
      text-decoration: none;
      display: inline-block;
      font-size: 14px;
      margin: 10px;
      cursor: pointer;
      border-radius: 12px;
      font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
    .pic{
      width: 22%;
      vertical-align: middle;
      padding-top: 30px;
      padding-right: 40px;
  }
```
### OUTPUT:
![Web capture_6-6-2023_142416_](https://github.com/KeerthikaNagarajan/portfolio-html-css/assets/93427089/e3c4840b-965a-4e7e-b46d-7d147fddb505)

### RESULT:
The result of running the code is a web page that displays a portfolio/CV was successful done.
