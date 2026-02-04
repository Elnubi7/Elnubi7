<!-- =======================
GitHub Profile README
User: Elnubi7
======================== -->

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=2800&pause=700&color=00E5FF&center=true&vCenter=true&width=800&lines=AI+Engineer+%7C+ML+%E2%86%92+MLOps;Building+end-to-end+ML+systems+in+production;NLP+%7C+CV+%7C+Deployment+%7C+Pipelines" />

<br/>

<a href="https://github.com/Elnubi7">
  <img src="https://img.shields.io/badge/GitHub-Elnubi7-111?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://www.linkedin.com/in/elnubi/">
  <img src="https://img.shields.io/badge/LinkedIn-elnubi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<img src="https://komarev.com/ghpvc/?username=Elnubi7&style=for-the-badge&color=00E5FF"/>

</div>

---

## 👋 About Me
- AI Engineer focused on **Machine Learning → MLOps**
- I build **production-ready** ML solutions: data → training → deployment → monitoring
- Interests: **NLP**, **Computer Vision**, **Model Serving**, **CI/CD**, **Pipelines**

---

## ⚡ Tech Stack (Icons)
<div align="center">

<img src="https://skillicons.dev/icons?i=python,sklearn,tensorflow,pytorch,opencv,fastapi,flask,docker,kubernetes,linux,git,github,postgres,mongodb,redis,aws,gcp&perline=8" />

</div>

---

## 🧩 What I Do (ML → MLOps)
- **Modeling:** classical ML, deep learning, transformers
- **Data:** preprocessing, feature engineering, validation
- **Deployment:** REST APIs (FastAPI/Flask), containerized services
- **MLOps:** experiment tracking, model registry, CI/CD, monitoring & drift
- **Orchestration:** scheduled training + automated pipelines

---

## 🚀 Featured Work
> Replace these with your real repos (or keep them placeholders).

- **End-to-End ML Pipeline** — data ingestion → training → deployment  
- **NLP Transformer App** — fine-tuning + serving + monitoring  
- **MLOps Production System** — Docker + K8s + CI/CD + tracking  

---

## 📊 Stats & Activity (Animated / Visual)
<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Elnubi7&show_icons=true&theme=tokyonight&hide_border=true" />
<img height="165" src="https://github-readme-streak-stats.herokuapp.com?user=Elnubi7&theme=tokyonight&hide_border=true" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=Elnubi7&theme=tokyonight&no-frame=true&row=1&column=7" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Elnubi7&theme=tokyo-night&hide_border=true" />

</div>

---

## 🐍 Contribution Snake (Animation)
> لازم تضيف Workflow (تحت) عشان الأنيميشن يشتغل.

<div align="center">
  <img src="https://raw.githubusercontent.com/Elnubi7/Elnubi7/output/snake.svg" alt="snake animation" />
</div>

---

## 🎬 GIF (اختار واحد أو حط بتاعك)
<div align="center">

<!-- Option 1: External GIF -->
<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="520" />

<!-- Option 2: Your own GIF (recommended)
1) create folder: assets/
2) add: assets/ai.gif
3) use: <img src="assets/ai.gif" width="520" />
-->

</div>

---

## 🤝 Connect
- LinkedIn: https://www.linkedin.com/in/elnubi/
- GitHub: https://github.com/Elnubi7

---

### ✅ Setup: GitHub Profile Repo
1) اعمل Repo جديد اسمه: **Elnubi7**  
2) حط الـ README.md ده جواه  
3) فعل الـ Snake بالـ workflow اللي تحت

---

## 🧾 GitHub Action for Snake (Paste as a file)
Create this file:
`.github/workflows/snake.yml`

```yml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: Elnubi7
          outputs: |
            dist/snake.svg
      - name: Push snake.svg to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
