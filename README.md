# Hi, I'm Rajat Jaiswal 👋

> Passionate Full-Stack Developer & AI Enthusiast — building AI-powered, cloud-integrated apps and learning every day.

[![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=rajatjaishwal.rajatjaishwal)](https://github.com/rajatjaishwal) 
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?logo=linkedin&logoColor=white&link=https://www.linkedin.com/in/rajatjaiswal)](https://www.linkedin.com/in/rajatjaiswal) 
[![Portfolio](https://img.shields.io/badge/-Portfolio-0A66C2?logo=firefox&logoColor=white&link=https://your-portfolio.example.com)](https://your-portfolio.example.com)
[![LeetCode](https://img.shields.io/badge/-LeetCode-FFA116?logo=leetcode&logoColor=white&link=https://leetcode.com/rajatjaiswal)](https://leetcode.com/rajatjaiswal)

---

🎯 Quick Snapshot
- Full-Stack Developer (React.js, Node.js, Express.js, MongoDB)
- AI/ML enthusiast — YOLOv8, TensorFlow basics, Python
- Cloud exposure: AWS (S3, Lambda, EC2), Azure Databricks (student projects)
- Looking for roles: Developer | AI/ML Engineer | Cloud-backed systems

---

## 🚀 What I Build (select projects)

### Smart Waste Management System
- AI-powered waste categorization using YOLOv8
- Route optimization and recyclables marketplace
- Stack: Python (YOLOv8), Node.js backend, React frontend, MongoDB
- Repo: https://github.com/rajatjaishwal/smart-waste-management (replace with your repo link)

### E-Shopping Website
- Full-stack e-commerce with authentication, dynamic product pages, cart, orders
- Tech: React, Node.js, Express, MongoDB, Stripe (payments)
- Repo: https://github.com/rajatjaishwal/e-shopping (replace with your repo link)

### Healthcare Prediction Platform
- AI-driven disease prediction + prescription management + hospital/ambulance integration
- Tech: Python ML models, Node.js API, React dashboard
- Repo: https://github.com/rajatjaishwal/healthcare-prediction (replace with your repo link)

---

## 🧰 Tech Stack

Frontend
- ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) React.js
- ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white) Tailwind CSS

Backend & Databases
- ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white) Node.js
- ![Express](https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white) Express.js
- ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) MongoDB
- ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) MySQL

AI / Data
- ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) Python
- YOLOv8 • TensorFlow (basics) • Gemini API

Cloud & DevOps
- ![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white) AWS (S3, Lambda, EC2)
- Azure Databricks (student projects)

---

## 📊 GitHub Stats & Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=rajatjaishwal&show_icons=true&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=rajatjaishwal&layout=compact&theme=radical)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=rajatjaishwal&theme=radical)

---

## 🧠 Currently Learning
- Advanced ML pipelines & model deployment (MLOps)
- Transformer-based models and multimodal AI
- Scalable backend patterns and event-driven systems
- Cloud-native services and serverless architectures

---

## ✨ Fun Fact / Tech Fact
> "Tech Fact: YOLOv8 can perform real-time object detection with high accuracy and is optimized for edge deployment."  
(Or replace with a dynamic Quote of the Day — see optional automation below.)

---

## 🏆 Achievements & Highlights
- Built and deployed AI + Cloud projects for college hackathons
- Created real-time dashboards in Power BI & Tableau for market data
- Presented on Cloud, AI, and Distributed Systems to technical audiences

---

## 📫 Let’s Connect
- LinkedIn: https://www.linkedin.com/in/rajatjaiswal
- Portfolio: https://your-portfolio.example.com
- Email: rajatjaiswaloffical1@gmail.com 
- LeetCode: https://leetcode.com/rajatjaiswal

---

## 📌 Notes & Customization
- Replace repository links and portfolio/email with your real links.
- The GitHub stats widgets use the GitHub username: `rajatjaishwal`. If your GitHub profile uses a different username (e.g., `RajatJaiswal`), update the widget URLs accordingly.
- If you want the "Quote of the Day" or "Tech Fact" to change daily, you can use the optional GitHub Action below to update this README automatically.

---

## Optional: Auto-update “Quote of the Day” (GitHub Action)
Add this workflow to .github/workflows/daily-quote.yml to fetch a random quote once per day and inject it into README. Replace the fetch script or API as you prefer.

```yaml
name: Daily README Quote
on:
  schedule:
    - cron: '0 8 * * *' # UTC 08:00 daily
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4

      - name: Get quote and update README
        run: |
          QUOTE=$(curl -s "https://api.quotable.io/random" | jq -r '.content + " — " + .author')
          # This replaces the Tech Fact block between markers <!--QUOTE_START--> and <!--QUOTE_END-->
          sed -i '/<!--QUOTE_START-->/, /<!--QUOTE_END-->/c\<!--QUOTE_START-->\n> '"$QUOTE"'\n<!--QUOTE_END-->' README.md

      - name: Commit & Push changes
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "41898282+github-actions[bot]@users.noreply.github.com"
          git add README.md
          git commit -m "chore: update quote of the day"
          git push
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

To use the action:
1. Create .github/workflows/daily-quote.yml with the content above.
2. Ensure README.md contains the markers <!--QUOTE_START--> and <!--QUOTE_END--> where you want the dynamic quote.

Example insertion in README (replace the static Tech Fact line above with the markers):
<!--QUOTE_START-->
> Your starting quote will be here.
<!--QUOTE_END-->

---

If you want, I can:
- Push this README directly to a new branch in your GitHub profile repo (I can create a branch + PR or push to your profile repo if you give the repo name).
- Generate the optional workflow file and push it too.
- Customize wording, badges, colors, or project entries and add screenshots or animated GIFs.

What should I do next — (A) push README.md to a branch in your profile repo, (B) also create the daily-quote workflow, or (C) make any content tweaks (tone, length, badges)?
