<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Personal Portfolio</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #0f0f0f; color: #e0e0e0; }
    header { background: #000000; color: #ffffff; padding: 40px 20px; text-align: center; }
    header h1 { margin: 0; font-size: 2.5rem; }

    .container { width: 90%; max-width: 1000px; margin: auto; background: #1a1a1a; padding: 30px; border-radius: 12px; margin-top: -20px; box-shadow: 0 4px 10px rgba(255,255,255,0.05); }
    .profile-img { width: 160px; height: 160px; border-radius: 50%; display: block; margin: 20px auto; object-fit: cover; border: 3px solid #333; }

    h2 { border-left: 5px solid #5e5e5e; padding-left: 10px; margin-top: 40px; color: #ffffff; }

    .projects { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-top: 20px; }
    .project { background: #262626; padding: 20px; border-radius: 10px; box-shadow: 0 2px 6px rgba(255,255,255,0.05); }
    .project h3 { margin-top: 0; color: #ffffff; }

    footer { margin-top: 40px; padding: 20px; text-align: center; color: #888; }
  </style>
</head>
<body>
  <header>
    <h1>Student Name</h1>
    <p>Welcome to my personal portfolio website</p>
  </header>

  <div class="container">
    <img src="your-photo.jpg" alt="Profile Photo" class="profile-img">

    <h2>About Me</h2>
    <p>Hello! I'm a student passionate about technology, creativity, and building cool projects. This website showcases my background, interests, and the work I’ve done.</p>

    <h2>Projects</h2>
    <div class="projects">
      <div class="project">
        <h3>Project One</h3>
        <p>A short description of your project. Explain what it does and what tools you used.</p>
      </div>
      <div class="project">
        <h3>Project Two</h3>
        <p>Another cool project. Describe the purpose and what you learned.</p>
      </div>
      <div class="project">
        <h3>Project Three</h3>
        <p>Describe the project, its features, and any interesting background.</p>
      </div>
    </div>

    <h2>Contact</h2>
    <p>Email: your.email@example.com</p>
    <p>GitHub: https://github.com/yourusername</p>
  </div>

  <footer>
    © 2025 Your Name — Portfolio
  </footer>
</body>
</html>
