<h1>Responsive Web Design</h1>
<h2>Building A Personal Portfolio Website</h2>

<h3>Project Objective</h3>
To Build an application that is functionally similar to https://personal-portfolio.freecodecamp.rocks
<br />


<h2>Languages Used</h2>

- <b>HTML and CSS</b> 
  
<h2>User Story:</h2> <br>
Your portfolio should have a welcome section with an id of welcome-section <br>
The welcome section should have an h1 element that contains text <br>
Your portfolio should have a projects section with an id of projects <br>
The projects section should contain at least one element with a class of project-tile to hold a project<br>
The projects section should contain at least one link to a project <br>
Your portfolio should have a navbar with an id of navbar <br>
The navbar should contain at least one link that you can click on to navigate to different sections of the page <br>
Your portfolio should have a link with an id of profile-link, which opens your GitHub or freeCodeCamp profile in a new tab <br>
Your portfolio should have at least one media query <br>
The height of the welcome section should be equal to the height of the viewport <br>
The navbar should always be at the top of the viewport <br>
Fulfill the user stories and pass all the tests below to complete this project. Give it your own personal style. 

<h2>Actual Project Development: HTML</h2>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Personal Portfolio Website</title>
  <link rel ="stylesheet" href ="styles.css">
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway:700&display=swap">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway:700&display=swap">

</head>
<body>
  <nav id="navbar" class="nav">
    <ul class="nav-list">
      <li><a href="#welcome-section">About</a></li>
      <li><a href="#projects">Work</a></li>
      <li><a href="#Contact">Contact</a></li>
    </ul>
  </nav>

  <section id="welcome-section" class="welcome-section">
  <h1>Hello! I am Alexander</h1>
  <p>Full stacked web developer</p>
  </section>


  <section id="projects" class="projects-section">
    <h2 class="projects-section-header">These are some of my projects</h2>
    <div class="projects-grid">
      
      <a href="https://codepen.io/freeCodeCamp/full/zNqgVx" target="_blank" class="project project-tile">
        <img  class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/tribute.jpg" alt="project">
        <p class="project-title">
         <span class="code"><</span>
         Tribute Page
         <span class="code">/></span>
 
        </p>
     </a>
     <a hf="https://codepen.io/freeCodeCamp/full/qRZeGZ" target="_blank" class="project project-tile">
      <img  class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/random-quote-machine.png" alt="project">
      <p class="project-title">
       <span class="code"><</span>
       Random-quote-machine
       <span class="code">/></span>

      </p>
   </a><a href="https://codepen.io/freeCodeCamp/full/wgGVVX" target="_blank" class="project project-tile">
    <img  class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/calc.png" alt="project">
    <p class="project-title">
     <span class="code"><</span>
     JavaScript Calculator
     <span class="code">/></span>

    </p>
 </a><a href="https://codepen.io/freeCodeCamp/full/mVEJag" target="_blank" class="project project-tile">
  <img  class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/map.jpg" alt="project">
  <p class="project-title">
   <span class="code"><</span>
   Map Data Across the Globe 
   <span class="code">/></span>

  </p>
</a><a href="https://codepen.io/freeCodeCamp/full/wGgEga" target="_blank" class="project project-tile">
  <img  class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/wiki.png" alt="project">
  <p class="project-title">
   <span class="code"><</span>
   Wikipedia Viewer
   <span class="code">/></span>

  </p>
</a>
<a href="https://codepen.io/freeCodeCamp/full/KzXQgy" target="_blank" class="project project-tile">
  <img  class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/tic-tac-toe.png" alt="project">
  <p class="project-title">
   <span class="code"><</span>
   Tic-Tac-Toe Game
   <span class="code">/></span>

  </p>
</a>

    </div>
    <a href="https://codepen.io/FreeCodeCamp/" class="btn btn-show-all" target="_blank">
      Show All
      <i class="fas fa-chevron-right">

      </i>
    </a>

  </section>

  <!--Start Contact Section-->
  <section id="contact" class="contact-section">
    <div class="contact-section-header">
      <h2>Let's Work Together</h2>
      <p>How do you take your coffee?</p>

    </div>
    <div class="contact-links">
      <a href="https://facebook.com/freecodecamp" target="_blank" class="btn contact-details">
        <i class="fab fa-facebook-square">
          
        </i>
        Facebook
      </a>
      <a id="profile-link" href="https://github.com/freecodecamp" target="_blank" class="btn contact-details">
        <i class="fab fa-github">
          
        </i>
        GitHub
      </a>
      <a href="https://youtube.com/freecodecamp" target="_blank" class="btn contact-details">
        <i class="fab fa-youtube">
        
        </i>
        Youtube
      </a>
      <a href="https://twitter.com/freecodecamp" target="_blank" class="btn contact-details">
        <i class="fab fa-twitter">
        
        </i>
        Twitter
      </a>
      <a href="mailto:peace@peace.com" target="_blank" class="btn contact-details">
        <i class="fas fa-at">
        
        </i>
        Send a Mail
      </a>
      <a href="tell:555-777-7878" target="_blank" class="btn contact-details">
        <i class="fas fa-mobile-alt">
          
        </i>
        Call Me
      </a>

    </div>

  </section>
  <!--End of Contact Section-->

  <!--Start Footer Section-->
  <footer>
    <p>**Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet vero, at earum nemo cumque nostrum reiciendis doloremque. Reprehenderit, quisquam voluptates**</p>
    <P>
       © Created for 
      <a href="https://www.freecodecamp.com/" target="_blank">
        FreeCodeCamp
        <i class="fab fa-free-code-camp">

        </i>
      </a>
    </P>

  </footer>
</body>
</html>
