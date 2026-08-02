<div align="center">

<!-- 3D AI Neural Network Banner Header -->
<a href="https://portfolio-website-psi-orpin-23.vercel.app" target="_blank">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 380" width="100%" height="100%">
  <defs>
    <!-- Background Gradient -->
    <linearGradient id="bg-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#080B10"/>
      <stop offset="50%" stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#121822"/>
    </linearGradient>

    <!-- Crimson Glow Gradient -->
    <radialGradient id="red-glow" cx="80%" cy="30%" r="60%">
      <stop offset="0%" stop-color="#FF1F3D" stop-opacity="0.35"/>
      <stop offset="50%" stop-color="#FF1F3D" stop-opacity="0.1"/>
      <stop offset="100%" stop-color="#000000" stop-opacity="0"/>
    </radialGradient>

    <!-- Blue Ambient Glow -->
    <radialGradient id="blue-glow" cx="15%" cy="80%" r="50%">
      <stop offset="0%" stop-color="#58A6FF" stop-opacity="0.15"/>
      <stop offset="100%" stop-color="#000000" stop-opacity="0"/>
    </radialGradient>

    <!-- Node Glow Filter -->
    <filter id="glow-red" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>

    <filter id="glow-bright" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="12" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
  </defs>

  <!-- Background Canvas -->
  <rect width="1200" height="380" rx="16" fill="url(#bg-grad)"/>
  <rect width="1200" height="380" rx="16" fill="url(#red-glow)"/>
  <rect width="1200" height="380" rx="16" fill="url(#blue-glow)"/>

  <!-- Border Frame -->
  <rect x="1" y="1" width="1198" height="378" rx="15" fill="none" stroke="#30363D" stroke-width="1.5"/>
  <rect x="1" y="1" width="1198" height="378" rx="15" fill="none" stroke="#FF1F3D" stroke-width="1" stroke-opacity="0.3"/>

  <!-- Cybernetic Grid Pattern Overlay -->
  <g opacity="0.06" stroke="#FFFFFF" stroke-width="1">
    <line x1="0" y1="60" x2="1200" y2="60"/>
    <line x1="0" y1="120" x2="1200" y2="120"/>
    <line x1="0" y1="180" x2="1200" y2="180"/>
    <line x1="0" y1="240" x2="1200" y2="240"/>
    <line x1="0" y1="300" x2="1200" y2="300"/>
    <line x1="200" y1="0" x2="200" y2="380"/>
    <line x1="400" y1="0" x2="400" y2="380"/>
    <line x1="600" y1="0" x2="600" y2="380"/>
    <line x1="800" y1="0" x2="800" y2="380"/>
    <line x1="1000" y1="0" x2="1000" y2="380"/>
  </g>

  <!-- 3D NEURAL NETWORK GRAPHIC (RIGHT SIDE) -->
  <g id="neural-net" transform="translate(150, 0)">
    <!-- Neural Synapse Connections (Lines) -->
    <g stroke="#30363D" stroke-width="1.5" opacity="0.8">
      <line x1="750" y1="100" x2="860" y2="150" />
      <line x1="750" y1="100" x2="820" y2="240" />
      <line x1="860" y1="150" x2="940" y2="110" />
      <line x1="860" y1="150" x2="920" y2="220" />
      <line x1="820" y1="240" x2="920" y2="220" />
      <line x1="820" y1="240" x2="880" y2="310" />
      <line x1="940" y1="110" x2="1010" y2="180" />
      <line x1="920" y1="220" x2="1010" y2="180" />
      <line x1="920" y1="220" x2="990" y2="280" />
      <line x1="880" y1="310" x2="990" y2="280" />
    </g>

    <!-- Active High-Energy Synaptic Lines (Crimson Glow) -->
    <g stroke="#FF1F3D" stroke-width="2" opacity="0.85" filter="url(#glow-red)">
      <line x1="750" y1="100" x2="860" y2="150" />
      <line x1="860" y1="150" x2="920" y2="220" />
      <line x1="920" y1="220" x2="1010" y2="180" />
      <line x1="820" y1="240" x2="920" y2="220" stroke-dasharray="6,4" />
    </g>

    <!-- Neural Nodes (Circles) -->
    <circle cx="750" cy="100" r="6" fill="#FFFFFF" opacity="0.9"/>
    <circle cx="860" cy="150" r="9" fill="#FF1F3D" filter="url(#glow-red)"/>
    <circle cx="860" cy="150" r="4" fill="#FFFFFF"/>

    <circle cx="820" cy="240" r="7" fill="#58A6FF" filter="url(#glow-red)"/>
    <circle cx="940" cy="110" r="6" fill="#FFFFFF" opacity="0.8"/>
    
    <circle cx="920" cy="220" r="11" fill="#FF1F3D" filter="url(#glow-bright)"/>
    <circle cx="920" cy="220" r="5" fill="#FFFFFF"/>

    <circle cx="880" cy="310" r="6" fill="#58A6FF" opacity="0.8"/>
    <circle cx="1010" cy="180" r="8" fill="#FF1F3D" filter="url(#glow-red)"/>
    <circle cx="1010" cy="180" r="3.5" fill="#FFFFFF"/>
    <circle cx="990" cy="280" r="5" fill="#FFFFFF" opacity="0.9"/>

    <!-- Data Signals floating on nodes -->
    <text x="935" y="215" fill="#FFFFFF" font-family="monospace" font-size="9" font-weight="bold">w_i: 0.984</text>
    <text x="872" y="145" fill="#FF1F3D" font-family="monospace" font-size="8" font-weight="bold">AI_NET</text>
  </g>

  <!-- LEFT TEXT & HEADER CONTENT -->
  <g transform="translate(60, 0)">
    
    <!-- Top Badge -->
    <g transform="translate(0, 50)">
      <rect x="0" y="0" width="220" height="28" rx="14" fill="#161B22" stroke="#30363D" stroke-width="1"/>
      <circle cx="14" cy="14" r="4" fill="#FF1F3D"/>
      <text x="28" y="18" fill="#C9D1D9" font-family="monospace" font-size="11" font-weight="600">3D AI NEURAL ENGINE // WEBGL</text>
    </g>

    <!-- Main Title -->
    <text x="0" y="130" fill="#FFFFFF" font-family="system-ui, -apple-system, sans-serif" font-size="44" font-weight="900" letter-spacing="-1">
      SANYA <tspan fill="#FF1F3D">JAISWAL</tspan>
    </text>

    <!-- Subtitle / Roles -->
    <text x="0" y="165" fill="#8B949E" font-family="monospace" font-size="14" font-weight="600" letter-spacing="0.5">
      DATA SCIENCE UNDERGRADUATE • AI &amp; ML ENGINEER
    </text>

    <!-- Description quote -->
    <text x="0" y="202" fill="#C9D1D9" font-family="system-ui, -apple-system, sans-serif" font-size="13" font-weight="400" opacity="0.9">
      Building intelligent AI models, predictive analytics frameworks, and interactive WebGL experiences.
    </text>

    <!-- Tech Badges -->
    <g transform="translate(0, 235)">
      <!-- Python Badge -->
      <g transform="translate(0, 0)">
        <rect x="0" y="0" width="85" height="28" rx="6" fill="#161B22" stroke="#30363D" stroke-width="1"/>
        <text x="42.5" y="18" fill="#58A6FF" font-family="monospace" font-size="11" font-weight="bold" text-anchor="middle">Python</text>
      </g>

      <!-- PyTorch Badge -->
      <g transform="translate(95, 0)">
        <rect x="0" y="0" width="90" height="28" rx="6" fill="#161B22" stroke="#30363D" stroke-width="1"/>
        <text x="45" y="18" fill="#FF1F3D" font-family="monospace" font-size="11" font-weight="bold" text-anchor="middle">PyTorch</text>
      </g>

      <!-- Scikit-learn Badge -->
      <g transform="translate(195, 0)">
        <rect x="0" y="0" width="115" height="28" rx="6" fill="#161B22" stroke="#30363D" stroke-width="1"/>
        <text x="57.5" y="18" fill="#F7931E" font-family="monospace" font-size="11" font-weight="bold" text-anchor="middle">Scikit-Learn</text>
      </g>

      <!-- React Badge -->
      <g transform="translate(320, 0)">
        <rect x="0" y="0" width="80" height="28" rx="6" fill="#161B22" stroke="#30363D" stroke-width="1"/>
        <text x="40" y="18" fill="#61DAFB" font-family="monospace" font-size="11" font-weight="bold" text-anchor="middle">React</text>
      </g>

      <!-- Three.js Badge -->
      <g transform="translate(410, 0)">
        <rect x="0" y="0" width="90" height="28" rx="6" fill="#161B22" stroke="#30363D" stroke-width="1"/>
        <text x="45" y="18" fill="#FFFFFF" font-family="monospace" font-size="11" font-weight="bold" text-anchor="middle">Three.js</text>
      </g>

      <!-- SQL Badge -->
      <g transform="translate(510, 0)">
        <rect x="0" y="0" width="65" height="28" rx="6" fill="#161B22" stroke="#30363D" stroke-width="1"/>
        <text x="32.5" y="18" fill="#E38C00" font-family="monospace" font-size="11" font-weight="bold" text-anchor="middle">SQL</text>
      </g>
    </g>

    <!-- Bottom Action Status Bar -->
    <g transform="translate(0, 300)">
      <rect x="0" y="0" width="575" height="32" rx="8" fill="#161B22" opacity="0.9" stroke="#30363D" stroke-width="1"/>
      <circle cx="16" cy="16" r="4" fill="#39D353"/>
      <text x="30" y="20" fill="#C9D1D9" font-family="monospace" font-size="11" font-weight="500">
        Live Portfolio: <tspan fill="#58A6FF">portfolio-website-psi-orpin-23.vercel.app</tspan>
      </text>
    </g>

  </g>

</svg>

</a>

<br /><br />

# 👋 Hi there, I'm **Sanya Jaiswal** 

### 🚀 Data Science Undergraduate | AI & Machine Learning Engineer | Full Stack Developer

[![Portfolio Website](https://img.shields.io/badge/🌐_Live_Portfolio-3D_AI_Neural_Engine-FF1F3D?style=for-the-badge&logo=react&logoColor=white)](https://portfolio-website-psi-orpin-23.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanya-jaiswal-ba1a55354)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sanya-6976)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sanyakumarjaiswal@gmail.com)

</div>

---

### 💫 About Me

I'm a **B.Tech Data Science student** passionate about building **AI-powered applications**, **intelligent analytics platforms**, and **scalable full-stack systems**. I bridge the gap between machine learning research, software engineering, and interactive web visualization to solve complex real-world problems.

- 🔭 **Currently Building**: Advanced AI agents, predictive customer lifetime value engines, and 3D WebGL neural simulation tools.
- 🎓 **Education**: B.Tech in Data Science & Artificial Intelligence.
- 💡 **Core Interests**: Deep Learning, Computer Vision, Predictive Analytics, NLP, MLOps & High-Performance Web Apps.
- 💬 **Ask me about**: Python, Scikit-learn, React, TypeScript, Three.js, FastAPI, & SQL.
- ⚡ **Fun Fact**: I designed an interactive 3D WebGL Neural Synaptic Engine in my live portfolio!

---

### 🛠️ Tech Stack & Tools

<div align="center">

#### **Languages & Data Science**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

#### **AI, ML & Data Analytics**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

#### **Web Development & Visualization**
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

</div>

---

### 🚀 Flagship Featured Projects

| Project | Description | Tech Stack | Links |
| :--- | :--- | :--- | :--- |
| **📊 Customer Lifetime Value** | Predictive ML framework for CLV modeling, churn probability estimation & RFM customer segmentation. | `Python` `Scikit-Learn` `Pandas` `RFM` | [Code](https://github.com/sanya-6976/CUSTOMER-LIFETIME-VALUE) • [Demo](https://portfolio-website-psi-orpin-23.vercel.app) |
| **📚 Notion AI Study Planner** | Intelligent study planner featuring Notion API integration, adaptive goal tracking & focus analytics. | `React` `Node.js` `Notion API` `Express` | [Code](https://github.com/sanya-6976/notion-ai-study-planner) • [Demo](https://portfolio-website-psi-orpin-23.vercel.app) |
| **🎭 SentAnal AI** | Real-time sentiment & emotion intelligence engine with aspect-based scoring & NLP telemetry. | `Python` `Transformers` `FastAPI` `React` | [Code](https://github.com/sanya-6976/SENTANAL-AI) • [Demo](https://portfolio-website-psi-orpin-23.vercel.app) |
| **🧠 Neuro Nexus** | Interactive WebGL 3D neural network visualizer & AI cognitive simulation mapping synaptic activations. | `Three.js` `React` `TypeScript` `WebGL` | [Code](https://github.com/sanya-6976/NEURO-NEXUS) • [Demo](https://portfolio-website-psi-orpin-23.vercel.app) |
| **🔐 Cipher Cloud** | Multi-layer cryptography desktop app with SHA-256 hashing, QR encryption & secure file pipelines. | `Python` `Tkinter` `OpenCV` `Cryptography` | [Code](https://github.com/sanya-6976/CIPHER-CLOUD) • [Demo](https://portfolio-website-psi-orpin-23.vercel.app) |
| **🤖 AI GitHub Code Reviewer** | Automated AI pull request code reviewer evaluating bugs, security risks & optimization feedback. | `Python` `OpenAI API` `GitHub Actions` | [Code](https://github.com/sanya-6976/AI-GITHUB-CODE-REVIEWER) • [Demo](https://portfolio-website-psi-orpin-23.vercel.app) |

---

### 📈 GitHub Analytics & Stats

<div align="center">

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sanya-6976&show_icons=true&theme=dark&hide_border=true&title_color=FF1F3D&text_color=C9D1D9&icon_color=FF1F3D&bg_color=0D1117" alt="Sanya's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sanya-6976&layout=compact&theme=dark&hide_border=true&title_color=FF1F3D&text_color=C9D1D9&bg_color=0D1117" alt="Top Languages" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sanya-6976&theme=dark&hide_border=true&background=0D1117&ring=FF1F3D&fire=FF1F3D&currStreakLabel=FF1F3D" alt="GitHub Streak" width="97%" />
</p>

</div>

---

### 📜 Certifications & Achievements

- 🏅 **Supervised Machine Learning: Regression and Classification** — *DeepLearning.AI & Stanford Online*
- 🏅 **Data Analysis with Python** — *IBM / Coursera*
- 🏅 **SQL for Data Science** — *UC Davis / Coursera*
- 🏅 **Google Data Analytics Professional Certificate** — *Google*
- 🏆 **Hackathon Finalist** — *5+ National Level AI & Data Science Hackathons*

---

### 📬 Connect With Me

<div align="center">

[![Portfolio](https://img.shields.io/badge/Website-Portfolio-FF1F3D?style=for-the-badge&logo=firefox&logoColor=white)](https://portfolio-website-psi-orpin-23.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sanya_Jaiswal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanya-jaiswal-ba1a55354)
[![Twitter](https://img.shields.io/badge/X-@sanyajaiswal-1DA1F2?style=for-the-badge&logo=x&logoColor=white)](https://x.com/sanyajaiswal)
[![Email](https://img.shields.io/badge/Email-sanyakumarjaiswal@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sanyakumarjaiswal@gmail.com)

</div>

<br />

<div align="center">
  <sub>Designed with ❤️ & AI by <b>Sanya Jaiswal</b></sub>
</div>
