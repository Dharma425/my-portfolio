# my-portfolio
#this is my first web site in college life 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale =1.0" />
    <title>Dharamraj Patel</title>
    <link rel="stylesheet" href="style.css" />
    <!-- <link href="https://unpkg.com/boxicons@2.1.4/css/boxicon.min.css"rel ="stylesheet"/> -->
</head>

<body>
    <header class="header">
        <a href="#HOME" class="logo">PortfolioWebsite</a>
        <i class="bx bx-menu" id="menu-icon"></i>
        <nav class="navbar">
            <a href="#HOME">HOME</a>
            <a href="#ABOUT">ABOUT</a>
            <a href="#skills">SKILL</a>
            <a href="#CONTACT">CONTACT</a>
        </nav>
    </header>
    <div class="home" id="home">
        <div class="home-content">
            <h1 align="center" item-width="100%">I Am <span>Dharamraj</span></h1>
            <!-- <h3>i'am Web Devloper</h3> -->
            <p align="center">
                Welcome to my portfolio website. Here you can find information about me and my skills. I currently pursuing a Bachelor's degree in Computer Applications.<br> I possess skills in Python, SQL, HTML,
                CSS, C++ and C.
            </p>
            <!-- <div class="social-icons">
                <a href="#">
                    <i classs="bx bxl-github"></i>
                    <a href="#"></a>
                    <i class="bx bx1-linkedin-square"></i>
                </a>
                <a href="#"></a>
                <i class="bx bx1-instagram-alt"></i>
                <a href="#">
                    <i class="bx bx1-twitter"></i></a>
            </div> -->

            <!-- <div class ="btn-group">
            <a href="#" class="btn">Hire</a>
            <a href="#contact" class="btn"> contact</a> -->
        </div>
        <div class="image">
            <img src="image2.png" height="400px" alt="Dharam">
        </div>
        <!--<div class="home-sci">
          <a href="#"><i class='bx bx1-facebook'</a>
          <a href="#"><i class='bx bx1-instagram'</a>
          <a href="#"><i class='bx bx1-whatsapp'</a>
          <a href="#"><i class='bx bx1-twitter'</a>
        </div>-->
    </div>
    <div class="container2">
        <h1 class="title" id="skills">My Programming Skills</h1>
        <div class="skills">
          <div class="skill">
            <h2>HTML</h2>
            <p>
              I can create structured and semantic HTML code that is easy to read
              and understand.
            </p>
          </div>
          <div class="skill">
            <h2>CSS</h2>
            <p><b></b>I can style and layout web pages using CSS<b></p>
          </div>
          <div class="skill">
            <h2>C/C++</h2>
            <p>I can do DSA in C/C++</p>
          </div>
        </div>
      </div>
      <div>
        <div class="footer">
          <p>Dharamraj Patel</p>
          <ul>
            <li>
              My name is Dharamraj Patel, currently pursuing a Bachelor's degree in
              Computer Applications. I possess skills in HTML, CSS,
              C++ and C.
            </li>
            <span id="element"></span>
          </ul>
          <ul>
            <li>+91 9044893809</li>
          </ul>
        </div>
        </div>
      </div>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
      var typed = new Typed('#element', {
        strings: ['web developar','graphics Designer','web designer','mo No:- 904893809'],
        typeSpeed: 50,
      });
    </script>
</body>

</html>
