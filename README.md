<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>A. Karthik | Portfolio</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: linear-gradient(135deg, #74ebd5, #ACB6E5);
      color: #333;
    }

    header {
      background: linear-gradient(90deg, #2575fc, #6a11cb);
      color: white;
      padding: 40px 0;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
    }

    header h1 {
      font-size: 2.8em;
      letter-spacing: 2px;
    }

    header p {
      font-size: 1.2em;
      margin-top: 8px;
    }

    section {
      background: white;
      margin: 40px auto;
      width: 90%;
      max-width: 900px;
      padding: 25px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    h2 {
      color: #6a11cb;
      margin-bottom: 15px;
      border-bottom: 3px solid #6a11cb;
      display: inline-block;
      padding-bottom: 5px;
    }

    ul {
      list-style: none;
      line-height: 1.8;
      padding-left: 0;
    }

    ul li::before {
      content: "🎯 ";
      margin-right: 8px;
      color: #2575fc;
    }

    .skills span, .hobbies span {
      display: inline-block;
      background: #2575fc;
      color: white;
      padding: 8px 15px;
      border-radius: 20px;
      margin: 5px;
      font-size: 0.9em;
      transition: 0.3s;
    }

    .skills span:hover, .hobbies span:hover {
      background: #6a11cb;
      transform: scale(1.1);
    }

    footer {
      text-align: center;
      padding: 20px;
      background: linear-gradient(90deg, #6a11cb, #2575fc);
      color: white;
      margin-top: 30px;
      border-top-left-radius: 20px;
      border-top-right-radius: 20px;
    }

    .contact a {
      color: #2575fc;
      text-decoration: none;
      font-weight: bold;
    }

    .contact a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <h1>A. Karthik</h1>
    <p>🎓 B.Tech Student | 💻 Aspiring Software Engineer</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>Hello! I’m <b>A. Karthik</b>, a passionate and motivated B.Tech student from SR University, Warangal. 
       I’m enthusiastic about technology, problem-solving, and continuous learning. 
       My goal is to contribute to the tech industry through innovative ideas and strong technical skills.</p>
  </section>

  <section>
    <h2>Education</h2>
    <ul>
      <li><b>SR University, Warangal</b> — B.Tech (Current)</li>
      <li><b>Narayana Junior College</b>, Siddipet — 971 Marks</li>
      <li><b>Srivani High School</b>, Siddipet — 9.8 GPA</li>
    </ul>
  </section>

  <section>
    <h2>Skills</h2>
    <div class="skills">
      <span>HTML</span>
      <span>CSS</span>
      <span>JavaScript</span>
      <span>Python</span>
      <span>C Programming</span>
      <span>Problem Solving</span>
      <span>Teamwork</span>
      <span>Communication</span>
    </div>
  </section>

  <section>
    <h2>Projects</h2>
    <ul>
      <li><b>Portfolio Website</b> — Designed a personal website using HTML, CSS, and JavaScript.</li>
      <li><b>Student Management System</b> — Created a system to manage student records using Python.</li>
      <li><b>IoT Smart Home Prototype</b> — Developed a model for home automation using Arduino.</li>
    </ul>
  </section>

  <section>
    <h2>Hobbies</h2>
    <div class="hobbies">
      <span>📷 Photography</span>
      <span>🏏 Playing Cricket</span>
      <span>📚 Learning New Skills</span>
      <span>🎮 Gaming</span>
    </div>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:avadoothakarthik7@gmail.com">avadoothakarthik7@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/avadootha-karthik-7ba73b342" target="_blank">linkedin.com/in/avadootha-karthik</a></p>
    <p>GitHub: <a href="https://github.com/karthik5251/Portfolio" target="_blank">github.com/karthik5251</a></p>
  </section>

  <footer>
    <p>© 2025 A. Karthik | Designed with 💜 using HTML & CSS</p>
  </footer>

</body>
</html>
