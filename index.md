<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">


    <title>Vanessa Hoang's Webpage</title>
    <link rel="stylesheet" href="./src/css/index.css">
    <link rel="shortcut icon" href="./src/img/favicon.png" type="image/x-icon" />
    <link href="https://fonts.googleapis.com/css2?family=Assistant:wght@800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
    <!-- Boostrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
    
    <!-- Hotjar Tracking Code for vanessah9.github.io -->
    <script>
        (function(h,o,t,j,a,r){
            h.hj=h.hj||function(){(h.hj.q=h.hj.q||[]).push(arguments)};
            h._hjSettings={hjid:1967828,hjsv:6};
            a=o.getElementsByTagName('head')[0];
            r=o.createElement('script');r.async=1;
            r.src=t+h._hjSettings.hjid+j+h._hjSettings.hjsv;
            a.appendChild(r);
        })(window,document,'https://static.hotjar.com/c/hotjar-','.js?sv=');
    </script>
</head>
<body>
    <!-- <nav class="navbar fixed-top">
        <a class="navbar-brand" href="#">
          <img src="./src/img/logo.png" width="100" height="49" alt="" loading="lazy">
        </a>
        <ul>
            <li>
                <a href="#home">Home</a> 
            </li>
            <li> 
                <a href="#projects">Projects</a> 
            </li>
            <li> 
                <a href="#contact">Contact</a> 
            </li>
        </ul>
      </nav> -->

      <nav class="navbar fixed-top navbar-expand-md">
        <div class="collapse navbar-collapse" id="main-navigation">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="#home">
                  01.
                <span class="teal-font">Home</span>
                </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#projects">
                02.
                <span class="teal-font">Projects</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">
                  03.
                  <span class="teal-font">Contact</span></a>
            </li>
          </ul>
        </div>

        <a class="navbar-brand pull-right" href="#">
            <img src="./src/img/logo.png" width="100" height="49" alt="" loading="lazy">
        </a>
      </nav>
      
      <div id="home">
        <img class="picture" src="./src/img/header.jpg">
    </div>

      <div class="container-fluid">
        <div class="row row-cols-2">
            <div class="col-4" id="projects">Projects</div>
            <div class="col-8"> 
                <div class="row">
                    <div class="col-sm-6">
                        <div class="project-img">
                            <a href="https://devpost.com/software/kenko-website-app" target="_blank">
                                <img class="picture" src="./src/img/kenko.jpg">
                            </a>
                        </div>
                    </div>
                    <div class="col-sm-6">
                        <h3 class="project-name">Kenko</h3>
                        <h6 class="subtitle">Made with HTML, CSS, Photoshop</h6>
                        <h5 class="description">During my time at SheHacks IV (2020), my teammates and I prototyped a web application called Kenko. It is intended to assist individuals who have medical conditions manage or treat their illnesses with set meal recipes.</h5>
                    </div>

                    <div class="col-sm-6">
                        <div class="project-img">
                            <a href="https://ilearn.netlify.app/" target="_blank">
                                <img class="picture" src="./src/img/sHacks pic.png">
                            </a>
                        </div>
                    </div>
                    <div class="col-sm-6">
                        <h3 class="project-name">Scotia iLearn</h3>
                        <h6 class="subtitle">Made with Figma, JavaScript, HTML, CSS.</h6>
                        <h5 class="description">At sHacks (2020), this app was created to encourage financial literacy within youth using Scotiabank's educational resources. Features includes course plans on personal finance topics and a assistant chatbot devised to answer questions on Scotiabnk's products/services or financial topics. </h5>
                    </div>

                    <div class="col-sm-6">
                        <div class="project-img">
                            <a href="https://github.com/vanessah9/ACNH-Discord-Bot" target="_blank">
                                <img class="picture" src="./src/img/discord image.jpg">
                            </a>
                        </div>
                    </div>
                    <div class="col-sm-6">
                        <h3 class="project-name">ACNH Discord Bot</h3>
                        <h6 class="subtitle">Made with Python.</h6>
                        <h5 class="description">Explored using API's and JSON files by creating a discord bot using Discord.py API and ACNH RESTful API. This bot was inspired by my recent pastime, Animal Crossing New Horizons, and is created to return the information of the called item (ex. fish, bug, art etc.) found in the database. </h5>
                    </div>

                </div>
            </div>
            <div class="col-4" id="contact">Get in Touch</div>
            <div class="col-8">
                <button class="btn"><a class="links" href="#"><i class="fa fa-envelope-o"></i> vanessahoang9@gmail.com</a></button>
                <button class="btn"><a class="links" href="https://linkedin.com/in/vanessahoang9" target="_blank"><i class="fa fa-linkedin-square"></i> Linkedin </a></button>
                <button class="btn"><a class="links" href="https://github.com/vanessah9" target="_blank"><i class="fa fa-github-square"></i></i> Github</a></button>
                <button class="btn"><a class="links" href="https://www.facebook.com/vanessahoang93/" target="_blank"><i class="fa fa-facebook-square"></i> Facebook</a></button>

            </div>
          </div>
      </div>

      <!-- Footer -->
      <div class="footer">
          <h3 class="quote"> “Design is not just what it looks like and feels like. 
            Design is how it works” - Steve Jobs</h3>
          <h6 class="footer-text"> Designed and Built by Vanessa Hoang</h6>

      </div>
     </div>

</body>
</html>


<!-- <div id="projects">
    <h4>
        Projects
    </h4>
    <div class="flex-container" >
        <div class="box">
            <img class="picture" src="./src/img/holder.png">
        </div>
        <div class="box">
            <img class="picture" src="./src/img/holder.png">
        </div>
        <div class="box">
            <img class="picture" src="./src/img/holder.png">
        </div>
    </div>
</div>  -->

<!-- 
        <h3>
            Hi I'm
            <span class="teal-font">Vanessa Hoang</span>
            a Computer Science student with a passion for 
            <span id="interest">design and technology</span> 
            attending
            <span class="teal-font"> Ryerson University</span>
            in Toronto, Canada.
        </h3> 
-->

<!-- Introduction Section -->
    <!-- <nav class="nav-bar">
        <ul>
            <li>
                <a href="#home">Home</a> 
            </li>
            <li> 
                <a href="#projects">Projects</a> 
            </li>
            <li> 
                <a href="#contact">Contact</a> 
            </li>
        </ul>
    </nav> -->
    <!-- <div class="navbar">
        <ul>
            <li>
                <a href="#home">Home</a> 
            </li>
            <li> 
                <a href="#projects">Projects</a> 
            </li>
            <li> 
                <a href="#contact">Contact</a> 
            </li>
        </ul>
    </div>
    <div id="home">
        <img class="picture" src="./src/img/header.jpg">
    </div> -->

    <!-- Project Section -->
    <!-- <div id="projects">
        <h4>
            Projects
        </h4>
        <div class="flex-container" >
            <div class="box">
                <img class="picture" src="./src/img/holder.png">
            </div>
            <div class="box">
                <img class="picture" src="./src/img/holder.png">
            </div>
            <div class="box">
                <img class="picture" src="./src/img/holder.png">
            </div>
        </div>
    </div> -->

    <!-- Contact Me Section-->
    <!-- <div id="contact">
        <h4>
            Get in Contact
        </h4>
    </div> -->
