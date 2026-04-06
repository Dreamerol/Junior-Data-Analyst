# PORTFOLIO

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dreamerol Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body { margin:0; font-family: 'Roboto', sans-serif; background: #f5f5f5; color: #333; }
    header { text-align:center; padding:60px 20px; background:#4B7BEC; color:white; }
    header h1 { font-size:3em; margin:0; }
    header p { font-size:1.2em; margin:10px 0; }
    .btn { display:inline-block; margin:10px; padding:10px 20px; background:#FFB400; color:white; text-decoration:none; border-radius:5px; font-weight:bold; }
    
    section { padding:60px 20px; max-width:1200px; margin:auto; }
    h2 { text-align:center; margin-bottom:40px; font-size:2em; color:#333; }

    /* Tech Stack */
    .tech-stack { display:flex; justify-content:center; flex-wrap:wrap; gap:20px; }
    .tech-card { background:white; padding:20px; border-radius:10px; text-align:center; width:120px; box-shadow:0 4px 8px rgba(0,0,0,0.1);}
    .tech-card img { width:60px; height:60px; margin-bottom:10px; }

    /* Projects */
    .projects { display:flex; flex-wrap:wrap; gap:30px; justify-content:center; }
    .project-card { background:white; width:300px; border-radius:10px; box-shadow:0 4px 12px rgba(0,0,0,0.1); overflow:hidden; text-align:center; }
    .project-card img { width:100%; height:180px; object-fit:cover; }
    .project-card h3 { margin:15px 0 5px 0; }
    .project-card p { font-size:0.95em; padding:0 15px; margin-bottom:10px; }
    .project-card .badge { display:inline-block; background:#4B7BEC; color:white; padding:5px 10px; margin:5px; border-radius:5px; font-size:0.8em; }
    .project-card a { display:inline-block; margin:10px; padding:8px 15px; background:#FFB400; color:white; text-decoration:none; border-radius:5px; font-weight:bold; }

    /* Footer */
    footer { text-align:center; padding:30px; background:#333; color:white; }
  </style>
</head>
<body>

<!-- Hero Section -->
<header>
  <h1>Milena Mihaylova</h1>
  <p>Python | Machine Learning | SQL | Algorithms | Neural Networks</p>
  <a href="#projects" class="btn">View Projects</a>
  <a href="https://github.com/Dreamerol" class="btn">GitHub</a>
  <a href="https://www.linkedin.com/in/dreamerol" class="btn">LinkedIn</a>
</header>

<!-- Tech Stack Section -->
<section id="tech">
  <h2>Tech Stack</h2>
  <div class="tech-stack">
    <div class="tech-card">
      <img src="https://cdn-icons-png.flaticon.com/512/5968/5968350.png" alt="Python">
      <p>Python</p>
    </div>
    <div class="tech-card">
      <img src="https://cdn-icons-png.flaticon.com/512/919/919836.png" alt="C++">
      <p>C++</p>
    </div>
    <div class="tech-card">
      <img src="https://cdn-icons-png.flaticon.com/512/919/919836.png" alt="SQL">
      <p>SQL</p>
    </div>
    <div class="tech-card">
      <img src="https://cdn-icons-png.flaticon.com/512/5968/5968672.png" alt="TensorFlow">
      <p>TensorFlow</p>
    </div>
    <div class="tech-card">
      <img src="https://cdn-icons-png.flaticon.com/512/919/919825.png" alt="Django">
      <p>Django</p>
    </div>
    <div class="tech-card">
      <img src="https://cdn-icons-png.flaticon.com/512/2111/2111425.png" alt="Git">
      <p>Git</p>
    </div>
  </div>
</section>

<!-- Projects Section -->
<section id="projects">
  <h2>Featured Projects</h2>
  <div class="projects">
    
    <div class="project-card">
      <img src="https://raw.githubusercontent.com/Dreamerol/Dreamerol/main/assets/nn_3d.png" alt="3D Vector Classification">
      <h3>3D Vector Classification</h3>
      <p>Python ML project classifying 3D vectors with neural networks. Demonstrates mathematical reasoning and data visualization.</p>
      <span class="badge">Python</span>
      <span class="badge">TensorFlow</span>
      <a href="https://github.com/Dreamerol/Neural_Networks_Lab" target="_blank">View Code</a>
    </div>
    
    <div class="project-card">
      <img src="https://raw.githubusercontent.com/Dreamerol/Dreamerol/main/assets/sales_predictor.png" alt="Profit Predictor">
      <h3>Profit Predictor</h3>
      <p>Machine Learning model for seasonal sales and profit optimization. Uses historical data to forecast trends.</p>
      <span class="badge">Python</span>
      <span class="badge">ML</span>
      <a href="https://github.com/Dreamerol/Profit_Predictor" target="_blank">View Code</a>
    </div>

    <div class="project-card">
      <img src="https://raw.githubusercontent.com/Dreamerol/Dreamerol/main/assets/placebo_effect.png" alt="Placebo Effect Analysis">
      <h3>Placebo Effect Analysis</h3>
      <p>Data Analysis project on placebo treatment outcomes. Demonstrates statistical reasoning and Python analysis skills.</p>
      <span class="badge">Python</span>
      <span class="badge">Data Analysis</span>
      <a href="https://github.com/Dreamerol/Placebo_Effect" target="_blank">View Code</a>
    </div>

  </div>
</section>

<!-- Footer -->
<footer>
  &copy; 2026 Milena Mihaylova | <a href="https://github.com/Dreamerol" style="color:#FFB400;">GitHub</a> | <a href="https://www.linkedin.com/in/dreamerol" style="color:#FFB400;">LinkedIn</a>
</footer>

</body>
</html>
