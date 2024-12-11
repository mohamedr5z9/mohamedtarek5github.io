# shanb55github.io
this test in git hup
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Personal Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>Nguyen Vu</h1>
      <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <section id="about" class="section">
    <div class="container">
      <h2>About Me</h2>
      <p>Hi, I'm Nguyen Vu, a passionate web developer who loves creating beautiful and functional websites.</p>
    </div>
  </section>

  <section id="projects" class="section">
    <div class="container">
      <h2>Projects</h2>
      <div class="project">
        <h3>Project 1</h3>
        <p>Description of the project.</p>
      </div>
      <div class="project">
        <h3>Project 2</h3>
        <p>Description of another project.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="section">
    <div class="container">
      <h2>Contact</h2>
      <p>Email: example@example.com</p>
      <p>LinkedIn: <a href="#">linkedin.com/in/nguyenvu</a></p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2024 Nguyen Vu. All rights reserved.</p>
    </div>
  </footer>

  <script>
    // Smooth scrolling for navigation links
    document.querySelectorAll('nav a').forEach(link => {
      link.addEventListener('click', function(e) {
        e.preventDefault();
        const targetId = this.getAttribute('href').substring(1);
        document.getElementById(targetId).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });

    // Simple alert for project clicks
    document.querySelectorAll('.project').forEach(project => {
      project.addEventListener('click', () => {
        alert('More details about this project coming soon!');
      });
    });
  </script>
</body>
</html>
