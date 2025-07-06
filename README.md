---

## ✨ Who Am I?

```yaml
name: Chaitali Vasist
education: 3rd Year B.E. in Information Science @ RIT (CGPA: 9.48)
roles:
  - Full-Stack Developer
  - AI/ML Researcher
  - IoT & Smart AgriTech Explorer
  - Product Strategist
skills:
  - React, Node.js, Python, SQL, C, HTML, CSS
  - AI/ML, IoT, Web3
fun_fact: "Bharatanatyam Dancer | Sprinter | Tech-for-Good Evangelist"
```

---

### 💀 Brain Tumor Detector (MRI)

* ML-based platform for real-time MRI analysis
* Website built for end-to-end prediction and research publication in process

### 🌿 Smart Hydroponics System

* IoT-driven project for automated plant nutrition using sensor feedback
* Built from scratch including dataset generation, dashboard, and actuator logic

### 🎥 NFThing: Web3 Movie Streaming

* Full-stack development with React & Node.js for a decentralized streaming site
* Managed product features and user experience design

### 💪 AlgoQuest

* A gamified learning roadmap for mastering algorithms interactively
* Includes animations, quizzes, and progression tracking
* Built with HTML/CSS/JS and educational APIs

### 🚨 Disaster Resource Finder

* Web app for real-time discovery of relief resources in emergencies
* Features geolocation, filtering, authorized submissions, and live data mapping

---

## 🛠️ Tech Stack

```text
Languages: Python, Java, C, SQL, HTML, CSS, JavaScript
Frameworks: React, Node.js, Express, Flask
Tools: Git, GitHub, Docker, Postman, VS Code
Platforms: Azure, Netlify, Render, GitHub Actions
AI/ML: Scikit-learn, PyTorch, TensorFlow, Prompt Engineering
IoT: Sensors, Microcontrollers, Data Logging & Automation
```

---

## 📊 GitHub Stats

---

## 🌟 Achievements

* 🎓 Top CGPA Holder @ RIT (9.48)
* 🔧 Prompt Engineering Certified
* 💃 National-level Bharatanatyam Dancer
* 🏀 College Sports: Football, Table Tennis
* 💼 Managed product dev at NFThing

---

## 🌍 Languages I Speak

* English – Proficient
* Hindi – Proficient
* Kannada – Proficient

---

## 📢 Let's Collaborate!

---

> *"Create boldly. Solve sustainably. Code with purpose."*

---

## ✨ Auto-Updating GitHub Stats Setup

To enable auto-update of GitHub stats and streaks:

1. Go to **Actions** tab on this repo and enable GitHub Actions.
2. Add the following `.github/workflows/update-stats.yml` file:

```yaml
name: Update README Stats

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Generate GitHub Stats
        uses: anuraghazra/github-readme-stats@master
        with:
          username: chaitalivasist
      - name: Commit & Push
        run: |
          git config --global user.name 'github-actions'
          git config --global user.email 'actions@github.com'
          git add .
          git commit -m "✅ Auto-update stats"
          git push
```

---

> Updated: July 2025
