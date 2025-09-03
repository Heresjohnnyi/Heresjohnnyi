<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>S. Muralikarthik | Data Engineer & Analytics</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background: #f5f5f5;
      color: #333;
    }

    /* Header with Background */
    .header {
      background: url('https://images.unsplash.com/photo-1557683316-973673baf926?auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
      height: 50vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
      position: relative;
    }

    .header::after {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0,0,0,0.5);
      z-index: 1;
    }

    .header h1, .header h3 {
      position: relative;
      z-index: 2;
      margin: 0.5rem;
    }

    /* Container */
    .container {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    /* Social Links */
    .social-links a {
      margin: 0 0.5rem;
      display: inline-block;
    }

    .social-links img {
      width: 40px;
      height: 40px;
    }

    /* Tools / Languages */
    .tools img {
      width: 50px;
      height: 50px;
      margin: 0.5rem;
    }

    /* Sections */
    section {
      margin-bottom: 2rem;
      text-align: center;
    }

    /* Buy Me a Coffee */
    .coffee-btn img {
      width: 220px;
      height: 50px;
    }

    @media (max-width: 768px) {
      .tools img {
        width: 40px;
        height: 40px;
        margin: 0.3rem;
      }
      .social-links img {
        width: 35px;
        height: 35px;
      }
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <div class="header">
    <h1>Hi 👋, I'm S. Muralikarthik</h1>
    <h3>Aspiring Data Engineer & Analytics Practitioner | Scalable Data Processing | AI & ML | Distributed Systems</h3>
  </div>

  <div class="container">

    <!-- Social Links -->
    <section>
      <h2>🌐 Connect with Me</h2>
      <div class="social-links">
        <a href="https://linkedin.com/in/muralikarthik7090" target="_blank"><img src="https://img.icons8.com/ios-filled/50/000000/linkedin.png" alt="LinkedIn"></a>
        <a href="https://medium.com/@muralikarthik7090" target="_blank"><img src="https://img.icons8.com/ios-filled/50/000000/medium-monogram.png" alt="Medium"></a>
        <a href="https://codeforces.com/profile/mura" target="_blank"><img src="https://img.icons8.com/ios-filled/50/000000/codeforces.png" alt="Codeforces"></a>
      </div>
    </section>

    <!-- About Me -->
    <section>
      <h2>💡 About Me</h2>
      <p>I’m a passionate <strong>Data Engineer & Analytics enthusiast</strong> who loves building <strong>scalable data pipelines</strong>, developing <strong>AI/ML models</strong>, and creating <strong>interactive analytics solutions</strong>. Every coffee you buy helps me dedicate more time to <strong>exploring new technologies</strong>, <strong>building projects</strong>, and <strong>sharing knowledge</strong> with the community.</p>
    </section>

    <!-- Tools & Languages -->
    <section>
      <h2>🛠 Languages & Tools</h2>
      <div class="tools">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL">
        <img src="https://www.vectorlogo.zone/logos/apache_spark/apache_spark-icon.svg" alt="Spark">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React">
        <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="TensorFlow">
        <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="PyTorch">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker">
        <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git">
        <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="Pandas">
      </div>
    </section>

    <!-- Buy Me a Coffee -->
    <section>
      <h2>☕ Support Me</h2>
      <div class="coffee-btn">
        <a href="https://www.buymeacoffee.com/smuralikarthik" target="_blank">
          <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee">
        </a>
      </div>
    </section>

  </div>

</body>
</html>
