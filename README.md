<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Kshetrapal Singh — Portfolio Header</title>
  <style>
    :root{
      --bg:#0b1220; /* deep navy */
      --card:#0f1724; /* slightly lighter */
      --muted:#9aa4b2;
      --accent-1:#00c2a8; /* teal */
      --accent-2:#ff6b6b; /* coral */
      --glass: rgba(255,255,255,0.04);
      --radius:16px;
      --maxw:900px;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }

    *{box-sizing:border-box}
    body{margin:0;min-height:100vh;display:flex;align-items:center;justify-content:center;background:linear-gradient(180deg,var(--bg),#08101a);color:#e6eef6}

    .card{
      width:calc(100% - 40px);
      max-width:var(--maxw);
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:var(--radius);
      padding:28px;
      display:flex;gap:22px;align-items:center;box-shadow: 0 8px 30px rgba(2,6,23,0.7);
      border:1px solid rgba(255,255,255,0.03);
    }

    .avatar{
      width:140px;height:140px;border-radius:20px;flex:0 0 140px;overflow:hidden;border:1px solid rgba(255,255,255,0.04);background:linear-gradient(135deg,var(--accent-1),var(--accent-2));display:flex;align-items:center;justify-content:center;font-weight:700;font-size:32px;color:#021018
    }

    .content{flex:1}
    h1{margin:0;font-size:28px;letter-spacing:-0.4px}
    h2{margin:6px 0 12px 0;font-size:15px;color:var(--muted);font-weight:600}

    p.lead{margin:0 0 14px 0;color:#d8e6f7;max-width:72%}

    .chips{display:flex;gap:10px;flex-wrap:wrap;margin-top:10px}
    .chip{background:var(--glass);padding:8px 12px;border-radius:999px;font-size:13px;color:var(--muted);border:1px solid rgba(255,255,255,0.02)}

    .actions{display:flex;gap:12px;margin-top:18px}
    .btn{display:inline-flex;align-items:center;gap:8px;padding:10px 14px;border-radius:12px;font-weight:600;text-decoration:none;border:none;cursor:pointer}
    .btn-primary{background:linear-gradient(90deg,var(--accent-1),#3be6d0);color:#021018}
    .btn-outline{background:transparent;border:1px solid rgba(255,255,255,0.06);color:#dbe9f3}

    .socials{margin-left:auto;display:flex;gap:8px}
    .socials a{display:inline-flex;align-items:center;justify-content:center;width:42px;height:42px;border-radius:10px;background:rgba(255,255,255,0.02);text-decoration:none;color:#e8f5fb;border:1px solid rgba(255,255,255,0.02)}

    /* small screens */
    @media (max-width:640px){
      .card{flex-direction:column;align-items:flex-start}
      .avatar{width:110px;height:110px;border-radius:14px}
      p.lead{max-width:100%}
      .socials{margin-left:0}
    }

    /* little flourish */
    .accent-line{height:6px;border-radius:999px;margin-top:14px;background:linear-gradient(90deg,var(--accent-1),var(--accent-2))}
  </style>
</head>
<body>
  <main class="card" role="banner">
    <div class="avatar" aria-hidden="true">KS</div>

    <div class="content">
      <h1>?? Hi, I'm <strong>Kshetrapal Singh</strong></h1>
      <h2>Software Developer • Tech Educator • Passionate Coder</h2>

      <p class="lead">I build clean, efficient, and scalable applications — currently exploring <strong>AI & Deep Learning</strong>, full-stack engineering, and open-source contributions. I enjoy turning complex problems into elegant solutions.</p>

      <div class="chips" aria-hidden="true">
        <div class="chip">Python</div>
        <div class="chip">Deep Learning</div>
        <div class="chip">Full-Stack</div>
        <div class="chip">Open Source</div>
        <div class="chip">System Design</div>
      </div>

      <div class="actions">
        <a class="btn btn-primary" href="https://github.com/your-github-url" target="_blank" rel="noopener">? Star / Follow</a>
        <a class="btn btn-outline" href="mailto:your-email@example.com">?? Email Me</a>

        <div class="socials" aria-hidden="true">
          <a href="https://linkedin.com/in/your-linkedin-url" target="_blank">in</a>
          <a href="https://twitter.com/your-twitter" target="_blank">t</a>
          <a href="https://github.com/your-github-url" target="_blank">gh</a>
        </div>
      </div>

      <div class="accent-line" aria-hidden="true"></div>
    </div>

---

### 🚀 About Me  
- 🎓 Passionate about coding and problem-solving Data Structures and Algorithms, C/C++, Competitive Programming
HTML
Database Management System
C# for Programming  
- 💻 I love working with **Python, C, Web Development**  
- 🌱 Currently Working on **IOT, AIML, Healthcare Projects**  
- ✨ Interested in building real-world projects  

---

### 🛠️ Skills  
<p align="center">
  <img src="https://img.shields.io/badge/Python-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C-orange?logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-red?logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-blue?logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-yellow?logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/GitHub-black?logo=github" />
</p>

---

### 📂 Projects  
- 🌤️ [Weather App](https://github.com/username/weather-app) – Python + Flask  
- 📝 [Student Portfolio Website](https://github.com/username/portfolio) – HTML, CSS, JS  
- 🤖 [AI Chatbot](https://github.com/username/chatbot) – Python + NLP  

---

### 📊 GitHub Stats  
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=tokyonight" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=tokyonight" />
</p>

---

### 🌐 Connect With Me  
<p align="center">
  <a href="https://linkedin.com/in/yourprofile"><img src="https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&logoColor=white" /></a>
  <a href="mailto:your@email.com"><img src="https://img.shields.io/badge/Email-red?logo=gmail&logoColor=white" /></a>
</p>
 </main>
</body>
</html>
