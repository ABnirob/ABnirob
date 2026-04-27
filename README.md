<!-- ╔══════════════════════════════════════════════════════╗ -->
<!--       SELF-CONTAINED SVG LIQUID WAVE HEADER            -->
<!-- ╚══════════════════════════════════════════════════════╝ -->
<p align="center">
<svg viewBox="0 0 900 220" xmlns="http://www.w3.org/2000/svg" width="100%">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#0d1117"/>
      <stop offset="50%"  stop-color="#0a2a4a"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <linearGradient id="wave1g" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00D4FF" stop-opacity="0.7"/>
      <stop offset="50%"  stop-color="#0080FF" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#00D4FF" stop-opacity="0.7"/>
    </linearGradient>
    <linearGradient id="wave2g" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00FFCC" stop-opacity="0.4"/>
      <stop offset="50%"  stop-color="#0040FF" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#00FFCC" stop-opacity="0.4"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="900" height="220" fill="url(#bg)" rx="0"/>

  <!-- Decorative floating dots -->
  <circle cx="60"  cy="40"  r="2" fill="#00D4FF" opacity="0.5"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="3s" repeatCount="indefinite"/></circle>
  <circle cx="840" cy="55"  r="2" fill="#00FFCC" opacity="0.5"><animate attributeName="opacity" values="0.5;0.1;0.5" dur="2.5s" repeatCount="indefinite"/></circle>
  <circle cx="150" cy="20"  r="1.5" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0.1;0.6;0.1" dur="4s" repeatCount="indefinite"/></circle>
  <circle cx="750" cy="30"  r="1.5" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0.4;0.1;0.4" dur="3.5s" repeatCount="indefinite"/></circle>
  <circle cx="450" cy="18"  r="1"   fill="#00D4FF" opacity="0.4"><animate attributeName="opacity" values="0.2;0.7;0.2" dur="2s" repeatCount="indefinite"/></circle>

  <!-- Wave layer 1 — slow deep wave -->
  <path fill="url(#wave1g)" opacity="0.6">
    <animate attributeName="d" dur="8s" repeatCount="indefinite"
      values="
        M0,160 C150,130 300,185 450,155 C600,125 750,175 900,150 L900,220 L0,220 Z;
        M0,150 C150,175 300,125 450,160 C600,195 750,135 900,160 L900,220 L0,220 Z;
        M0,160 C150,130 300,185 450,155 C600,125 750,175 900,150 L900,220 L0,220 Z
      "/>
  </path>

  <!-- Wave layer 2 — faster ripple -->
  <path fill="url(#wave2g)" opacity="0.5">
    <animate attributeName="d" dur="5s" repeatCount="indefinite"
      values="
        M0,175 C120,155 250,195 400,170 C550,145 700,185 900,165 L900,220 L0,220 Z;
        M0,165 C120,185 250,150 400,180 C550,210 700,160 900,175 L900,220 L0,220 Z;
        M0,175 C120,155 250,195 400,170 C550,145 700,185 900,165 L900,220 L0,220 Z
      "/>
  </path>

  <!-- Wave layer 3 — thin shimmer top -->
  <path fill="#00D4FF" opacity="0.15">
    <animate attributeName="d" dur="6s" repeatCount="indefinite"
      values="
        M0,185 C200,168 400,200 600,178 C750,162 850,188 900,180 L900,220 L0,220 Z;
        M0,178 C200,195 400,165 600,190 C750,205 850,172 900,185 L900,220 L0,220 Z;
        M0,185 C200,168 400,200 600,178 C750,162 850,188 900,180 L900,220 L0,220 Z
      "/>
  </path>

  <!-- Glowing horizontal line -->
  <line x1="60" y1="125" x2="840" y2="125" stroke="#00D4FF" stroke-width="0.5" opacity="0.3"/>

  <!-- Main Name Text -->
  <text x="450" y="72" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif"
        font-size="36" font-weight="700" fill="#ffffff" filter="url(#glow)">
    Md. Abul Bashar Nirob
    <animate attributeName="opacity" values="0;1" dur="1.5s" fill="freeze"/>
  </text>

  <!-- Subtitle -->
  <text x="450" y="105" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif"
        font-size="14" font-weight="400" fill="#00D4FF" letter-spacing="1">
    Data &amp; Business Analyst · Future Data Engineer · AI Enthusiast
    <animate attributeName="opacity" values="0;1" dur="2s" begin="0.5s" fill="freeze"/>
  </text>
</svg>
</p>

<!-- Animated Typing Tagline -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=00D4FF&center=true&vCenter=true&width=860&lines=Turning+raw+data+into+strategic+decisions+%F0%9F%9A%80;Building+pipelines+that+power+the+future+%F0%9F%94%A7;From+Analyst+%E2%86%92+Engineer+%E2%86%92+Data+Scientist+%F0%9F%A7%A0;TrillionData+%7C+North+South+University+%7C+Dhaka%2C+Bangladesh+%F0%9F%87%A7%F0%9F%87%A9" alt="Typing SVG" />
</p>

<!-- Social Badges -->
<p align="center">
  <a href="https://www.linkedin.com/in/md-abul-bashar-nirob/">
    <img src="https://img.shields.io/badge/LinkedIn-Md.%20Abul%20Bashar%20Nirob-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>&nbsp;
  <a href="https://github.com/ABnirob">
    <img src="https://img.shields.io/badge/GitHub-ABnirob-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>&nbsp;
  <a href="mailto:ab.nirob.7@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>&nbsp;
  <img src="https://komarev.com/ghpvc/?username=ABnirob&style=for-the-badge&color=00D4FF&label=PROFILE+VIEWS"/>
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## `$ whoami`

```python
nirob = {
    "name"       : "Md. Abul Bashar Nirob",
    "role"       : "Data & Business Analyst → Data Engineer → (Future) Data Scientist",
    "location"   : "Dhaka, Bangladesh 🇧🇩",
    "education"  : "BSc in CSE — North South University",
    "company"    : "TrillionData",
    "focus"      : ["Data Pipelines", "Business Intelligence", "ML-Driven Insights"],
    "mission"    : "Building data systems that don't just report — they predict and prescribe."
}
```

I don't just analyze data — I architect the story it tells. Currently working as a **Data & Business Analyst** at TrillionData, I bridge the gap between raw numbers and boardroom decisions. My work today is a deliberate foundation for where I'm going: building **robust data engineering pipelines** and ultimately deploying **ML and AI-driven insights** at scale.

My edge? I understand the business *before* I touch the data — and I never stop at the dashboard.

---

## 🛠️ Tech Stack

### 💻 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)

### 📊 Data Analysis & Science
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)

### 📈 Visualization & BI
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat-square&logo=python&logoColor=white)
![IBM Cognos](https://img.shields.io/badge/IBM%20Cognos-052FAD?style=flat-square&logo=ibm&logoColor=white)

### 🗄️ Databases
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

### ⚙️ Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat-square&logo=google-sheets&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)

---

## 🚀 Project Showcase

<details>
<summary><strong>🚗 Car Sales & Profit Analysis — SwiftAuto Traders</strong></summary>
<br/>

> Multi-dimensional analysis of sales performance and profitability across a dealership network. Built an end-to-end BI dashboard identifying top-performing models, seasonal trends, and margin leakages — enabling data-backed inventory and pricing strategy.

**Impact:** Surfaced profitability gaps across dealer segments; actionable insights for pricing optimization.

**Stack:** `Python` `SQL` `HTML` `Power BI` `Pandas`

[![Repo](https://img.shields.io/badge/View%20Project-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ABnirob/Car-Sales-Profit-Analysis-Dashboard-SwiftAuto-Traders-)

</details>

<details>
<summary><strong>🌍 TourOn — Tourism Management System</strong></summary>
<br/>

> Designed and developed a full-featured tour and travel agency management platform. Handles booking flows, package management, and customer data — demonstrating applied database design and systems thinking.

**Impact:** End-to-end digital workflow replacing manual booking processes.

**Stack:** `HTML` `CSS` `JavaScript` `MySQL`

[![Repo](https://img.shields.io/badge/View%20Project-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ABnirob/TourOn)

</details>

<details>
<summary><strong>🔍 Seismarch — Frontend Analytics Interface</strong></summary>
<br/>

> Built a responsive frontend interface for a seismic data search and analysis tool — combining data-driven UX principles with structured data querying workflows.

**Stack:** `HTML` `CSS` `JavaScript`

[![Repo](https://img.shields.io/badge/View%20Project-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ABnirob/seismarch_frontend)

</details>

> 💡 *More projects in active development — data engineering pipelines & ML experiments dropping soon.*

---

## 📌 Experience & Impact

- 📊 Designed and delivered BI dashboards that reduced reporting cycles and surfaced KPIs previously invisible to stakeholders
- 🔄 Automated recurring data workflows, cutting manual processing time and reducing human error in reporting pipelines
- 🧠 Applied statistical analysis and segmentation models to support strategic business decisions with measurable outcomes
- 🏗️ Architected relational database schemas for multi-entity systems, balancing normalization with query performance
- 📈 Translated complex analytical findings into executive-ready narratives — bridging data teams and decision-makers
- 🌐 Currently deepening expertise in data pipeline architecture, cloud infrastructure, and scalable ETL design

---

## 🏅 Certifications & Credentials

> Verified industry credentials from **Google**, **IBM**, **Microsoft**, **Cisco** & **Coursera** — earned through deliberate, continuous upskilling. Click any badge to verify on Credly.

<p align="center">

  <a href="https://www.credly.com/badges/23ef8da3-f6d6-4865-87dd-95e2cb2d7f75" target="_blank">
    <img src="https://img.shields.io/badge/Google-%F0%9F%93%8A%20Data%20Analytics%20Professional%20Certificate-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
  </a>
  <br/><br/>

  <a href="https://www.credly.com/badges/45a07691-87c4-4c33-b8ed-5c8cefbe7024" target="_blank">
    <img src="https://img.shields.io/badge/IBM-%F0%9F%94%AC%20Data%20Analyst%20Professional%20Certificate%20v3-052FAD?style=for-the-badge&logo=ibm&logoColor=white"/>
  </a>
  <br/><br/>

  <a href="https://www.credly.com/badges/45f97d5f-2ce4-461a-85fa-e988d3921e46" target="_blank">
    <img src="https://img.shields.io/badge/Microsoft-%F0%9F%92%BC%20Business%20Analyst%20Professional%20Certificate-0078D4?style=for-the-badge&logo=microsoft&logoColor=white"/>
  </a>
  <br/><br/>

  <a href="https://www.credly.com/badges/2f3dc82e-8664-4431-a657-d1f9a5bdf5ee" target="_blank">
    <img src="https://img.shields.io/badge/Coursera-%F0%9F%93%88%20Data%20Analysis%20%26%20Visualization%20Foundations%20Specialization-0056D2?style=for-the-badge&logo=coursera&logoColor=white"/>
  </a>
  <br/><br/>

  <a href="https://www.credly.com/badges/7323ee13-f277-46c0-966a-a37a358be840" target="_blank">
    <img src="https://img.shields.io/badge/Cisco-%F0%9F%93%A1%20Data%20Analytics%20Essentials-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white"/>
  </a>
  <br/><br/>

  <a href="https://www.credly.com/badges/61fda1b1-cf3c-436e-841e-aa0c6970f399" target="_blank">
    <img src="https://img.shields.io/badge/IBM-%F0%9F%90%8D%20Python%20for%20Data%20Science%20%26%20AI-052FAD?style=for-the-badge&logo=ibm&logoColor=white"/>
  </a>
  <br/><br/>

  <a href="https://www.credly.com/badges/7724971e-a1a1-4080-b506-1940b122dfd5" target="_blank">
    <img src="https://img.shields.io/badge/IBM-%F0%9F%A4%96%20Generative%20AI%20Essentials-052FAD?style=for-the-badge&logo=ibm&logoColor=white"/>
  </a>

</p>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=ABnirob&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ABnirob&layout=compact&theme=tokyonight&hide_border=true"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=ABnirob&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 🧭 Currently Learning

```text
Data Engineering Track
├── 🔧  Apache Spark & PySpark         [▓▓▓▓░░░░░░]  In Progress
├── 🌊  Apache Airflow (Orchestration)  [▓▓▓░░░░░░░]  In Progress
├── ☁️  Cloud Platforms (AWS / GCP)     [▓▓░░░░░░░░]  Exploring
├── 🗃️  dbt (Data Build Tool)           [▓▓░░░░░░░░]  Exploring
└── 🤖  ML Pipelines & MLOps            [▓░░░░░░░░░]  On the Horizon
```

> *The path from analyst to engineer to scientist isn't a career change — it's a deliberate evolution.*

---

## 🤝 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/md-abul-bashar-nirob/">
    <img src="https://img.shields.io/badge/LinkedIn-Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>&nbsp;
  <a href="https://github.com/ABnirob">
    <img src="https://img.shields.io/badge/GitHub-Follow%20My%20Work-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>&nbsp;
  <a href="https://www.facebook.com/ab.nirob.7">
    <img src="https://img.shields.io/badge/Facebook-ab.nirob.7-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/>
  </a>&nbsp;
  <a href="mailto:ab.nirob.7@gmail.com">
    <img src="https://img.shields.io/badge/Email-Say%20Hello-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

<!-- ╔══════════════════════════════════════════════════════╗ -->
<!--          ANIMATED SEPARATOR + FOOTER WAVE              -->
<!-- ╚══════════════════════════════════════════════════════╝ -->

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&pause=1200&color=00D4FF&center=true&vCenter=true&width=780&lines=Data+is+not+just+numbers+%E2%80%94+it%27s+the+language+of+every+strategic+decision.;Building+today%27s+dashboards+%7C+Engineering+tomorrow%27s+pipelines.;The+future+belongs+to+those+who+build+it+%E2%80%94+one+model+at+a+time." alt="Footer Typing" />
  <br/><br/>
  <strong>Md. Abul Bashar Nirob</strong> &nbsp;·&nbsp; <code>Data & Business Analyst</code> &nbsp;·&nbsp; Dhaka, Bangladesh 🇧🇩
  <br/>
  <sub><em>Open to collaborations, data projects, and conversations about the future of analytics.</em></sub>
</div>

<p align="center">
<svg viewBox="0 0 900 130" xmlns="http://www.w3.org/2000/svg" width="100%">
  <defs>
    <linearGradient id="footerbg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#0d1117"/>
      <stop offset="50%"  stop-color="#0a2a4a"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <linearGradient id="fw1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00D4FF" stop-opacity="0.7"/>
      <stop offset="50%"  stop-color="#0080FF" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#00D4FF" stop-opacity="0.7"/>
    </linearGradient>
    <linearGradient id="fw2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00FFCC" stop-opacity="0.4"/>
      <stop offset="50%"  stop-color="#0040FF" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#00FFCC" stop-opacity="0.4"/>
    </linearGradient>
  </defs>
  <rect width="900" height="130" fill="url(#footerbg)"/>
  <circle cx="80"  cy="90" r="2"   fill="#00D4FF" opacity="0.5"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="3s"   repeatCount="indefinite"/></circle>
  <circle cx="820" cy="80" r="2"   fill="#00FFCC" opacity="0.5"><animate attributeName="opacity" values="0.5;0.1;0.5" dur="2.5s" repeatCount="indefinite"/></circle>
  <circle cx="450" cy="95" r="1.5" fill="#ffffff"  opacity="0.3"><animate attributeName="opacity" values="0.1;0.6;0.1" dur="4s"   repeatCount="indefinite"/></circle>
  <path fill="url(#fw1)" opacity="0.6">
    <animate attributeName="d" dur="8s" repeatCount="indefinite"
      values="M0,50 C150,20 300,75 450,45 C600,15 750,65 900,40 L900,0 L0,0 Z;M0,40 C150,65 300,15 450,50 C600,85 750,25 900,50 L900,0 L0,0 Z;M0,50 C150,20 300,75 450,45 C600,15 750,65 900,40 L900,0 L0,0 Z"/>
  </path>
  <path fill="url(#fw2)" opacity="0.5">
    <animate attributeName="d" dur="5s" repeatCount="indefinite"
      values="M0,65 C120,45 250,80 400,58 C550,36 700,72 900,55 L900,0 L0,0 Z;M0,55 C120,72 250,38 400,65 C550,92 700,48 900,62 L900,0 L0,0 Z;M0,65 C120,45 250,80 400,58 C550,36 700,72 900,55 L900,0 L0,0 Z"/>
  </path>
  <path fill="#00D4FF" opacity="0.12">
    <animate attributeName="d" dur="6s" repeatCount="indefinite"
      values="M0,75 C200,58 400,85 600,65 C750,50 850,72 900,68 L900,0 L0,0 Z;M0,68 C200,80 400,52 600,75 C750,90 850,60 900,72 L900,0 L0,0 Z;M0,75 C200,58 400,85 600,65 C750,50 850,72 900,68 L900,0 L0,0 Z"/>
  </path>
</svg>
</p>
