
# Hi, I'm Anshuman Polai 👋

<p align="left">
<strong>Cybersecurity • Data Analytics • AI • Full Stack Development</strong><br>
Building secure, data-driven applications and continuously learning modern security, analytics, and automation technologies.
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=TECH-ANSHU&label=Profile%20Views&style=flat-square" />
  <img src="https://img.shields.io/github/followers/TECH-ANSHU?style=flat-square" />
  <img src="https://img.shields.io/badge/Open%20to-Internships-success?style=flat-square" />
</p>

---

## About Me

I'm a **B.Tech Computer Science (Cyber Security)** student at **ITER, Siksha 'O' Anusandhan University** with a strong interest in **Cybersecurity, Data Analytics, Artificial Intelligence, and Full Stack Development**.

I enjoy solving practical problems through automation, data analysis, and secure software engineering.

**Areas of Interest**
- Cybersecurity & SOC
- Threat Detection
- Data Analytics & BI
- AI-powered Security
- Python Automation
- Web Development

---

## Education

**B.Tech – Computer Science & Engineering (Cyber Security)**  
ITER, Siksha 'O' Anusandhan University  
2021 – 2025

---

## Technical Skills

### Programming
Python • Java • JavaScript • HTML • CSS • C • C++

### Data Analytics
SQL • Excel • Pandas • NumPy • Data Cleaning • EDA • Visualization

### Cybersecurity
Wireshark • Burp Suite • Kali Linux • Nmap • OpenSSL • Splunk • Nessus • OpenVAS • Metasploit

### Web Development
React • Bootstrap • Node.js • SQLite • MySQL

### Tools
Git • GitHub • VS Code • Linux • Bash

---

## Certifications

- Deloitte Data Analytics Job Simulation
- Tata Cybersecurity Analyst Job Simulation
- ANZ Cyber Security Job Simulation
- AWS APAC Solutions Architecture
- SQL (Intermediate) – HackerRank
- Skill India Digital Hub Certifications

---

## Featured Projects

| Project | Description |
|---------|-------------|
| AI Threat Detection System | AI-assisted security monitoring |
| Data Analytics Portfolio | SQL, Excel & Python dashboards |
| TLS Cryptography Analysis | TLS packet inspection using Wireshark |
| Student Data Keeper | Python + SQLite automation |
| GlyphBloc Website | Responsive business website |

---

## GitHub Analytics

<p>
<img height="165" src="https://github-readme-stats.vercel.app/api?username=TECH-ANSHU&show_icons=true&hide_border=true&theme=transparent"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TECH-ANSHU&layout=compact&hide_border=true&theme=transparent"/>
</p>

<p>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=TECH-ANSHU&hide_border=true&theme=transparent"/>
</p>

## Contribution Graph

<img src="https://github-readme-activity-graph.vercel.app/graph?username=TECH-ANSHU&theme=github-compact"/>

---

## Career Objective

Seeking opportunities in:

- Cybersecurity
- Security Operations (SOC)
- Data Analytics
- Business Intelligence
- AI Engineering
- Full Stack Development

I enjoy building secure, scalable, and data-driven solutions that create measurable impact.

---

## Connect

- GitHub: https://github.com/TECH-ANSHU
- LinkedIn: https://www.linkedin.com/in/anshumanpolai-cyber
- Email: anshumanpolai@gmail.com

---

> "Secure systems. Meaningful insights. Continuous learning."

---

# GitHub Contribution Snake (Fully Configured)

Create the following file:

`.github/workflows/snake.yml`

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: TECH-ANSHU
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Then embed this image in the README:

```html
<p align="center">
<img src="https://raw.githubusercontent.com/TECH-ANSHU/TECH-ANSHU/output/github-contribution-grid-snake-dark.svg">
</p>
```
