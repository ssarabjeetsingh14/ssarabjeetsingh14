<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>GitHub README — Profile Section</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--muted:#94a3b8;--accent:#06b6d4;--glass:rgba(255,255,255,0.03)}
    *{box-sizing:border-box}
    body{font-family:Inter,system-ui,Segoe UI,Roboto,Helvetica,Arial,sans-serif;margin:24px;background:linear-gradient(180deg,#071021 0%, #081026 100%);color:#e6eef6}
    .container{max-width:900px;margin:0 auto}
    .card{background:linear-gradient(180deg,var(--card),#071026);border-radius:12px;padding:24px;box-shadow:0 6px 30px rgba(2,6,23,0.6);backdrop-filter:blur(6px)}
    header{display:flex;gap:16px;align-items:center}
    .avatar{width:84px;height:84px;border-radius:10px;background:var(--glass);display:flex;align-items:center;justify-content:center;font-weight:600;color:var(--accent);font-size:20px}
    h1{margin:0;font-size:20px}
    p.lead{margin:6px 0 0;color:var(--muted);font-size:14px}
    .grid{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-top:18px}
    .section{background:rgba(255,255,255,0.02);padding:14px;border-radius:8px}
    .section h3{margin:0 0 8px;font-size:14px}
    ul{margin:0;padding-left:18px;color:var(--muted);font-size:14px}
    .stack{display:flex;flex-wrap:wrap;gap:8px}
    .chip{padding:6px 8px;border-radius:999px;background:rgba(255,255,255,0.02);font-size:13px;color:var(--muted)}
    .projects li{margin-bottom:8px}
    .contact{display:flex;flex-direction:column;gap:6px}
    a{color:var(--accent);text-decoration:none}
    footer{margin-top:16px;color:var(--muted);font-size:13px;text-align:right}
    @media (max-width:700px){.grid{grid-template-columns:1fr}.avatar{width:68px;height:68px}}
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <header>
        <div class="avatar">SS</div>
        <div>
          <h1>Data Scientist — Python · SQL · ML · DL</h1>
          <p class="lead">Building clean datasets, training efficient models, and shipping end-to-end ML apps with Streamlit.</p>
        </div>
      </header>

      <div class="grid">
        <section class="section">
          <h3>Tech Stack</h3>
          <div class="stack">
            <span class="chip">Python</span>
            <span class="chip">NumPy</span>
            <span class="chip">Pandas</span>
            <span class="chip">Scikit-learn</span>
            <span class="chip">TensorFlow / Keras</span>
            <span class="chip">SQL</span>
            <span class="chip">Power BI</span>
            <span class="chip">Tableau</span>
            <span class="chip">Streamlit</span>
            <span class="chip">Git</span>
          </div>
        </section>

        <section class="section">
          <h3>Current Focus</h3>
          <ul>
            <li>Model optimization and robust feature engineering</li>
            <li>Deep learning pipelines and GPU workflows</li>
            <li>Deploying ML apps (Streamlit) and reproducible code</li>
          </ul>
        </section>

        <section class="section">
          <h3>Projects</h3>
          <ul class="projects">
            <li><strong>Customer Churn Prediction</strong> — RandomForest + Streamlit; end-to-end pipeline and evaluation.</li>
            <li><strong>Spam Detection</strong> — NLP, vectorizers, and classifier deployment.</li>
            <li><strong>Car Price Prediction</strong> — Regression model with feature engineering and simple UI.</li>
          </ul>
        </section>

        <section class="section">
          <h3>Contact</h3>
          <div class="contact">
            <div>Email: <a href="mailto:your-email@example.com">your-email@example.com</a></div>
            <div>LinkedIn: <a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a></div>
            <div>Portfolio: <a href="#">your-portfolio-url</a></div>
          </div>
        </section>
      </div>

      <footer>Copy this HTML into any page or include as a profile section. Edit text and links to match your details.</footer>
    </div>
  </div>
</body>
</html>
