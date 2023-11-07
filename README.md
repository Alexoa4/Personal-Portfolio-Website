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

<h2>Actual Project Development: CSS</h2>

body{
font-family: 'Poppins', sans-serif;
font-size: 1.8rem;
font-weight: 400;
line-height: 1.4;
color:#f0f0f0;
}
*{
  margin: 0;
  padding: 0;
}

@media screen(max-width: 75em) {
  
}

html{
  box-sizing: border-box;
  font-size: 62.5%;
  scroll-behavior: smooth;
}


.nav{
  display: flex;
  justify-content: flex-end;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background: #be3144;
  box-shadow: 0 2px 0;
  z-index: 10;
}

.nav-list{
  display: flex;
  margin-right: 2rem;

}
@media screen (max-width: 28.75;) {
  .nav {
    justify-content: center;
  }
}

.nav-list a {
  display:block;
  font-size: 3.2rem;
  padding: 2rem;
}

.nav-list a:hover{
  background: greenyellow;
}
ul{
  list-style-type: none ;
}
a {
  text-decoration: none;
  color:#f0f0f0;
}

h1, 
h2{
  font-family: 'Times New Roman', Times, serif;
  font-weight: 700;
  text-align:center ;
}

h1 {
  font-size: 7.0rem;
}

h2 {
  font-size: 4.2rem;
}

.welcome-section{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100vh;
  background-color: #000;
  background-image: linear-gradient(62deg, #3a3d40, #181719 100%);
}

.welcome-section > p {
  font-size: 3rem;
  font-weight: 200;
  font-style: italic;
  color: #be3144;
}

/*Poject Section*/
.projects-section{
text-align: center;
padding: 10rem 2rem;
background: #45567d;
}

.projects-section-header{
  max-width: 640px;
  margin: 0 auto 6rem auto;
  border-bottom: 0.2rem solid #f0f0f0;
}

@media (max-width: 28.75em){
  .project-section-header{
    font-size: 4rem;
  }
}

/*autoatic image grid using no media queries */
.projects-grid{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr) );
  grid-gap: 4rem;
  width: 100%;
  max-width: 1280px;
  margin: 0 auto;
  margin-bottom: 6rem;
}

.project{
  background:#303841;
  box-shadow: 1px 1px 2px rgb(0, 0, 0, 0.5);
  border-radius: 2px;
}

.code{
  color: #303841;
  transition: color 0.3s ease-out;
}
.project:hover .code{
  color: #ff7f50;
}

.project-image {
  height: calc(100% - 6.8rem);
  width: 100%;
  object-fit: cover;
}
.project-title{
  font-size: 2rem;
  padding: 2rem 0.5rem;
}

.btn {
  display: inline-block;
  padding: 1rem 2rem;
  border-radius: 2px;
}
.btn-show-all{
  font-size: 3rem;
  background: #303841;
  transition: background 0.3s ease-out;

}

.btn-show-all:hover{
  background: #be3144;
}
.btn-show-all:hover > i{
  transform: translateX(2px);
}
.btn-show-all > i {
  margin-left: 10px;
  transform: translateX(0);
  transition: transform 0.3s ease-out;

}

/* Contact Section */
.contact-section{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  width: 100%;
  height: 80vh;
  padding: 0 2rem;
  background: #303841;
}

.contact-section-header > h2 {
font-size: 6rem;
}

@media (max-width: 28.75){
  .contact-section-header > h2 {
    font-size: 4rem;
  }
  
}

.contact-section-header > p {
  font-style: italic;
}

.contact-links{
display: flex;
justify-content: center;
width: 100%;
max-width: 980px;
margin-top: 4rem;
flex-wrap: wrap;
}

.contact-details{
  font-size: 2.1rem;
  text-shadow: 2px 2px 1px #1f1f1f;
  transition: transform 0.3s ease-out;
}
.contact-details:hover {
  transform: translateY(8px);
}

/* footer*/
footer{
  font-weight: 300;
  display: flex;
  justify-content: space-evenly;
  padding: 2rem;
  background: #303841;
  border-top:4px solid #be3144;
}
footer > p{
  margin: 2rem;

}
footer > i {
  vertical-align: middle;
}
