<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Luis Mendez | ML Engineer</title>

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">

<!-- Font Awesome Icons -->
<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"
/>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Inter', sans-serif;
  }

  body {
    background: #0f172a;
    color: #e2e8f0;
    line-height: 1.6;
  }

  header {
    text-align: center;
    padding: 80px 20px 40px 20px;
  }

  header h1 {
    font-size: 3rem;
    font-weight: 800;
  }

  header p {
    margin-top: 15px;
    font-size: 1.1rem;
    color: #94a3b8;
  }

  .section {
    padding: 60px 20px;
    max-width: 1000px;
    margin: auto;
  }

  .section h2 {
    font-size: 2rem;
    margin-bottom: 30px;
    text-align: center;
  }

  .tech-stack {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 12px;
  }

  .badge {
    background: #1e293b;
    padding: 8px 16px;
    border-radius: 999px;
    font-size: 0.9rem;
    border: 1px solid #334155;
  }

  .focus {
    text-align: center;
    font-size: 1.1rem;
    color: #cbd5e1;
  }

  /* CONNECT SECTION */
  .connect-container {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
    margin-top: 30px;
  }

  .connect-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 150px;
    height: 150px;
    border-radius: 20px;
    text-decoration: none;
    color: white;
    font-weight: 600;
    transition: all 0.3s ease;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);
  }

  .connect-card i {
    font-size: 2.2rem;
    margin-bottom: 10px;
  }

  .connect-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.6);
  }

  .linkedin { background: #0a66c2; }
  .kaggle { background: #20beff; }
  .hackerrank { background: #2ec866; }

  footer {
    text-align: center;
    padding: 40px;
    font-size: 0.9rem;
    color: #64748b;
  }

  @media (max-width: 768px) {
    header h1 {
      font-size: 2.2rem;
    }

    .connect-card {
      width: 120px;
      height: 120px;
    }
  }
</style>
</head>

<body>

<header>
  <h1>Luis Mendez 👋</h1>
  <p>
    🎓 Computer Science & Engineering + Mathematics @ UConn<br>
    🧠 Applied Machine Learning | Computer Vision | Dataset Engineering<br>
    📍 Connecticut, USA
  </p>
</header>

<section class="section">
  <h2>🛠 Tech Stack</h2>
  <div class="tech-stack">
    <span class="badge">Python</span>
    <span class="badge">C++</span>
    <span class="badge">TypeScript</span>
    <span class="badge">PyTorch</span>
    <span class="badge">OpenCV</span>
    <span class="badge">NumPy</span>
    <span class="badge">Scikit-Learn</span>
    <span class="badge">Vision Transformers</span>
    <span class="badge">Linux</span>
    <span class="badge">Git</span>
    <span class="badge">Docker</span>
    <span class="badge">VS Code</span>
    <span class="badge">Streamlit</span>
  </div>
</section>

<section class="section">
  <h2>📊 Current Focus</h2>
  <p class="focus">
    Designing scalable, human-in-the-loop AI systems for infrastructure image understanding and evaluation.
  </p>
</section>

<section class="section">
  <h2>📫 Connect</h2>
  <div class="connect-container">

    <a href="https://linkedin.com/in/luis-mendez-reyes" target="_blank" class="connect-card linkedin">
      <i class="fab fa-linkedin"></i>
      <span>LinkedIn</span>
    </a>

    <a href="https://kaggle.com/luismndezreyes" target="_blank" class="connect-card kaggle">
      <i class="fab fa-kaggle"></i>
      <span>Kaggle</span>
    </a>

    <a href="https://hackerrank.com/profile/luismendezr12" target="_blank" class="connect-card hackerrank">
      <i class="fab fa-hackerrank"></i>
      <span>HackerRank</span>
    </a>

  </div>
</section>

<footer>
  © 2026 Luis Mendez • Built with HTML & CSS
</footer>

</body>
</html>
