<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Noel Jr Relao | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }
    html {
      scroll-behavior: smooth;
    }
    body {
      margin: 0;
      padding: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f5f5f5;
      color: #333;
      line-height: 1.6;
    }
    h1, h2, p {
      margin: 10px;
    }
    h2 {
      color: #222;
      border-bottom: 2px solid #4a90a4;
      padding-bottom: 8px;
      display: inline-block;
    }
    /* Navbar */
    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      overflow: hidden;
      background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
      position: fixed;
      top: 0;
      width: 94.5%;
      z-index: 1000;
      box-shadow: 0 2px 10px rgba(0,0,0,0.2);
    }
    nav ul li.left {
      float: left;
    }
    nav ul li {
      float: right;
    }
    nav ul li a {
      display: block;
      color: white;
      text-align: center;
      padding: 16px 20px;
      text-decoration: none;
      font-weight: 500;
      transition: all 0.3s ease;
    }
    nav ul li a:hover {
      background-color: #4a90a4;
      transform: translateY(-2px);
    }
    nav ul li.left a {
      font-weight: 700;
      font-size: 1.1em;
    }
    main {
      padding-top: 70px;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: 0 auto;
    }
    #name {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
      margin-bottom: 20px;
    }
    #name h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
    }
    #name p {
      font-size: 1.2em;
      opacity: 0.95;
    }
    #name a img {
      transition: transform 0.3s ease;
      margin: 5px;
    }
    #name a img:hover {
      transform: scale(1.05);
    }
    .card {
      background: white;
      border-radius: 10px;
      padding: 25px;
      margin: 20px auto;
      max-width: 900px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.08);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .card:hover {
      transform: translateY(-3px);
      box-shadow: 0 8px 25px rgba(0,0,0,0.12);
    }
    .card ul {
      list-style-type: none;
      padding-left: 0;
    }
    .card ul li {
      padding: 8px 0;
      padding-left: 25px;
      position: relative;
    }
    .card ul li::before {
      content: ">";
      position: absolute;
      left: 0;
      color: #4a90a4;
      font-weight: bold;
    }
    /* Tech Stack */
    #tech .badges {
      text-align: center;
      padding: 20px 0;
    }
    #tech .badges img {
      margin: 5px;
      transition: transform 0.3s ease;
    }
    #tech .badges img:hover {
      transform: scale(1.1);
    }
    /* Projects Table */
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 20px 0;
    }
    table th, table td {
      padding: 15px;
      text-align: left;
      border-bottom: 1px solid #eee;
    }
    table th {
      background-color: #4a90a4;
      color: white;
    }
    table tr:hover {
      background-color: #f8f9fa;
    }
    /* Footer Quote */
    .quote {
      text-align: center;
      padding: 40px 20px;
      background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
      color: white;
      margin-top: 40px;
    }
    .quote em {
      font-size: 1.2em;
      opacity: 0.9;
    }
    hr {
      display: none;
    }
  </style>
</head>
<body>

<nav>
  <ul>
    <li class="left"><a href="#name">Noel Jr.</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#tech">Tech Stack</a></li>
    <li><a href="#about">About Me</a></li>
  </ul>
</nav>

<main>
  <section id="name">
    <h1>Noel Jr Relao</h1>
    <p><strong>Web Development Student | Learning by Building</strong></p>
    <div style="margin-top: 20px;">
      <a href="https://github.com/Njr329" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-Njr329-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
      </a>
      <a href="mailto:noel@gameclubsea.com">
        <img src="https://img.shields.io/badge/Email-noel@gameclubsea.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
      </a>
    </div>
  </section>

  <div class="card" id="about">
    <h2>About Me</h2>
    <p>
      I'm a web development student passionate about creating clean, user-friendly interfaces. 
      I believe in learning by doing — building real projects, making mistakes, and improving every day.
    </p>
    <p><strong>My approach:</strong></p>
    <ul>
      <li>Structure and consistency in code</li>
      <li>Attention to the small details</li>
      <li>Always seeking to improve</li>
    </ul>
  </div>

  <div class="card" id="tech">
    <h2>Tech Stack</h2>
    <div class="badges">
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
      <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
      <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"/>
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
    </div>
  </div>

  <div class="card" id="projects">
    <h2>Projects</h2>
    <table>
      <thead>
        <tr>
          <th>Project</th>
          <th>Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><strong>TPS Transaction Processing System</strong></td>
          <td>It's my first creating web based TPS for capstone.</td>
        </tr>
        <tr>
          <td><strong>Responsive landing page</strong></td>
          <td>First layout using HTML, CSS, and Bootstrap</td>
        </tr>
      </tbody>
    </table>
  </div>

  <div class="card" id="learning">
    <h2>Currently Learning</h2>
    <ul>
      <li>Web Development</li>
      <li>Frontend project architecture</li>
      <li>JavaScript</li>
    </ul>
  </div>

  <div class="quote">
    <em>"Every sunrise is a second chance to shine."</em>
  </div>
</main>

</body>
</html>
