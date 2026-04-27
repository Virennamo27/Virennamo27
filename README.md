<!-- HEADER FOREST CARD -->
<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 300" width="100%">
  <defs>
    <linearGradient id="sky" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%"   stop-color="#020d0d"/>
      <stop offset="60%"  stop-color="#071a1a"/>
      <stop offset="100%" stop-color="#0a2a2a"/>
    </linearGradient>
    <linearGradient id="mist" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%"  stop-color="#0e4a4a" stop-opacity="0"/>
      <stop offset="100%" stop-color="#80d4d4" stop-opacity="0.07"/>
    </linearGradient>
    <radialGradient id="moonglow" cx="75%" cy="18%" r="20%">
      <stop offset="0%"   stop-color="#e0f7f7" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#020d0d"  stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="fog" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%"  stop-color="#80d4d4" stop-opacity="0.12"/>
      <stop offset="100%" stop-color="#80d4d4" stop-opacity="0"/>
    </linearGradient>
    <filter id="nameglow" x="-20%" y="-60%" width="140%" height="220%">
      <feGaussianBlur stdDeviation="5" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="softglow" x="-10%" y="-40%" width="120%" height="180%">
      <feGaussianBlur stdDeviation="2.5" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="starglow">
      <feGaussianBlur stdDeviation="0.8" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- SKY -->
  <rect width="900" height="300" fill="url(#sky)"/>
  <rect width="900" height="300" fill="url(#mist)"/>
  <rect width="900" height="300" fill="url(#moonglow)"/>

  <!-- STARS -->
  <g fill="#e0f7f7" filter="url(#starglow)">
    <circle cx="45"  cy="22"  r="0.8" opacity="0.9"/>
    <circle cx="130" cy="14"  r="0.6" opacity="0.7"/>
    <circle cx="200" cy="30"  r="0.9" opacity="0.8"/>
    <circle cx="290" cy="10"  r="0.7" opacity="0.85"/>
    <circle cx="380" cy="25"  r="0.6" opacity="0.6"/>
    <circle cx="480" cy="12"  r="0.8" opacity="0.75"/>
    <circle cx="560" cy="32"  r="0.7" opacity="0.9"/>
    <circle cx="640" cy="18"  r="0.9" opacity="0.7"/>
    <circle cx="740" cy="8"   r="0.6" opacity="0.8"/>
    <circle cx="820" cy="28"  r="0.8" opacity="0.85"/>
    <circle cx="870" cy="15"  r="0.7" opacity="0.65"/>
    <circle cx="95"  cy="48"  r="0.6" opacity="0.6"/>
    <circle cx="175" cy="55"  r="0.8" opacity="0.7"/>
    <circle cx="330" cy="42"  r="0.7" opacity="0.75"/>
    <circle cx="430" cy="58"  r="0.6" opacity="0.5"/>
    <circle cx="700" cy="44"  r="0.8" opacity="0.7"/>
    <circle cx="800" cy="52"  r="0.7" opacity="0.8"/>
  </g>

  <!-- MOON -->
  <circle cx="675" cy="52" r="22" fill="#c8f0f0" opacity="0.92"/>
  <circle cx="683" cy="46" r="18" fill="#0a2a2a" opacity="0.55"/>

  <!-- BACK TREES -->
  <polygon points="30,210 55,130 80,210"    fill="#062020" opacity="0.7"/>
  <polygon points="60,210 88,115 116,210"   fill="#071a1a" opacity="0.8"/>
  <polygon points="100,210 122,138 144,210" fill="#062020" opacity="0.65"/>
  <polygon points="170,210 198,105 226,210" fill="#051515" opacity="0.75"/>
  <polygon points="210,210 232,128 254,210" fill="#071a1a" opacity="0.7"/>
  <polygon points="245,210 268,118 291,210" fill="#062020" opacity="0.8"/>
  <polygon points="610,210 638,108 666,210" fill="#062020" opacity="0.75"/>
  <polygon points="648,210 672,122 696,210" fill="#051515" opacity="0.8"/>
  <polygon points="685,210 706,135 727,210" fill="#071a1a" opacity="0.7"/>
  <polygon points="730,210 758,112 786,210" fill="#062020" opacity="0.75"/>
  <polygon points="770,210 794,128 818,210" fill="#071a1a" opacity="0.8"/>
  <polygon points="808,210 832,140 856,210" fill="#062020" opacity="0.7"/>
  <polygon points="845,210 868,118 891,210" fill="#051515" opacity="0.75"/>

  <!-- FRONT TREES -->
  <polygon points="0,300   28,175  56,300"  fill="#030f0f"/>
  <polygon points="40,300  72,155  104,300" fill="#041414"/>
  <polygon points="85,300  112,168 139,300" fill="#030f0f"/>
  <polygon points="125,300 148,182 171,300" fill="#041414"/>
  <polygon points="729,300 752,178 775,300" fill="#041414"/>
  <polygon points="762,300 788,160 814,300" fill="#030f0f"/>
  <polygon points="800,300 828,170 856,300" fill="#041414"/>
  <polygon points="840,300 866,155 892,300" fill="#030f0f"/>
  <polygon points="875,300 900,172 900,300" fill="#041414"/>

  <!-- GROUND FOG -->
  <rect x="0" y="240" width="900" height="60" fill="url(#fog)" opacity="0.6"/>
  <ellipse cx="450" cy="265" rx="420" ry="28" fill="#80d4d4" opacity="0.04"/>

  <!-- CENTRE TEXT OVERLAY -->
  <rect x="200" y="80" width="500" height="160" rx="8" fill="#020d0d" opacity="0.45"/>
  <line x1="220" y1="102" x2="680" y2="102" stroke="#00B4B4" stroke-width="0.5" opacity="0.3"/>
  <line x1="220" y1="218" x2="680" y2="218" stroke="#00B4B4" stroke-width="0.5" opacity="0.3"/>

  <!-- ROLE BADGES -->
  <rect x="240" y="108" width="150" height="26" rx="5" fill="#00B4B4" opacity="0.12"/>
  <rect x="240" y="108" width="150" height="26" rx="5" fill="none" stroke="#00B4B4" stroke-width="0.8" opacity="0.5"/>
  <text x="315" y="125" font-family="'Segoe UI', Arial, sans-serif" font-size="11" font-weight="600"
        text-anchor="middle" fill="#80d4d4" letter-spacing="1.5">⚡ AI / ML ENGINEER</text>

  <rect x="510" y="108" width="150" height="26" rx="5" fill="#00B4B4" opacity="0.12"/>
  <rect x="510" y="108" width="150" height="26" rx="5" fill="none" stroke="#00B4B4" stroke-width="0.8" opacity="0.5"/>
  <text x="585" y="125" font-family="'Segoe UI', Arial, sans-serif" font-size="11" font-weight="600"
        text-anchor="middle" fill="#80d4d4" letter-spacing="1.5">📊 DATA ANALYST</text>

  <!-- NAME -->
  <text x="450" y="180"
        font-family="'Segoe UI', Arial, sans-serif"
        font-size="54" font-weight="800"
        text-anchor="middle"
        fill="#e0f7f7"
        filter="url(#nameglow)"
        letter-spacing="2">Viren Namo</text>

  <!-- SUBTITLE -->
  <text x="450" y="206"
        font-family="'Segoe UI', Arial, sans-serif"
        font-size="12" font-weight="400"
        text-anchor="middle"
        fill="#80d4d4"
        filter="url(#softglow)"
        letter-spacing="3"
        opacity="0.85">MSc DATA SCIENCE  ·  AMRITA VISHWA VIDYAPEETHAM</text>
</svg>

</div>

<br/>

<!-- TYPING ROLE SWITCHER -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=18&duration=3000&pause=800&color=00B4B4&center=true&vCenter=true&width=500&lines=🤖+AI+%2F+ML+Engineer;📊+Data+Analyst;🧠+NLP+%26+Transformers;🌿+Full-stack+AI+Apps;🌊+Always+Building" alt="Role switcher"/>
</p>

---

## 🌊 Who am I?

```python
viren = {
    "name"       : "Viren Namo",
    "role"       : ["AI/ML Engineer 🤖", "Data Analyst 📊"],
    "studying"   : "MSc Data Science @ Amrita Vishwa Vidyapeetham",
    "superpower" : "Turning messy data into decisions that matter 🌿",
    "currently"  : "Getting better every single day 🚀",
    "fun_fact"   : "I built a Parkinson's screener using just voice. Yes, really. 🫀",
    "vibe"       : "Ocean forest. Deep. Cool. Building in the mist. 🌊",
}
```

> *Where the forest meets the sea — patterns run deep, and so does the data.*
>
> I sit at the intersection of **machine learning** and **data analytics** —
> I can train a model *and* tell you what it means for the business.
> Every repo here is me pushing past what I already know. 🐾

---

## 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Virennamo27&theme=darkhub&no-frame=true&row=1&column=7&margin-w=8" width="100%"/>
</p>

---

## 🛠️ My Toolkit

### 🤖 AI Tools & LLMs

![Claude](https://img.shields.io/badge/Claude%20Code-0a6b6b?style=flat-square&logo=anthropic&logoColor=white)
![ChatGPT](https://img.shields.io/badge/ChatGPT-0e8080?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-0d7377?style=flat-square&logo=google&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Groq](https://img.shields.io/badge/Groq-14a0a0?style=flat-square&logo=groq&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-0a3d3d?style=flat-square&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-093030?style=flat-square&logo=ollama&logoColor=white)

---

### 🧠 ML & Modelling

[![ML Skills](https://skillicons.dev/icons?i=python,pytorch,tensorflow&theme=dark)](https://skillicons.dev)

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0e7a7a?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-0a5a5a?style=flat-square&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-Explainability-0d9090?style=flat-square)
![BERT](https://img.shields.io/badge/BERT-Transformers-0a7070?style=flat-square&logo=huggingface&logoColor=white)
![LLaMA](https://img.shields.io/badge/LLaMA%203.3-Groq-14a0a0?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-0a3d4d?style=flat-square&logo=pandas&logoColor=white)

---

### 📊 Data & Visualization

[![Data Skills](https://skillicons.dev/icons?i=mysql,postgres&theme=dark)](https://skillicons.dev)

![Tableau](https://img.shields.io/badge/Tableau-0e7a7a?style=flat-square&logo=tableau&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-0a4a5a?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-0d6b7a?style=flat-square)
![Plotly](https://img.shields.io/badge/Plotly-0a3d4d?style=flat-square&logo=plotly&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-0e8080?style=flat-square&logo=powerbi&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-0a5a5a?style=flat-square&logo=microsoft-excel&logoColor=white)

---

### 🚀 Deployment & Full-Stack

[![Dev Skills](https://skillicons.dev/icons?i=fastapi,react,git,github,docker&theme=dark)](https://skillicons.dev)

`FastAPI` `React.js` `PostgreSQL` `REST APIs` `Docker`

---

## 🌿 Featured Projects

> *Each project is a current — starting from a real problem, running somewhere useful.*

| 🌊 Project | 🐾 What it does | 🪵 Stack |
|---|---|---|
| [🫀 EchoCheck](https://github.com/Virennamo27/EchoCheck) | Full-stack ML system screening Parkinson's via **voice biomarkers** | Python · FastAPI · React · PostgreSQL |
| [📉 Customer Churn Prediction](https://github.com/Virennamo27/Customer_Churn_Prediction) | End-to-end ML + Tableau dashboard. **ROC-AUC 0.85** with SHAP explainability | XGBoost · SHAP · Tableau · SQL |
| [🤖 TalentScout](https://github.com/Virennamo27/TalentScout) | AI hiring assistant powered by **LLaMA 3.3** — screens candidates & gaps | Python · Groq · React.js |
| [📊 E-Commerce Analytics](https://github.com/Virennamo27/E-Commerce_Sales_Analytics_Dashboard) | Google Data Analytics methodology · RFM segmentation · business dashboard | Python · Pandas · Tableau |
| [🧠 Pragmatic Understanding](https://github.com/Virennamo27/Pragmatic_Understanding) | Sarcasm detection + sentiment analysis using **BERT + contrastive learning** | BERT · PyTorch · Transformers |

---

## 🌙 My ML Journey

```
🌱 Seed                    🌿 Sapling                    🌊 Deep waters
──────────────────────────────────────────────────────────────────────►

📘 Started MSc             🤖 First ML model              🏥 EchoCheck
   Data Science       →       felt like magic         →      Parkinson's
                                                             voice screening

🐍 Fell in love            📊 Discovered SHAP              🧠 Dived into NLP
   with Python +       →       understood WHY          →      BERT · sarcasm
   Pandas                       models predict                detection

⚡ Started with LLMs                                         🚀 Now: shipping
   Groq · LangChain    →    Full-stack AI apps          →      full-stack AI
   Ollama                                                      never stopping
```

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Virennamo27&show_icons=true&hide_border=true&count_private=true&border_radius=12&bg_color=071a1a&title_color=00B4B4&icon_color=00d4d4&text_color=80d4d4" height="165"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Virennamo27&layout=compact&hide_border=true&border_radius=12&bg_color=071a1a&title_color=00B4B4&text_color=80d4d4" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Virennamo27&hide_border=true&border_radius=12&background=071a1a&ring=00B4B4&fire=00d4d4&currStreakLabel=80d4d4&sideLabels=80d4d4&dates=4a9090" height="165"/>
</p>

---

## 🌊 Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Virennamo27&theme=react-dark&bg_color=071a1a&color=00B4B4&line=00d4d4&point=80d4d4&area=true&area_color=0e6b6b&hide_border=true" width="95%"/>
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/Virennamo27/Virennamo27/output/github-contribution-grid-snake-dark.svg" alt="Snake animation"/>
</p>

---

## 🐾 Ask Me About

```
🌊 How to explain ML models to non-technical stakeholders
🌿 SHAP values and model interpretability
🌙 Building end-to-end ML pipelines from scratch
🐾 Getting started with LLMs and prompt engineering
🌊 Data storytelling — making dashboards people actually use
```

---

## 🤝 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/viren-namo-052525274">
    <img src="https://img.shields.io/badge/LinkedIn-Viren%20Namo-0a6b6b?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://github.com/Virennamo27">
    <img src="https://img.shields.io/badge/GitHub-Virennamo27-012a2a?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Virennamo27&style=flat-square&color=0a6b6b&label=Visitors+in+the+deep"/>
</p>

<p align="center">
  <i>💼 Actively looking for AI/ML Engineer & Data Analyst roles.<br/>
  If you're working on something interesting — let's talk. 🌊</i>
</p>

<!-- FOOTER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=1a8a8a,0e6b6b,0a4a4a,012a2a&height=140&section=footer&text=The%20ocean%20is%20deep.%20The%20model%20is%20training.&fontSize=16&fontColor=80d4d4&fontAlignY=65&animation=fadeIn" width="100%"/>
