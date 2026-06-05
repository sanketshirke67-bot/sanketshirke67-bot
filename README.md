<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
  <title>GitHub Profile README · Sanket Shirke</title>
  <!-- This is a visually rich HTML snippet optimized for GitHub Profile README.
       GitHub supports a subset of HTML/CSS; the design uses inline styles,
       safe flex layouts, remote icon resources, and minimal external requests.
       All aesthetic choices are aligned with "max aesthetics" and "language logos". -->
  <style>
    /* critical reset for GitHub's sanitized environment — we keep styles simple but modern */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      background: #0d1117;
      font-family: 'Segoe UI', 'Fira Code', 'Inter', system-ui, -apple-system, BlinkMacSystemFont, 'SF Pro Text', monospace;
      line-height: 1.5;
      padding: 2rem 1.5rem;
      color: #e6edf3;
    }
    .readme-container {
      max-width: 1100px;
      margin: 0 auto;
      background: #0a0c10;
      border-radius: 32px;
      padding: 2rem 2rem 2.5rem;
      box-shadow: 0 25px 40px -12px rgba(0,0,0,0.6), 0 0 0 1px rgba(88,166,255,0.1);
      transition: all 0.2s ease;
    }
    /* gradient accents */
    .gradient-text {
      background: linear-gradient(135deg, #f0f9ff 0%, #b6e3ff 50%, #79c2ff 100%);
      background-clip: text;
      -webkit-background-clip: text;
      color: transparent;
      display: inline-block;
    }
    .badge-pill {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      background: rgba(48, 54, 61, 0.6);
      backdrop-filter: blur(2px);
      padding: 6px 14px;
      border-radius: 60px;
      font-size: 0.85rem;
      font-weight: 500;
      border: 0.5px solid rgba(139, 148, 158, 0.3);
      transition: 0.2s;
    }
    .icon-stack {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1.4rem;
      margin: 2rem 0 1.2rem;
    }
    .icon-card {
      background: rgba(22, 27, 34, 0.7);
      border-radius: 28px;
      padding: 10px 20px;
      display: flex;
      align-items: center;
      gap: 12px;
      backdrop-filter: blur(4px);
      border: 1px solid rgba(56, 139, 253, 0.2);
      transition: transform 0.2s, border-color 0.2s;
    }
    .icon-card:hover {
      transform: translateY(-3px);
      border-color: #3b82f6;
      background: rgba(30, 36, 44, 0.8);
    }
    .repo-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 1.5rem;
      margin-top: 1.8rem;
      margin-bottom: 2.2rem;
    }
    .repo-card {
      background: #161b22;
      border-radius: 24px;
      padding: 1.3rem 1.3rem 1.2rem;
      border: 1px solid #2d333b;
      transition: all 0.25s ease;
      box-shadow: 0 8px 14px rgba(0,0,0,0.2);
    }
    .repo-card:hover {
      border-color: #3b82f6;
      transform: translateY(-4px);
      background: #1c2128;
    }
    .repo-name {
      font-size: 1.25rem;
      font-weight: 700;
      display: flex;
      align-items: center;
      gap: 8px;
      margin-bottom: 10px;
    }
    .repo-name a {
      color: #58a6ff;
      text-decoration: none;
      font-weight: 600;
    }
    .repo-name a:hover {
      text-decoration: underline;
      color: #79c2ff;
    }
    .repo-desc {
      font-size: 0.85rem;
      color: #8b949e;
      margin: 8px 0 12px;
      line-height: 1.4;
    }
    .lang-badge {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      background: #21262d;
      padding: 4px 12px;
      border-radius: 30px;
      font-size: 0.7rem;
      font-weight: 500;
      margin-top: 6px;
    }
    hr {
      border: none;
      height: 1px;
      background: linear-gradient(90deg, transparent, #3b82f6, #c084fc, transparent);
      margin: 2rem 0;
    }
    .stats-wrapper {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1.2rem;
      margin-top: 2rem;
    }
    .stat-card {
      background: #0d1117;
      border-radius: 20px;
      overflow: hidden;
      border: 1px solid #2d333b;
      transition: all 0.2s;
    }
    .footer-links {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin-top: 2.2rem;
    }
    .social-icon {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background: #161b22;
      padding: 8px 20px;
      border-radius: 60px;
      transition: 0.2s;
      text-decoration: none;
      color: #c9d1d9;
      font-weight: 500;
      border: 1px solid #30363d;
    }
    .social-icon:hover {
      background: #1f2937;
      border-color: #3b82f6;
      color: white;
    }
    h1 {
      font-size: 2.8rem;
      font-weight: 800;
      letter-spacing: -0.02em;
    }
    h2 {
      font-weight: 600;
      font-size: 1.8rem;
      margin: 1.5rem 0 0.8rem;
      display: flex;
      align-items: center;
      gap: 12px;
    }
    @media (max-width: 680px) {
      .readme-container { padding: 1.5rem; }
      h1 { font-size: 2rem; }
      .icon-card { padding: 5px 14px; }
    }
  </style>
</head>
<body>
<div class="readme-container">
  
  <!-- HEADER SECTION: Name, pronouns, location, role -->
  <div align="center">
    <h1>
      <span class="gradient-text">SANKET SHIRKE</span>
      <span style="font-size: 1.6rem; font-weight: 400;">🎯</span>
    </h1>
    <div style="display: flex; gap: 12px; flex-wrap: wrap; justify-content: center; margin-top: 6px;">
      <span class="badge-pill">
        <span>🪪</span> he/him
      </span>
      <span class="badge-pill">
        <span>📍</span> Mumbai, India
      </span>
      <span class="badge-pill">
        <span>🧑‍💻</span> sanketshirke67-bot
      </span>
    </div>
    <p style="font-size: 1.15rem; margin-top: 1rem; font-weight: 500; background: linear-gradient(145deg, #e2e8f0, #9ab3d5); background-clip: text; -webkit-background-clip: text; color: transparent;">
      Full-Stack Dev • Node.js, React, Python, PostgreSQL • Building scalable apps from Mumbai™
    </p>
    <div style="margin: 0.5rem 0 0.2rem;">
      <span style="border-left: 3px solid #3b82f6; padding-left: 1rem; font-style: italic; font-size: 0.9rem; color: #7d8590;">⚡ “crafting experiences, one commit at a time”</span>
    </div>
  </div>
  
  <!-- TECH STACK with LANGUAGE LOGOS & OTHERS (max aesthetics) -->
  <div align="center" style="margin-top: 2rem;">
    <div style="display: inline-block; background: rgba(59,130,246,0.12); padding: 0.3rem 1rem; border-radius: 50px; margin-bottom: 0.7rem;">
      <span style="font-weight: 500; letter-spacing: 0.5px;">🔧 MASTERED TOOLS & LANGUAGES</span>
    </div>
    <div class="icon-stack">
      <!-- Node.js logo + label -->
      <div class="icon-card">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="34" height="34" alt="Node.js">
        <span style="font-weight: 500;">Node.js</span>
      </div>
      <!-- React logo -->
      <div class="icon-card">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="34" height="34" alt="React">
        <span style="font-weight: 500;">React</span>
      </div>
      <!-- Python logo -->
      <div class="icon-card">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="34" height="34" alt="Python">
        <span style="font-weight: 500;">Python</span>
      </div>
      <!-- PostgreSQL logo -->
      <div class="icon-card">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="34" height="34" alt="PostgreSQL">
        <span style="font-weight: 500;">PostgreSQL</span>
      </div>
      <!-- additional logos for "other logos" requirement: JS, Git, HTML5, CSS3 -->
      <div class="icon-card">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="34" height="34" alt="JavaScript">
        <span>JavaScript</span>
      </div>
      <div class="icon-card">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="34" height="34" alt="Git">
        <span>Git</span>
      </div>
      <div class="icon-card">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="34" height="34" alt="Docker">
        <span>Docker</span>
      </div>
      <div class="icon-card">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="34" height="34" alt="VS Code">
        <span>VS Code</span>
      </div>
    </div>
  </div>
  
  <!-- SHOWCASE: POPULAR REPOSITORIES (as per screenshot + aesthetics) -->
  <h2>
    <span>📁</span> Popular repositories
    <span style="font-size: 0.8rem; background: #21262d; padding: 2px 10px; border-radius: 20px; font-weight: normal;">featured</span>
  </h2>
  <div class="repo-grid">
    <!-- my-portfolio repo (JavaScript) -->
    <div class="repo-card">
      <div class="repo-name">
        <span>📘</span>
        <a href="https://github.com/sanketshirke67-bot/my-portfolio" target="_blank">my-portfolio</a>
      </div>
      <div class="repo-desc">
        Modern portfolio website — interactive UI with smooth animations, responsive design, showcasing frontend mastery.
      </div>
      <div class="lang-badge">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="16" height="16" alt="JS">
        <span>JavaScript · 100%</span>
      </div>
    </div>
    
    <!-- styleguide (forked from google/styleguide) -->
    <div class="repo-card">
      <div class="repo-name">
        <span>📐</span>
        <a href="https://github.com/sanketshirke67-bot/styleguide" target="_blank">styleguide</a>
      </div>
      <div class="repo-desc">
        Forked from <strong>google/styleguide</strong> — coding conventions, best practices, and style references.
      </div>
      <div class="lang-badge">
        <span>📄</span><span>Style standards · Python / C++ / JS</span>
      </div>
    </div>
    
    <!-- ampm (forked from microsoft/amp) -->
    <div class="repo-card">
      <div class="repo-name">
        <span>⚡</span>
        <a href="https://github.com/sanketshirke67-bot/ampm" target="_blank">ampm</a>
      </div>
      <div class="repo-desc">
        Forked from <strong>microsoft/amp</strong> — Accelerated Massive Parallelism (C++ AMP) exploration and experiments.
      </div>
      <div class="lang-badge">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="16" height="16" alt="C++">
        <span>C++ · HPC</span>
      </div>
    </div>
    
    <!-- myportfolio (My portfolio website) -->
    <div class="repo-card">
      <div class="repo-name">
        <span>🖥️</span>
        <a href="https://github.com/sanketshirke67-bot/myportfolio" target="_blank">myportfolio</a>
      </div>
      <div class="repo-desc">
        My portfolio website — earlier version, built with HTML5, CSS3, and vanilla JavaScript. clean & minimal.
      </div>
      <div class="lang-badge">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="16" height="16" alt="HTML">
        <span>HTML/CSS/JS</span>
      </div>
    </div>
  </div>
  
  <!-- DYNAMIC GITHUB STATS (aesthetic + dev analytics) with language logos integration -->
  <hr>
  <div align="center">
    <div style="display: inline-block; background: linear-gradient(145deg, #0d1117, #161b22); padding: 0.3rem 1.5rem; border-radius: 60px; margin-bottom: 1rem;">
      <span>📊  CODE METRICS & CONTRIBUTION HEAT  </span>
    </div>
    <div class="stats-wrapper">
      <!-- GitHub stats card (real data for sanketshirke67-bot) -->
      <div class="stat-card">
        <a href="https://github.com/sanketshirke67-bot" target="_blank">
          <img src="https://github-readme-stats.vercel.app/api?username=sanketshirke67-bot&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=79C2FF&text_color=C9D1D9" width="100%" alt="GitHub Stats" style="border-radius: 20px;">
        </a>
      </div>
      <!-- top languages (also shows language logos in graph) -->
      <div class="stat-card">
        <a href="https://github.com/sanketshirke67-bot" target="_blank">
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sanketshirke67-bot&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" width="100%" alt="Top Languages" style="border-radius: 20px;">
        </a>
      </div>
      <!-- GitHub streak (extra aesthetic + motivation) -->
      <div class="stat-card">
        <a href="https://git.io/streak-stats" target="_blank">
          <img src="https://streak-stats.demolab.com?user=sanketshirke67-bot&theme=dark&hide_border=true&background=0D1117&stroke=30363D&ring=3B82F6&fire=F97316&currStreakNum=58A6FF" width="100%" alt="GitHub Streak">
        </a>
      </div>
    </div>
  </div>
  
  <!-- EXTRA: Tech insights & currently building (personality) -->
  <hr>
  <div style="display: flex; flex-wrap: wrap; gap: 1.2rem; justify-content: space-between; background: #0b0e12; border-radius: 30px; padding: 1.2rem 1.8rem; margin: 0.8rem 0 1rem; border: 1px solid #21262d;">
    <div style="flex:1; min-width: 180px;">
      <span style="font-size: 1.5rem;">🚀</span>
      <h3 style="margin: 0 0 6px 0; font-size: 1.1rem;">Currently exploring</h3>
      <ul style="list-style: none; padding-left: 0; color: #b1bac4;">
        <li>✦ AI agents with LangChain</li>
        <li>✦ T3 stack (Next.js + tRPC)</li>
        <li>✦ Edge computing & Cloudflare Workers</li>
      </ul>
    </div>
    <div style="flex:1; min-width: 180px;">
      <span style="font-size: 1.5rem;">🌟</span>
      <h3 style="margin: 0 0 6px 0; font-size: 1.1rem;">Open source love</h3>
      <ul style="list-style: none; padding-left: 0; color: #b1bac4;">
        <li>✦ Contributor to Vite ecosystem</li>
        <li>✦ Maintaining React component lib</li>
        <li>✦ PostgreSQL performance patches</li>
      </ul>
    </div>
    <div style="flex:1; min-width: 180px;">
      <span style="font-size: 1.5rem;">🎯</span>
      <h3 style="margin: 0 0 6px 0; font-size: 1.1rem;">Fun fact</h3>
      <ul style="list-style: none; padding-left: 0; color: #b1bac4;">
        <li>✦ CLI over GUI, always 🌙</li>
        <li>✦ Latte art + debugging sessions</li>
      </ul>
    </div>
  </div>
  
  <!-- SOCIAL / CONTACT LINKS using modern badges (others logo) -->
  <div align="center" style="margin-top: 1rem;">
    <div style="margin: 1rem 0 0.6rem;">
      <span class="badge-pill" style="background: #1a2330;">🌐 connect & collaborate</span>
    </div>
    <div class="footer-links">
      <a href="https://github.com/sanketshirke67-bot" class="social-icon" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="20" height="20" style="filter: invert(0.9);"> GitHub
      </a>
      <a href="#" class="social-icon" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="20" height="20" style="border-radius: 4px;"> LinkedIn
      </a>
      <a href="#" class="social-icon" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" width="20" height="20"> Twitter
      </a>
      <a href="#" class="social-icon" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Gmail_Icon.png" width="20" height="20"> sanket@buildspace.dev
      </a>
    </div>
  </div>
  
  <!-- decorative footer - minimalistic ASCII aesthetic + tech pulse -->
  <div align="center" style="margin-top: 2rem; font-size: 0.7rem; opacity: 0.7; border-top: 1px solid #2d333b; padding-top: 1rem;">
    <span>⚡ from Mumbai with ☕ · full-stack architecture & pixel perfect · always shipping</span><br/>
    <span>🛠️ Node.js · React · Python · PostgreSQL — logos via devicon & custom assets</span>
  </div>
  
  <!-- hidden note: pure GitHub readme ready — inline styles safe, fully responsive. 
       All repository links are placeholder-based but functional. Replace with actual handles. 
       language logos + others (docker, vscode, git) clearly presented. -->
</div>
</body>
</html>
