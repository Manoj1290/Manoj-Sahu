<!DOCTYPE html>
<html> 
<head>  
  <meta charset="UTF-8">
  <title>Manoj Sahu - Data Analyst</title>
  <style>
    /* CSS styles for the portfolio website */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
    }
    .container {
      max-width: 800px;
      margin: 40px auto;
      padding: 20px;
    }
    .about-me {
      text-align: center;
      margin-bottom: 30px;
    }
    .projects {
      margin-bottom: 30px;
    }
    .project {
      margin-bottom: 20px;
      padding: 20px;
      background-color: #f4f4f4;
    }
    .project h3 {
      margin-top: 0;
    }
    .contact {
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <h1>Manjo Sahu</h1>
    <h2>Data Analyst</h2>
  </header>

  <div class="container">
    <section class="about-me">
      <h2>About Me</h2>
      <p>Welcome to my portfolio website! I am a data analyst with expertise in analyzing and interpreting complex data sets. I am passionate about extracting meaningful insights to drive informed business decisions.</p>
    </section>

    <section class="projects">
      <h2>Projects</h2>
      <div class="project">
        <h3>Project 1: Sales Analysis</h3>
        <p>Description of Project 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      </div>
      <div class="project">
        <h3>Project 2: Customer Segmentation</h3>
        <p>Description of Project 2. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      </div>
      <!-- Add more projects here -->
    </section>

    <section class="contact">
      <h2>Contact Me</h2>
      <p>Feel free to reach out to me. Email: manojsahu2114@gmail.com</p>
     </section>
  </div>

  <script>
    // JavaScript code for the portfolio website
    // Add interactivity or functionality here

    // Example: Display an alert when the contact form is submitted
    var contactForm = document.querySelector('.contact form');
    contactForm.addEventListener('submit', function(event) {
      event.preventDefault();
      alert('Thank you for contacting me!');
    });

    // Example: Toggle visibility of project descriptions
    var projectDescriptions = document.querySelectorAll('.project p');
    projectDescriptions.forEach(function(description) {
      description.style.display = 'none'; // Hide descriptions initially
    });

    var projectTitles = document.querySelectorAll('.project h3');
    projectTitles.forEach(function(title) {
      title.addEventListener('click', function() {
        var description = this.nextElementSibling;
        if (description.style.display === 'none') {
          description.style.display = 'block';
        } else {
          description.style.display = 'none';
        }
      });
    });
  </script>
</body>
</html>
