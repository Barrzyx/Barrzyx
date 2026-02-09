## Hi!👋  I'm Felipe Domingues
Studying Software Engineering - FIAP



## 🌐 Where to find me

<p align="left">
  <a href="https://github.com/Barrzyx">
    <img src="https://img.shields.io/badge/GitHub-Barrzyx-181717?style=for-the-badge&logo=github" />
  </a>
  <a href="https://instagram.com/fslipe.domingues">
    <img src="https://img.shields.io/badge/Instagram-@fslipe.domingues-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>
    <a href = "mailto:felipedominguessousa@gmail.com">
     <img src="https://img.shields.io/badge/Gmail-felipedominguessousa@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
</p>

---

## 🛠️ Tech Stack

### Backend

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 



---

## 📊 GitHub Stats


<a href="https://github.com/Barrzyx/github-readme-stats">
  <img height=200 align="center" src="https://github-readme-stats-fast.vercel.app/api?username=Barrzyx&theme=tokyonight" />
</a>
<a href="https://github.com/Barrzyx/convoychat">
  <img height=200 align="center" src="https://github-readme-stats-fast.vercel.app/api/top-langs?username=Barrzyx&layout=compact&langs_count=8&card_width=320&theme=tokyonight&size_weight=0.5&count_weight=0.5" />
</a>

---

## 🚀 Philosophy

> _"It's not the programming language that defines the programmer, but rather their logic. 

---

name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: Barrzyx
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  
---
