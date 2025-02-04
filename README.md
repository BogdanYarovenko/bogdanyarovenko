<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Bogdan Yarovenko | Developer</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap"
      rel="stylesheet"
    />
    <style>
      :root {
        --primary-bg: #f6f8fa; /* GitHub light background */
        --primary-text: #24292e; /* GitHub text color */
        --header-bg: #24292e; /* Dark header similar to GitHub nav */
        --header-text: #ffffff;
        --accent: #0366d6; /* GitHub blue */
        --section-bg: #ffffff;
      }
      * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
      }
      body {
        font-family: "Roboto", sans-serif;
        background: var(--primary-bg);
        color: var(--primary-text);
        line-height: 1.6;
      }
      a {
        text-decoration: none;
      }
      /* Header */
      .header {
        text-align: center;
        padding: 60px 20px;
        background: var(--header-bg);
        color: var(--header-text);
      }
      .header h1 {
        font-size: 2.8rem;
        margin-bottom: 10px;
      }
      .header h3 {
        font-weight: 300;
        font-size: 1.5rem;
      }
      /* Container */
      .container {
        max-width: 900px;
        margin: 0 auto;
        padding: 40px 20px;
      }
      .section {
        margin-bottom: 40px;
        text-align: center;
        background: var(--section-bg);
        padding: 20px;
        border-radius: 8px;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      }
      .section h3 {
        font-size: 1.8rem;
        margin-bottom: 20px;
        color: var(--primary-text);
      }
      /* Social and Tech Icons */
      .icons {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 15px;
      }
      .icons a img {
        transition: transform 0.3s ease;
        border-radius: 4px;
      }
      .icons a img:hover {
        transform: scale(1.1);
      }
      /* Footer */
      .footer {
        text-align: center;
        font-size: 0.9rem;
        color: #777;
        margin-top: 40px;
        padding: 20px 0;
        border-top: 1px solid #ddd;
      }
    </style>
  </head>
  <body>
    <header class="header">
      <h1>Hi 👋, I'm Bogdan Yarovenko</h1>
      <h3>Developer from Ukraine</h3>
    </header>
    <main class="container">
      <section class="section">
        <h3>Connect with me:</h3>
        <div class="icons">
          <a href="#" target="_blank">
            <img
              src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=Linkedin&logoColor=white"
              alt="LinkedIn"
            />
          </a>
          <a href="#" target="_blank">
            <img
              src="https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=Instagram&logoColor=white"
              alt="Instagram"
            />
          </a>
          <a href="#" target="_blank">
            <img
              src="https://img.shields.io/badge/-Facebook-1877F2?style=for-the-badge&logo=Facebook&logoColor=white"
              alt="Facebook"
            />
          </a>
        </div>
      </section>
      
   <section class="section">
        <h3>Languages:</h3>
        <div class="icons">
          <a
            href="https://www.w3schools.com/cs/"
            target="_blank"
            rel="noreferrer"
          >
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg"
              alt="C#"
              width="40"
              height="40"
            />
          </a>
          <a
            href="https://www.w3schools.com/css/"
            target="_blank"
            rel="noreferrer"
          >
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg"
              alt="CSS3"
              width="40"
              height="40"
            />
          </a>
          <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg"
              alt="HTML5"
              width="40"
              height="40"
            />
          </a>
          <a href="https://www.java.com" target="_blank" rel="noreferrer">
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg"
              alt="Java"
              width="40"
              height="40"
            />
          </a>
          <a
            href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"
            target="_blank"
            rel="noreferrer"
          >
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg"
              alt="JavaScript"
              width="40"
              height="40"
            />
          </a>
          <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg"
              alt="MySQL"
              width="40"
              height="40"
            />
          </a>
          <a href="https://www.python.org" target="_blank" rel="noreferrer">
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"
              alt="Python"
              width="40"
              height="40"
            />
          </a>
        </div>
      </section>


  <section class="section">
        <h3>Frameworks:</h3>
        <div class="icons">
          <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer">
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg"
              alt="Pandas"
              width="40"
              height="40"
            />
          </a>
          <a href="https://matplotlib.org/" target="_blank" rel="noreferrer">
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg"
              alt="Matplotlib"
              width="40"
              height="40"
            />
          </a>
          <a href="https://numpy.org/" target="_blank" rel="noreferrer">
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original-wordmark.svg"
              alt="NumPy"
              width="40"
              height="40"
            />
          </a>
          <a href="https://wordpress.org/" target="_blank" rel="noreferrer">
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/wordpress/wordpress-plain.svg"
              alt="WordPress"
              width="40"
              height="40"
            />
          </a>
        </div>
      </section>

   
  <section class="section">
        <h3>Tools:</h3>
        <div class="icons">
          <a href="https://www.figma.com/" target="_blank" rel="noreferrer">
            <img
              src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg"
              alt="Figma"
              width="40"
              height="40"
            />
          </a>
          <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
            <img
              src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg"
              alt="Git"
              width="40"
              height="40"
            />
          </a>
          <a
            href="https://code.visualstudio.com/"
            target="_blank"
            rel="noreferrer"
          >
            <img
              src="https://www.vectorlogo.zone/logos/visualstudio_code/visualstudio_code-icon.svg"
              alt="VS Code"
              width="40"
              height="40"
            />
          </a>
          <a
            href="https://www.jetbrains.com/idea/"
            target="_blank"
            rel="noreferrer"
          >
            <img
              src="https://www.vectorlogo.zone/logos/jetbrains/jetbrains-icon.svg"
              alt="IntelliJ"
              width="40"
              height="40"
            />
          </a>
        </div>
      </section>
    </main>

  <footer class="footer">
      <p>&copy; 2025 Bogdan Yarovenko. All rights reserved.</p>
    </footer>
  </body>
</html>
