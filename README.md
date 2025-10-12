<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>README — Fairouz Omar</title>
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --accent:#7c3aed;
      --muted:#94a3b8;
      --text:#e6eef8;
      --glass: rgba(255,255,255,0.03);
    }
    html,body{height:100%;margin:0;font-family:"Segoe UI",Tahoma,Arial,sans-serif;background:linear-gradient(180deg,#071029 0%, #081222 100%);color:var(--text)}
    .container{max-width:900px;margin:36px auto;padding:28px;background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);border-radius:12px;box-shadow:0 10px 30px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.03)}
    header{display:flex;gap:18px;align-items:center}
    .avatar{width:96px;height:96px;border-radius:14px;background:linear-gradient(135deg,var(--accent),#0ea5a0);display:flex;align-items:center;justify-content:center;font-weight:700;font-size:28px;color:white;box-shadow:0 6px 20px rgba(124,58,237,0.18)}
    h1{margin:0;font-size:24px}
    p.lead{margin:6px 0 0;color:var(--muted)}
    .badges{margin-top:12px;display:flex;gap:8px;flex-wrap:wrap}
    .badge{background:var(--glass);padding:6px 10px;border-radius:999px;font-size:13px;color:var(--muted);border:1px solid rgba(255,255,255,0.02)}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:20px}
    .card{background:rgba(255,255,255,0.02);padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
    h2{margin:0 0 10px;font-size:18px;color:var(--text)}
    ul{margin:8px 0 0;padding-left:18px;color:var(--muted)}
    li{margin:6px 0}
    .tools{display:flex;flex-wrap:wrap;gap:8px}
    .tool{background:rgba(255,255,255,0.02);padding:8px 10px;border-radius:8px;font-size:13px;border:1px solid rgba(255,255,255,0.02);color:var(--muted)}
    .projects a{color:var(--accent);text-decoration:none}
    footer{margin-top:20px;color:var(--muted);font-size:13px;display:flex;justify-content:space-between;align-items:center;gap:10px;flex-wrap:wrap}
    .quote{font-style:italic;color:#cbd5e1}
    @media (max-width:880px){
      .grid{grid-template-columns:1fr;}
      .avatar{width:80px;height:80px;font-size:24px}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">FO</div>
      <div>
        <h1>Fairouz Omar — AI Student & Future Innovator</h1>
        <p class="lead">
          I’m an Artificial Intelligence student at Jordan University of Science and Technology 🎓 passionate about Machine Learning, Deep Learning, and Computer Vision.
          I enjoy building smart systems, solving real-world problems, and exploring the endless possibilities of technology.
        </p>
        <div class="badges">
          <span class="badge">🎓 AI Student</span>
          <span class="badge">💻 Python · C++ · HTML</span>
          <span class="badge">🤖 ML · DL · CV Enthusiast</span>
        </div>
      </div>
    </header>

    <div class="grid">
      <div>
        <div class="card">
          <h2>About Me</h2>
          <p style="color:var(--muted);margin:6px 0 0">
            I’m a passionate learner and problem-solver who loves combining creativity with technology. I believe in learning by doing and building projects that have real-world impact.
            My focus is on developing AI solutions that can make people’s lives better, smarter, and easier.
          </p>
        </div>

        <div class="card" style="margin-top:14px">
          <h2>Languages & Tools</h2>
          <div class="tools" style="margin-top:8px">
            <span class="tool">Python</span>
            <span class="tool">C++</span>
            <span class="tool">HTML</span>
          
            <span class="tool">CSS</span>
            <span class="tool">Jupyter Notebook</span>
            <span class="tool">Git</span>
            <span class="tool">NumPy · Pandas</span>
            <span class="tool">TensorFlow</span>
            <span class="tool">OpenCV</span>
            <span class="tool">VS Code</span>
          </div>
          <p style="color:var(--muted);margin-top:8px;font-size:14px">
            (You can tell me if you’d like to add or remove any tools — for example SQL, React, or PyTorch.)
          </p>
        </div>

        <div class="card projects" style="margin-top:14px">
          <h2>Projects & Work</h2>
          <ul>
            <li><strong>Logistic Regression (Mini-Batch GD)</strong> — Built from scratch for Breast Cancer Wisconsin Dataset with hyperparameter analysis.</li>
            <li><strong>AlexNet Implementation</strong> — Recreated the original architecture, studied code behavior, and wrote a detailed report with screenshots.</li>
            <li><strong>Multi-Label Text Classification</strong> — Compared Logistic Regression, CNN, and BERT models with accuracy tracking and loss visualization.</li>
            <li><em>Next Project?</em> — Plan to turn AI projects into interactive web applications using Flask or FastAPI.</li>
          </ul>
        </div>

        <div class="card" style="margin-top:14px">
          <h2>Current Goals</h2>
          <ul>
            <li>Deepen my understanding of Deep Learning and Computer Vision.</li>
            <li>Build deployable AI-powered web applications.</li>
            <li>Contribute to open-source ML projects.</li>
            <li>Learn about model serving and MLOps tools.</li>
          </ul>
        </div>
      </div>

      <aside>
        <div class="card">
          <h2>Contact Me</h2>
          <ul>
            <li>📧 Email: <strong>your_email_here@example.com</strong></li>
            <li>🐙 GitHub: <strong><a href="https://github.com/your-username" target="_blank" style="color:var(--accent);text-decoration:none">github.com/your-username</a></strong></li>
            <li>🏫 University: Jordan University of Science and Technology</li>
            <li>📚 Field: Artificial Intelligence, Machine Learning, Computer Vision</li>
          </ul>
        </div>

        <div class="card" style="margin-top:14px">
          <h2>Project Ideas</h2>
          <ul>
            <li>AI model performance dashboard (Flask / FastAPI + React)</li>
            <li>Simple OCR system using OpenCV and Tesseract</li>
            <li>Educational content recommender using ML clustering</li>
            <li>Interactive visualization of AlexNet layers and outputs</li>
          </ul>
        </div>

        <div class="card" style="margin-top:14px">
          <h2>Favorite Quote</h2>
          <p class="quote">"The best way to learn AI is to build it yourself." — Fairouz</p>
        </div>
      </aside>
    </div>

    <footer>
      <div>✨ Like my work? Show some love by starring my repositories ⭐</div>
      <div style="color:var(--muted)">Created with ❤️ by Fairouz Omar</div>
    </footer>
  </div>
</body>
</html>
