<h1 align="center">Hi 👋, I'm Ajay H J</h1>
<h3 align="center">Passionate Web Developer from India 🇮🇳</h3>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=25&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&width=500&lines=Web+Developer;Backend+Developer;React+Developer;Data+Analytics+Enthusiast" />
</p>

---

## 👨‍💻 About Me

- 🎓 MSc Computer Science (Final Year) – The Oxford College of Science  
- 💼 Web Developer Intern at Infotact Solutions  
- 🌱 Currently learning **Advanced Backend Development & Scalable Systems**
- 💡 Interested in **Web Development, Backend Development & Data Analytics**

---

## 🚀 Tech Stack

### 🌐 Frontend
<p>
<img src="https://skillicons.dev/icons?i=html,css,js,react" />
</p>

### ⚙️ Backend
<p>
<img src="https://skillicons.dev/icons?i=java,spring,nodejs,express" />
</p>

### 🗄 Database
<p>
<img src="https://skillicons.dev/icons?i=mysql,mongodb" />
</p>

### 🛠 Tools
<p>
<img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

---

## 📂 Featured Project

### 🍽 Integrated Food Delivery & Dine-Out Platform

A full-stack web application designed to simplify food ordering, restaurant reservations, and hospitality services.

**Tech Stack**
- Java
- Spring Boot
- React.js
- MySQL

**Features**
- Restaurant menu browsing
- Online food ordering
- Table reservation system
- Microservices-based backend

---

## 📊 GitHub Stats

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=tokyonight" />
</p>

<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&theme=tokyonight" />
</p>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=tokyonight" />
</p>

---

## 👀 Profile Views

<p align="center">
<img src="https://komarev.com/ghpvc/?username=YOUR_GITHUB_USERNAME&label=Profile%20views&color=0e75b6&style=flat" />
</p>

---

## 📫 Connect With Me

<p>
<a href="https://www.linkedin.com/in/ajay-h-j">
<img src="https://img.shields.io/badge/LinkedIn-AjayHJ-blue?style=for-the-badge&logo=linkedin" />
</a>
</p>

📧 Email: **gowdaajay342@gmail.com**

---

## 🐍 Contribution Snake

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: YOUR_GITHUB_USERNAME
          outputs: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
