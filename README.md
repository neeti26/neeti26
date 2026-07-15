<img src="https://komarev.com/ghpvc/?username=neeti26&label=Profile%20Views&color=8b5cf6&style=for-the-badge" alt="profile views" />

<p align="center">
  <svg width="100%" viewBox="0 0 1200 420" xmlns="http://www.w3.org/2000/svg" style="background: linear-gradient(135deg, #020617 0%, #111827 50%, #0f172a 100%);">
    <defs>
      <linearGradient id="neuralFlow" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#00d9ff" />
        <stop offset="50%" stop-color="#0084ff" />
        <stop offset="100%" stop-color="#7c3aed" />
      </linearGradient>
      <radialGradient id="brainCore" cx="40%" cy="50%" r="60%">
        <stop offset="0%" stop-color="#00ffff" stop-opacity="0.8" />
        <stop offset="40%" stop-color="#0084ff" stop-opacity="0.6" />
        <stop offset="100%" stop-color="#7c3aed" stop-opacity="0.2" />
      </radialGradient>
      <filter id="glow">
        <feGaussianBlur stdDeviation="4" result="coloredBlur" />
        <feMerge>
          <feMergeNode in="coloredBlur" />
          <feMergeNode in="SourceGraphic" />
        </feMerge>
      </filter>
      <filter id="deepGlow">
        <feGaussianBlur stdDeviation="8" result="coloredBlur" />
        <feMerge>
          <feMergeNode in="coloredBlur" />
          <feMergeNode in="SourceGraphic" />
        </feMerge>
      </filter>
    </defs>
    
    <!-- Brain hemisphere outline -->
    <g filter="url(#deepGlow)">
      <path d="M 380 180 Q 400 140 420 120 Q 440 100 460 90 Q 480 85 500 90 Q 520 95 540 110 Q 560 125 570 145 Q 580 165 575 185 Q 570 205 560 220 Q 550 230 535 235 Q 520 240 500 238 Q 480 235 460 230 Q 440 225 420 220 Q 400 215 385 205 Q 375 195 380 180 Z" fill="url(#brainCore)" stroke="#00ffff" stroke-width="2" opacity="0.9" />
      
      <!-- Brain convolutions -->
      <path d="M 420 150 Q 430 145 440 150" fill="none" stroke="#00d9ff" stroke-width="2" opacity="0.8" />
      <path d="M 420 170 Q 435 165 450 170" fill="none" stroke="#0084ff" stroke-width="2" opacity="0.7" />
      <path d="M 425 190 Q 440 188 455 192" fill="none" stroke="#00d9ff" stroke-width="2" opacity="0.8" />
      <path d="M 430 210 Q 445 208 460 212" fill="none" stroke="#0084ff" stroke-width="2" opacity="0.7" />
    </g>
    
    <!-- Binary/AI pattern inside brain -->
    <g font-family="monospace" font-size="10" fill="#00ffff" opacity="0.6" filter="url(#glow)">
      <text x="420" y="155">1</text>
      <text x="435" y="145">0</text>
      <text x="450" y="160">1</text>
      <text x="428" y="175">1</text>
      <text x="445" y="185">0</text>
      <text x="460" y="175">1</text>
      <text x="420" y="200">0</text>
      <text x="440" y="210">1</text>
      <text x="455" y="200">1</text>
      <text x="430" y="220">1</text>
      <text x="450" y="228">0</text>
    </g>
    
    <!-- Neural connections - left side (input) -->
    <g stroke="url(#neuralFlow)" stroke-width="3" fill="none" stroke-linecap="round" opacity="0.85" filter="url(#glow)">
      <path d="M 200 140 Q 280 160 380 180" />
      <path d="M 200 180 Q 290 180 380 190" />
      <path d="M 200 220 Q 280 200 380 200" />
      <path d="M 200 260 Q 290 220 380 210" />
    </g>
    
    <!-- Input node points (left) -->
    <circle cx="200" cy="140" r="5" fill="#00ffff" opacity="0.9" filter="url(#glow)" />
    <circle cx="200" cy="180" r="5" fill="#00ffff" opacity="0.9" filter="url(#glow)" />
    <circle cx="200" cy="220" r="5" fill="#0084ff" opacity="0.8" filter="url(#glow)" />
    <circle cx="200" cy="260" r="5" fill="#00ffff" opacity="0.9" filter="url(#glow)" />
    
    <!-- Central brain sphere -->
    <circle cx="470" cy="190" r="95" fill="none" stroke="url(#neuralFlow)" stroke-width="3" opacity="0.5" />
    <circle cx="470" cy="190" r="75" fill="none" stroke="#00d9ff" stroke-width="2" opacity="0.4" />
    
    <!-- Neural connections - right side (output) -->
    <g stroke="url(#neuralFlow)" stroke-width="3" fill="none" stroke-linecap="round" opacity="0.85" filter="url(#glow)">
      <path d="M 560 165 Q 700 145 900 110" />
      <path d="M 565 190 Q 720 180 920 170" />
      <path d="M 560 215 Q 700 220 900 250" />
      <path d="M 555 235 Q 710 250 920 290" />
    </g>
    
    <!-- Output node points (right) -->
    <circle cx="900" cy="110" r="5" fill="#7c3aed" opacity="0.9" filter="url(#glow)" />
    <circle cx="920" cy="170" r="5" fill="#00ffff" opacity="0.9" filter="url(#glow)" />
    <circle cx="900" cy="250" r="5" fill="#7c3aed" opacity="0.9" filter="url(#glow)" />
    <circle cx="920" cy="290" r="5" fill="#00ffff" opacity="0.9" filter="url(#glow)" />
    
    <!-- Circuit-like nodes -->
    <g fill="#00ffff" opacity="0.7" filter="url(#glow)">
      <circle cx="650" cy="120" r="4" />
      <circle cx="680" cy="145" r="4" />
      <circle cx="720" cy="160" r="4" />
      <circle cx="750" cy="140" r="4" />
      <circle cx="800" cy="120" r="4" />
      <circle cx="650" cy="260" r="4" />
      <circle cx="680" cy="235" r="4" />
      <circle cx="720" cy="250" r="4" />
      <circle cx="760" cy="270" r="4" />
      <circle cx="810" cy="280" r="4" />
    </g>
    
    <!-- Text labels -->
    <g font-family="Arial, sans-serif" fill="#f8fafc" font-weight="700">
      <text x="80" y="340" font-size="32" font-weight="800">Neeti Malu</text>
      <text x="80" y="375" font-size="18" font-weight="600" fill="#cbd5e1">AI Systems Engineer | GraphRAG | Multimodal AI | GRC Automation</text>
      <text x="80" y="405" font-size="14" fill="#94a3b8">Building intelligent systems that turn data into decisions</text>
    </g>
    
    <!-- Animated pulse effect markers -->
    <circle cx="470" cy="190" r="90" fill="none" stroke="#00ffff" stroke-width="1" opacity="0.2" />
  </svg>
</p>

---

## 🚀 Who I Am

I'm an **AI Engineer** passionate about building intelligent systems that think, reason, and act at production scale. I work across **GraphRAG**, **multimodal AI**, **computer vision**, **NLP**, and **compliance automation**—turning complex problems into elegant AI solutions.

My focus is on creating **high-performance, reasoning-first AI** systems that move beyond pattern matching to true intelligence. I've built fraud detection engines that reduce noise by 94.5%, multimodal pipelines that generate assets in minutes, and GRC automation that maps real-time threats to compliance frameworks.

**What drives me:** Building the next generation of AI products that are faster, smarter, and more reliable. Open to collaborating on **high-impact AI/ML projects**, **research**, and **product development** opportunities.

---

<p align="center">
  <a href="https://linkedin.com/in/neeti-malu"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://neetieportfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="mailto:neetimalu@gmail.com"><img src="https://img.shields.io/badge/Email-ff4d4d?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/neeti26"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<div align="center">
  <img src="https://img.shields.io/badge/Role-AI%20Engineer-8B5CF6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Graph%20%26%20Multimodal%20AI-06B6D4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Mode-Shipping%20production%20systems-10B981?style=for-the-badge" />
</div>

<p align="center">
  <code>system status: online · graph reasoning active · multimodal pipelines live · compliance automation running</code>
</p>

---

## ✦ Mission

I design and build AI systems that turn signal into intelligence, intelligence into automation, and automation into real-world impact. My work is centered on advanced reasoning, multimodal understanding, and high-performance AI products.

<div align="center">
  <img src="https://img.shields.io/badge/Impact-94.5%25%20token%20reduction-10B981?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Speed-70%25%20faster%20queries-06B6D4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Fraud%20%7C%20GRC%20%7C%20Content%20AI-8B5CF6?style=for-the-badge" />
</div>

- 🤖 Building next-generation AI products for reasoning, automation, and decision support
- 🧠 Working across GraphRAG, LLMs, computer vision, NLP, and agentic workflows
- ⚡ Focused on scalable, production-grade AI systems and intelligent infrastructure

---

## ⚡ Core Focus

- 🕸️ Designing graph-native retrieval systems that improve reasoning quality and reduce noise
- 🧠 Building multimodal pipelines that turn raw inputs into polished, production-ready outputs
- 🛡️ Automating compliance and risk-critical workflows with intelligent decision layers
- 🤖 Exploring agentic AI, reasoning frameworks, and intelligent orchestration systems

<div align="center">
  <img src="https://img.shields.io/badge/Stack-GraphRAG%20%2B%20LLMs-8B5CF6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Stack-Computer%20Vision%20%2B%20NLP-06B6D4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Stack-Agentic%20AI-10B981?style=for-the-badge" />
</div>

---

## 🚀 Signature Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔍 FraudGraph

![Python](https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=white)
![TigerGraph](https://img.shields.io/badge/TigerGraph-7C3AED?style=flat-square&logo=graphql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-06B6D4?style=flat-square&logo=fastapi&logoColor=white)

An advanced graph-powered fraud intelligence platform engineered to uncover suspicious patterns with higher precision and lower inference cost.

> ⚡ Efficient retrieval · 🕸️ Graph reasoning · 🧠 Decision support at scale

</td>
<td width="50%" valign="top">

### 🧠 StepOne Content Intelligence

![Next.js](https://img.shields.io/badge/Next.js-111827?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-7C3AED?style=flat-square&logo=typescript&logoColor=white)
![GPT-4o](https://img.shields.io/badge/GPT--4o_Vision-06B6D4?style=flat-square&logo=openai&logoColor=white)

A multimodal pipeline that transforms raw inputs into polished, multi-platform assets with minimal manual effort.

> 📸 Vision + language workflows · ⚙️ Rapid prototyping · 🎯 Quality scoring loops

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ Automated GRC Engine

![Python](https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=white)
![ML](https://img.shields.io/badge/ML-7C3AED?style=flat-square&logo=scikit-learn&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-06B6D4?style=flat-square&logo=fastapi&logoColor=white)

A compliance automation layer that maps alerts to regulatory frameworks and surfaces actionable risk signals.

> 📋 NIST + ISO 27001 mapping · 🤖 Risk prioritization · 📄 Audit-ready reporting

</td>
<td width="50%" valign="top">

### 💬 Emotion → Offer Mapper

![Python](https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-7C3AED?style=flat-square&logo=spacy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-06B6D4?style=flat-square&logo=scikit-learn&logoColor=white)

A machine-learning project that connects behavioral signals to more relevant, high-performing recommendations.

> 📈 Better relevance · 🏷️ Intent modeling · 🧪 Data-driven experimentation

</td>
</tr>
</table>

---

## 🧰 Core Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![TigerGraph](https://img.shields.io/badge/TigerGraph-E34A26?style=for-the-badge&logo=tigergraph&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

---

## 📈 GitHub Pulse

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=neeti26&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="github stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=neeti26&theme=tokyonight&hide_border=true" alt="streak stats" />
</p>

---

## 🌐 Let’s Connect

If you’re building in AI, data systems, or product-driven automation, I’d love to connect.

<p align="center">
  <a href="https://linkedin.com/in/neeti-malu"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:neetimalu@gmail.com"><img src="https://img.shields.io/badge/Email%20Me-ff4d4d?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" />
</div>
