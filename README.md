# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Abhay Tripathi | Machine Learning Enthusiast</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #1db954;
      --dark-bg: #121212;
      --accent: #1ed760;
      --text: #ffffff;
      --card-bg: #1e1e1e;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background-color: var(--dark-bg);
      color: var(--text);
      line-height: 1.6;
      padding: 2rem;
    }

    header {
      text-align: center;
      padding: 2rem 1rem;
    }

    header h1 {
      font-size: 2.5rem;
      color: var(--accent);
    }

    header p {
      font-size: 1.2rem;
      color: #ccc;
    }

    main {
      display: grid;
      gap: 2rem;
      max-width: 1000px;
      margin: 0 auto;
    }

    section {
      background-color: var(--card-bg);
      padding: 2rem;
      border-radius: 1rem;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }

    h2 {
      color: var(--accent);
      margin-bottom: 1rem;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li {
      margin-bottom: 0.5rem;
    }

    a {
      color: var(--primary);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 2rem;
      color: #888;
    }

    .toast {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: var(--accent);
      color: #000;
      padding: 1rem 2rem;
      border-radius: 10px;
      font-weight: bold;
      display: none;
    }

    .project-box {
      background-color: #2d2d2d;
      border-radius: 1rem;
      padding: 2rem;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
      margin-bottom: 2rem;
    }

    .project-box h3 {
      color: var(--accent);
      margin-bottom: 1rem;
    }

    .project-box p {
      color: #ccc;
      margin-bottom: 1rem;
    }

    .certifications {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
    }

    .cert {
      background-color: #2d2d2d;
      padding: 1rem;
      border-radius: 1rem;
      width: 300px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
    }

    .cert h3 {
      font-size: 1.2rem;
      color: var(--accent);
    }

    .cert p {
      color: #ccc;
    }

    .cert img {
      width: 100%;
      max-width: 600px;
      border-radius: 10px;
      margin-top: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Abhay Tripathi</h1>
    <p>Machine Learning Enthusiast | CSE 3rd Year Student</p>
  </header>

  <main>
    <section>
      <h2>About Me</h2>
      <p>I am a tech-driven Machine Learning enthusiast and a 3rd-year B.Tech CSE student, passionate about turning real-world problems into intelligent solutions using Python, C++, and modern tools.</p>
    </section>

    <section>
      <h2>Skills</h2>
      <ul>
        <li>C++, Python, HTML</li>
        <li>Figma (UI/UX Design)</li>
        <li>Git & GitHub</li>
        <li>Problem Solving, NLP</li>
      </ul>
    </section>

    <section>
      <h2>Projects</h2>

      <div class="project-box">
        <h3>Banking Management System</h3>
        <p>A C++ console application simulating banking operations such as account creation, balance checking, fund transfers, and withdrawal/deposit functionality. This project helped enhance my skills in C++ and object-oriented programming, particularly for managing real-world operations in a console environment.</p>
      </div>

      <div class="project-box">
        <h3>Tweet Sentiment Analysis</h3>
        <p>A Python project that uses Natural Language Processing (NLP) to analyze Twitter data. This project involved extracting tweets using the Twitter API, processing the data, and classifying sentiments into positive, neutral, and negative categories. It improved my understanding of text processing and sentiment analysis.</p>
      </div>

      <div class="project-box">
        <h3>Travel App Prototype</h3>
        <p>Designed in Figma, this project focuses on a travel app that allows users to explore popular destinations, manage bookings, and track their travel itinerary. The user interface prioritizes a clean, modern design with a dark theme and intuitive navigation, providing an immersive experience for travelers.</p>
      </div>
    </section>

    <section id="certifications">
      <h2>Certifications</h2>
      <div class="certifications">
        <div class="cert">
          <h3>Machine Learning Specialization</h3>
          <p><strong>Coursera</strong> | 2024</p>
        </div>
        <div class="cert">
          <h3>Generative AI for All</h3>
          <p><strong>Coursera</strong> | 2025</p>
          <img src="path/to/your/certificate-image.jpg" alt="Generative AI for All Certificate">
        </div>
      </div>
    </section>

    <section>
      <h2>Education</h2>
      <p>B.Tech in Computer Science and Engineering (2022–2026)<br />University – 3rd Year</p>
    </section>

    <section>
      <h2>Contact</h2>
      <p>Email: <a href="mailto:tripathiabhay87@gmail.com">tripathiabhay87@gmail.com</a></p>
      <p>Phone: +91 8808242193</p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/abhaytripathi1/" target="_blank">linkedin.com/in/abhaytripathi1</a></p>
      <p>GitHub: <a href="https://github.com/abhay051" target="_blank">github.com/abhay051</a></p>
    </section>
  </main>

  <footer>
    <p>© 2025 Abhay Tripathi — Built with ❤️ and a love for Machine Learning</p>
  </footer>

  <div class="toast" id="welcomeToast">Welcome to my portfolio!</div>

  <script>
    window.onload = () => {
      const toast = document.getElementById("welcomeToast");
      toast.style.display = "block";
      setTimeout(() => {
        toast.style.display = "none";
      }, 3000);
    };
  </script>
</body>
</html>
