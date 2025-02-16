<!DOCTYPE html>
<html lang="en">
<title>My Portfolio</title>
  <style>
    /* Basic Styling */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 10px;
    }

    .container {
      width: 80%;
      margin: 20px auto;
    }

    .about, .projects, .skills, .contact {
      background: #fff;
      padding: 20px;
      margin: 20px 0;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    .profile-img {
      display: block;
      margin: 20px auto;
      border-radius: 50%;
      width: 150px;
      height: 150px;
    }

    .project {
      margin: 20px 0;
    }

    .project h3 {
      margin: 0;
    }

    .project p {
      margin: 10px 0;
    }

    .btn {
      display: inline-block;
      padding: 10px 20px;
      background: #333;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
    }

    .btn:hover {
      background: #555;
    }

    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="container">
    <!-- About Section -->
    <section id="about" class="about">
      <h2>About Me</h2>
      <p>
        Hi, I'm [Your Name], a first-year programming student. I'm learning how to code and build cool projects. I love solving problems and creating things with code!
      </p>
      <img src="https://via.placeholder.com/150" alt="My Photo" class="profile-img">
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
      <h2>My Projects</h2>
      <div class="project">
        <h3>Project 1: Simple Calculator</h3>
        <p>A basic calculator built using HTML, CSS, and JavaScript.</p>
        <a href="#" class="btn">View Project</a>
      </div>
      <div class="project">
        <h3>Project 2: To-Do List</h3>
        <p>A to-do list app that helps you organize your tasks.</p>
        <a href="#" class="btn">View Project</a>
      </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
      <h2>My Skills</h2>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript (Beginner)</li>
        <li>Python (Beginner)</li>
      </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
      <h2>Contact Me</h2>
      <p>If you'd like to get in touch, feel free to reach out!</p>
      <ul>
        <li>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></li>
        <li>GitHub: <a href="https://github.com/yourusername">github.com/yourusername</a></li>
      </ul>
    </section>
  </div>

  <footer>
    <p>&copy; 2023 [Your Name]. All rights reserved.</p>
  </footer>
</body>
</html>
