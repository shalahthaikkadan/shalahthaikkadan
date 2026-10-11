<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Mohammad%20Shalah&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Computer%20Science%20Engineer%20%7C%20Python%20Developer%20%7C%20Data%20Science%20Enthusiast&descSize=16&descAlignY=58" alt="header" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=7C3AED&center=true&vCenter=true&width=720&lines=Building+practical+software+solutions;Python+%7C+Flask+%7C+Django+%7C+React;AI+%7C+Computer+Vision+%7C+IoT;Learn+%E2%86%92+Build+%E2%86%92+Break+%E2%86%92+Fix+%E2%86%92+Repeat" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=shalahthaikkadan&label=PROFILE%20VIEWS&color=blueviolet&style=flat-square" alt="Profile Views" />
<img src="https://img.shields.io/github/followers/shalahthaikkadan?label=FOLLOWERS&style=flat-square&color=007ec6" alt="Followers" />
<img src="https://img.shields.io/badge/dynamic/json?url=https://api.github.com/users/shalahthaikkadan&query=$.public_repos&label=REPOSITORIES&style=flat-square&color=007ec6" alt="Repositories" />

<br/><br/>

<a href="mailto:shalahthaikkadan@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/shalah-thaikkadan-40142b32b/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/shalahthaikkadan"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

---

## 👨‍💻 About Me

I'm a **B.Tech Computer Science & Engineering** graduate from **Royal College of Engineering and Technology, Kerala**, passionate about building practical software, learning new technologies, and turning ideas into real-world projects.

```python
class MohammadShalah:
    role       = "Computer Science Engineer"
    focus      = ["Python", "Backend Development", "Data Science", "AI & Automation"]
    experience = ["Web Apps", "REST APIs", "Computer Vision", "IoT / Embedded"]
    learning   = ["SQL", "Data Analysis", "Data Visualization", "Machine Learning"]
    open_to    = ["Python Developer", "Data Analyst", "Backend Developer", "ML roles"]
    philosophy = "Learn → Build → Break → Fix → Improve → Repeat"

    def current_goal(self):
        return "Turn strong fundamentals into real-world, production-grade projects 🚀"
```

---

## 🛠️ Tech Stack

<div align="center">

| Category | Technologies |
|:--|:--|
| **💻 Languages** | <img src="https://skillicons.dev/icons?i=py,ts,js,html,css" /> |
| **⚙️ Backend** | <img src="https://skillicons.dev/icons?i=django,flask,redis" /> |
| **🌐 Frontend** | <img src="https://skillicons.dev/icons?i=react,vite,tailwind" /> |
| **🗄️ Databases** | <img src="https://skillicons.dev/icons?i=mysql,postgres" /> |
| **🤖 AI / Vision** | <img src="https://skillicons.dev/icons?i=opencv" /> ![YOLO](https://img.shields.io/badge/YOLO-111111?style=flat-square&logo=ultralytics&logoColor=white) ![Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white) |
| **🔌 Hardware / IoT** | <img src="https://skillicons.dev/icons?i=raspberrypi,arduino" /> |
| **☁️ DevOps & Tools** | <img src="https://skillicons.dev/icons?i=git,github,githubactions,cloudflare,vscode" /> |

</div>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🌊 Career Sea
AI-powered career discovery platform with personalized pathways, learning roadmaps, and an interactive AI mentor. *(Team project — contributor)*

**Stack:** `React` `Vite` `TypeScript` `Tailwind CSS` `Cloudflare Workers` `PostgreSQL` `Gemini API`

- 🧭 Three career directions per assessment (mainstream, adjacent, wildcard)
- 🗺️ Step-by-step roadmaps with study guides
- 💬 Context-aware AI mentor chat
- 🔐 JWT authentication
- ⚡ Edge architecture + CI/CD via GitHub Actions

[![Repo](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/shalahthaikkadan/Career-Sea)
[![Live](https://img.shields.io/badge/Live%20Demo-careersea.in-success?style=flat-square&logo=googlechrome&logoColor=white)](https://careersea.in)

</td>
<td width="50%" valign="top">

### 📄 AI Resume Analyzer
AI-powered recruitment platform that analyzes, scores, and ranks resumes, then generates a personalized technical quiz for each candidate.

**Stack:** `Python` `Django REST Framework` `Celery` `Redis` `Gemini API` `Tailwind CSS` `JavaScript`

- 📑 PDF & DOCX resume parsing
- 🧠 AI scorecard (skills, experience, red flags, positives)
- 📝 Auto-generated 10-question quiz per candidate
- 📊 Admin dashboard ranked by AI score
- ⚡ Async processing with Celery + Redis
- 🔐 JWT authentication

[![Repo](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/shalahthaikkadan/Resume-Analyzer)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🗑️ AI-Based Smart Waste Segregation System
An intelligent hardware + AI system that automatically detects and sorts waste on a conveyor.

**Stack:** `Python` `YOLO` `OpenCV` `Raspberry Pi` `Picamera2` `Sensors` `Stepper Motor`

```mermaid
flowchart LR
    A[📷 Camera Capture] --> B[🤖 YOLO Detection]
    B --> C{Waste Class}
    C -->|Plastic| D[♻️ Bin 1]
    C -->|Paper| E[♻️ Bin 2]
    C -->|Other| F[♻️ Bin 3]
    G[📡 Sensors] --> B
    B --> H[⚙️ Stepper Motor / Conveyor]
    H --> C
```

</td>
</tr>
</table>

<details>
<summary><b>🔎 Architecture overview — AI Resume Analyzer</b></summary>

```mermaid
flowchart LR
    U[Candidate] -->|Upload PDF/DOCX| API[Django REST API]
    API -->|Enqueue task| R[(Redis)]
    R --> W[Celery Worker]
    W -->|Parse + prompt| G[Google Gemini API]
    G --> W
    W -->|Scorecard + Quiz| DB[(Database)]
    DB --> D[Admin Dashboard<br/>Ranked Applicants]
```

</details>

---

## 📊 GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=shalahthaikkadan&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shalahthaikkadan&layout=compact&theme=tokyonight&hide_border=true" />

<br/>

<img src="https://streak-stats.demolab.com/?user=shalahthaikkadan&theme=tokyonight&hide_border=true" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=shalahthaikkadan&theme=tokyo-night&hide_border=true&area=true" width="100%" />

</div>

---

## 🧭 Learning Roadmap

```mermaid
flowchart LR
    A[🐍 Python] --> B[🗄️ SQL]
    B --> C[📊 Data Analysis]
    C --> D[📈 Visualization]
    D --> E[🤖 Machine Learning]
    E --> F[🧠 Data Science]
    F --> G[🚀 Real-World Projects]
    style A fill:#3776AB,color:#fff
    style G fill:#7C3AED,color:#fff
```

| Area | Status |
|:--|:--|
| Python & Backend (Flask, Django) | 🟢 Building projects |
| SQL & Databases (MySQL, PostgreSQL) | 🟢 Working knowledge |
| Computer Vision & IoT | 🟢 Hands-on project experience |
| Data Analysis & Visualization | 🟡 In progress |
| Machine Learning & Data Science | 🟡 In progress |

---

## 🎯 Career Interests

<div align="center">

![Python](https://img.shields.io/badge/Python%20Development-3776AB?style=flat-square&logo=python&logoColor=white)
![Backend](https://img.shields.io/badge/Backend%20Development-009688?style=flat-square&logo=fastapi&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Data Science](https://img.shields.io/badge/Data%20Science-FF6F00?style=flat-square&logo=jupyter&logoColor=white)
![ML](https://img.shields.io/badge/Machine%20Learning-8A2BE2?style=flat-square&logo=scikitlearn&logoColor=white)
![SQL](https://img.shields.io/badge/SQL%20%26%20Databases-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Automation](https://img.shields.io/badge/AI%20%26%20Automation-111111?style=flat-square&logo=openai&logoColor=white)

</div>

---

## 💡 Philosophy

> **Learn → Build → Break → Fix → Improve → Repeat.**

The best way to learn technology is through practical projects, problem solving, experimentation, and continuous improvement.

---

## 🤝 Let's Connect

I'm open to **opportunities, collaborations, and conversations** around Python, backend, data, and AI.

| | |
|:--|:--|
| 📧 **Email** | [shalahthaikkadan@gmail.com](mailto:shalahthaikkadan@gmail.com) |
| 💼 **LinkedIn** | [linkedin.com/in/shalah-thaikkadan-40142b32b](https://www.linkedin.com/in/shalah-thaikkadan-40142b32b/) |
| 🐙 **GitHub** | [github.com/shalahthaikkadan](https://github.com/shalahthaikkadan) |

<div align="center">

⭐ If you find my projects useful, feel free to **star** the repositories!

**Keep Learning. Keep Building. Keep Growing.** 🚀

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%" alt="footer"/>

</div>
