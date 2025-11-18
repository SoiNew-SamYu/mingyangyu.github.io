# mingyangyu.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mingyang Yu | Personal Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      line-height: 1.6;
    }
    header {
      background: #333;
      color: #fff;
      padding: 1rem 0;
    }
    header nav {
      display: flex;
      justify-content: center;
    }
    header nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 1rem;
    }
    header nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    h1, h2 {
      color: #333;
    }
    footer {
      background: #f4f4f4;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <!-- Navigation -->
  <header>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#resume">Resume</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero / Intro -->
  <section id="home">
    <h1>Your Name</h1>
    <p>Welcome to my personal website. </p>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>[Placeholder]</p>
  </section>

<section id="projects">
  <h2>Projects</h2>

  <!-- Project 1 -->
  <div class="project">
    <img src="images/friction_test.png" alt="Friction Test Setup" />
    <h3>Friction Test Setup & Analysis</h3>
    <p>
      Designed and built a friction testing apparatus to evaluate the effect of sample geometry
      on vacuum-based gripping performance.
    </p>
  </div>

  <!-- Project 2 -->
  <div class="project">
    <img src="images/robot_control.png" alt="Robot Control System" />
    <h3>Real Robot Control Framework</h3>
    <p>
      Developed control software for a Unitree Go1 robot with a custom gripper, integrating ROS,
      joystick teleoperation, and safety constraints.
    </p>
  </div>

  <!-- Project 3 -->
  <div class="project">
    <img src="images/tdmpc.png" alt="TD-MPC RL Project" />
    <h3>TD-MPC Reinforcement Learning Implementation</h3>
    <p>
      Implemented TD-MPC with diffusion-style trajectory optimization for robotic control tasks.
    </p>
  </div>

</section>

  <!-- Resume Section -->
  <section id="resume">
    <h2>Resume</h2>
    <p>[Placeholder: resume]</p>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:myu3@andrew.cmu.edu">your.email@example.com</a></p>
    <p>LinkedIn: <a href="#">linkedin.com/in/yourprofile</a></p>
    <p>GitHub: <a href="#">github.com/yourusername</a></p>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Mingyang Yu. All Rights Reserved.</p>
  </footer>
</body>
</html>
