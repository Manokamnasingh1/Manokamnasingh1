<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Manokamna Singh | Full Stack Developer</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 40px;
      background: linear-gradient(to right, #f8f9fa, #dfe6e9);
      font-family: 'Poppins', sans-serif;
      color: #2d3436;
      line-height: 1.6;
      animation: fadeIn 1s ease-in;
    }

    h1 {
      font-size: 2.5rem;
      color: #7D5FFF;
      font-weight: 800;
    }

    h2 {
      color: #FFA502;
    }

    h3 {
      color: #E17055;
    }

    .section {
      margin-bottom: 30px;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li {
      margin: 10px 0;
      display: flex;
      align-items: center;
    }

    li img {
      margin-right: 10px;
      width: 24px;
      animation: float 2s infinite ease-in-out;
    }

    a {
      color: #0984E3;
      text-decoration: none;
      font-weight: 600;
      transition: all 0.3s ease;
    }

    a:hover {
      color: #6c5ce7;
      transform: scale(1.05);
    }

    .social-icons img {
      width: 30px;
      margin-right: 10px;
      transition: transform 0.3s ease;
    }

    .social-icons a:hover img {
      transform: scale(1.2);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-5px); }
    }
  </style>
</head>
<body>

  <div class="section">
    <h1>👋 Hi, I’m <span style="color:#7D5FFF;">Manokamna Singh</span></h1>
    <p>I am a <strong>Full Stack Web Developer</strong></p>
  </div>

  <div class="section">
    <h2>👀 Interests</h2>
    <ul>
      <li><img src="https://img.icons8.com/color/32/000000/source-code.png"/> <b>Web Development</b></li>
      <li><img src="https://img.icons8.com/color/32/000000/algorithm.png"/> <b>Data Structures and Algorithms (DSA)</b></li>
      <li><img src="https://img.icons8.com/color/32/000000/idea.png"/> <b>Problem Solving</b></li>
    </ul>
  </div>

  <div class="section">
    <h3>💞️ Looking to Collaborate On</h3>
    <a href="https://tinyurl.com/33ar4mzz" target="_blank">
      <img src="https://img.icons8.com/color/48/domain--v2.png" width="24"/> Request For Web Designing Service
    </a>
  </div>

  <div class="section">
    <h2>🌱 Currently Learning</h2>
    <ul>
      <li><img src="https://img.icons8.com/color/32/000000/web.png"/> Web Development & Web Frameworks</li>
    </ul>
  </div>

  <div class="section">
    <h2>📫 How to Reach Me</h2>
    <div class="social-icons">
      <a href="https://manokamnasingh1.github.io/Portfolio1/" target="_blank">
        <img src="https://img.icons8.com/color/48/domain--v2.png"/> <b>Portfolio</b>
      </a> |
      <a href="https://www.instagram.com/manokamnasingh.official" target="_blank">
        <img src="https://img.icons8.com/fluency/48/instagram-new.png"/> <b>Instagram</b>
      </a> |
      <a href="https://www.facebook.com/manokamna.singh.7771/" target="_blank">
        <img src="https://img.icons8.com/color/48/facebook-new.png"/> <b>Facebook</b>
      </a>
    </div>
  </div>

</body>
</html>

