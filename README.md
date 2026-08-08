# Hello, I'm Thomas! 👋

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2D9EF7&center=true&vCenter=true&width=435&lines=IT+Security+Student;CS+Graduate;Rust+%26+Self-hosted+AI+Tinkerer" alt="Typing SVG" />
</div>

<div align="center">
  <a href="https://thomasgav.com">
    <img src="https://img.shields.io/badge/Portfolio-4D4D4D?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" />
  </a>
  <a href="mailto:tgruch@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>

## 🧑🏻‍💻 About Me

I finished my Computer Science degree and am now specializing in **IT security**. My CS background covered full-stack development (Java/Spring Boot, JavaScript, Python), and these days I'm most interested in how systems work under the hood — and how they break.

- 🎓 CS graduate, currently studying **IT security** (networking, offensive/defensive security, secure development)
- 🤖 Running **self-hosted AI** experiments: local LLM chat UIs, live meeting transcription, speech-to-text
- 🛠️ Comfortable across the stack, happiest close to the backend

## 💻 Tech Stack

### Languages
<div align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</div>

### Backend & Data
<div align="center">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
</div>

### Frontend & Mobile
<div align="center">
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React Native" />
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white" alt="Vue.js" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
</div>

### Systems & Tools
<div align="center">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark" />
</div>

## 📊 GitHub Analytics
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=tgavri&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="GitHub Stats" />
  <br/>
  <img src="https://github-readme-streak-stats-eight.vercel.app?user=tgavri&theme=dark" alt="GitHub Streak" />
</div>

## 🚀 Featured Projects

### [MitID Gateway](https://github.com/tgavri/MitID) 🦀
> An authentication API gateway written in **Rust**, inspired by Denmark's national digital ID system (MitID). My hands-on project for learning systems programming — building login and token-verification endpoints from scratch instead of reading yet another tutorial.
- Async HTTP server with **Axum** and **Tokio**
- `POST /auth/login` and `POST /auth/verify` token flow, typed request/response models with **Serde**
- Work in progress — the goal is a small but production-shaped auth service

### [Skynet + Jitsi Meet Integration](https://github.com/tgavri/skynet-integration)
> Self-hosted AI meeting assistant: wiring [Skynet](https://github.com/tgavri/skynet) (an API server for AI services) into a **Jitsi Meet** frontend so meetings get live AI features without sending audio to third-party clouds.
- **Live transcription** streamed over WebSockets via Faster Whisper
- **Meeting summaries & action items** generated with vLLM / Ollama (Llama 3.1)
- Custom Jitsi Meet frontend integration (prejoin flow, in-call UI hooks, PWA assets)
- Companion repos: [skynet](https://github.com/tgavri/skynet) (the AI service backend) and [meet2stuffs](https://github.com/tgavri/meet2stuffs)

### [QwenBot](https://github.com/tgavri/qwenbot)
> A self-hosted LLM chat interface for **Qwen 2.5** models (0.5B → 72B parameters), deployed on datacenter GPUs (NVIDIA A100 80GB).
- Real-time token streaming over **WebSockets**
- Dynamic model switching from the UI — pick the model size that fits the task
- Dockerized deployment with HTTPS and persistent local model cache

### [Perplexity Alfred Workflow](https://github.com/tgavri/Perplexity-Alfred) ⭐
> My most-starred repo: an **Alfred workflow** for macOS that puts Perplexity AI one keystroke away — type `p <query>` and get answers without opening a browser.
- Instant queries from anywhere in macOS
- Copy results to clipboard or open the full answer in the browser

### [Whisper Fun](https://github.com/tgavri/whisper-fun)
> Speech-to-text experiments with **OpenAI Whisper**, trying out different ways to serve the same model.
- **Flask** web UI and a **Streamlit** variant for quick comparisons
- Reproducible dev environment with a Nix shell

### [ML Travel Game](https://github.com/tgavri/TravelAppExam)
> Exam project for my Machine Learning and Mobile Development electives (spring 2025): a travel guessing game backed by a machine-learning model.
- ML implementation in **Python**, following the course pipeline (data prep → training → evaluation)
- **React Native / Expo** app as the mobile frontend
- Includes the full write-up and presentation material (in Danish and English)

<details>
<summary><b>📦 Earlier CS coursework</b></summary>
<br/>

- **[DronePizza](https://github.com/tgavri/DronePizza)** — 24-hour exam project: REST API for a drone-based pizza delivery system. Java, Spring Boot, JPA, Docker.
- **[KinoXP](https://github.com/tgavri/KinoXP)** — Cinema booking system with seat selection and scheduling. Java, Spring Boot, MySQL.
- **[Vegan Recipe Generator](https://github.com/tgavri/Vegan-Recipe-Generator)** — Ingredient-based recipe generation with Llama 2. Python, Flask, Replicate API.
- **[Guessr](https://github.com/tgavri/guessr)** — Guessing game built with a student group.

</details>

## 🌟 Interests & Hobbies
- 🏞️ Traveling and exploring new destinations
- 🍳 Cooking and experimenting with different cuisines
- 🚵 Mountain biking and swimming

## 📫 Let's Connect
<div align="center">
  <a href="mailto:tgruch@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://thomasgav.com">
    <img src="https://img.shields.io/badge/Portfolio-4D4D4D?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" />
  </a>
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=tgavri&color=brightgreen&style=flat-square" alt="Profile Views" />
</div>

---
<div align="center">
  <img src="https://camo.githubusercontent.com/ff1d4eb768b74fa335491dd8a7e87d95017665c1570e5a8828fddfdb728da450/68747470733a2f2f63617073756c652d72656e6465722e76657263656c2e6170702f6170693f747970653d776176696e6726636f6c6f723d6772616469656e74266865696768743d3130302673656374696f6e3d666f6f746572" alt="end" />
</div>

<!-- ============================================================
  OLD README BACKUP (commented out on 2026-08-07)
  NOTE: every comment-closer inside the backup was escaped as "--/>" so
  this whole block stays hidden. To restore, change "--/>" back
  to dash-dash-angle-bracket and remove this wrapper comment.
=============================================================

<img src="https://raw.githubusercontent.com/Yash621/Yash621/refs/heads/master/images/github-banner.png" alt="Banner" />

  # Hello, I'm Thomas! 👋
<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2D9EF7&center=true&vCenter=true&width=435&lines=Computer+Science+Student;Tech+Enthusiast" alt="Typing SVG" />
</div>

<div align="center">
  <a href="https://thomasgav.com">
    <img src="https://img.shields.io/badge/Portfolio-4D4D4D?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" />
  </a>
</div>

## 🧑🏻‍💻 About Me
<!--<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=tgavri&theme=darkhub&no-frame=true&column=7&margin-w=15&margin-h=15" alt="Trophy" />
</div> --/>

I'm an it security student focused on creating innovative solutions and meaningful applications. With a strong foundation in both frontend and backend development, I enjoy tackling complex problems and building scalable solutions.

- 🔭 Currently working on **React Native** and **Machine Learning** projects
- 🌱 Expanding my knowledge in **Python** and **TypeScript**
- 💡 Always open to learning new technologies
<!--- 👯 Looking to collaborate on interesting projects--/>

## 💻 Tech Stack

### Languages & Frameworks
<div align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</div>

### Frontend Development
<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white" alt="Vue.js" />
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React Native" />
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
</div>

### Backend & Database
<div align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white" alt="JSON" />
  <img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
</div>

### Tools & Platforms
<div align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/NPM-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="NPM" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
</div>

## 📊 GitHub Analytics
<div align="center">
  <!--<img src="https://github-readme-stats.vercel.app/api?username=tgavri&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="GitHub Stats" />--/>
  <img src="https://github-readme-streak-stats-eight.vercel.app?user=tgavri&theme=dark" alt="GitHub Streak" />
  <!--<img src="https://github-readme-activity-graph.vercel.app/graph?username=tgavri&theme=dark&hide_border=true" alt="GitHub Activity Graph" /> --/>
</div>

## 🚀 Featured Projects

### [DronePizza](https://github.com/tgavri/DronePizza)
> A 24-hour exam project: An autonomous drone-based pizza delivery system that streamlines order management and delivery operations. Features include:
- Real-time drone status tracking (active, out of order, retired)
- Order management with expected delivery times
- User-friendly dashboard for delivery management
- Drone assignment system for orders
- Built with Java, Spring Boot, JPA, JDBC, RESTful API, and Docker

### [Vegan Recipe Generator](https://github.com/tgavri/Vegan-Recipe-Generator)
> An AI-powered web application that generates healthy vegan recipes based on available ingredients. Features include:
- AI-powered recipe generation using Meta Llama 2
- User-friendly interface for ingredient input
- Responsive design for all devices
- Danish language support
- Nutritional information display
- Built with Python, Flask, Replicate API, and HTML/CSS

### [KinoXP](https://github.com/tgavri/KinoXP)
> A cinema booking system with features like:
- Seat selection interface
- Movie scheduling
- User authentication
- Booking management
- Built with Java, Spring Boot, and MySQL

## 🌟 Interests & Hobbies
- 🏞️ Traveling and exploring new destinations
- 🍳 Cooking and experimenting with different cuisines
- 🚵 Mountain biking and swimming

## 📫 Let's Connect
<div align="center">
  <a href="mailto:tgruch@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://thomasgav.com">
    <img src="https://img.shields.io/badge/Portfolio-4D4D4D?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" />
  </a>
</div>

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="Readme Quotes" />
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=tgavri&color=brightgreen&style=flat-square" alt="Profile Views" />
</div>

---

<!--
old backup section from before
# Hello, I'm Thomas! 👋

[![Twitter Badge](https://img.shields.io/badge/-@YourTwitterHandle-1DA1F2?style=flat&logo=twitter&logoColor=white)](https://twitter.com/YourTwitterHandle)
[![LinkedIn Badge](https://img.shields.io/badge/-YourLinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YourLinkedIn/)
[![GitHub Badge](https://img.shields.io/badge/-YourGitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/tgavri)

## 👨‍💻 About Me
I'm a Full Stack Developer passionate about building meaningful and impactful projects. I enjoy working with cutting-edge technologies and love to learn and collaborate with others.

- 🌱 Currently learning Python.
- 🚀 Looking to contribute to any project. Get in touch.

## 🛠️ Skills & Technologies

### Programming Languages
- Java, JavaScript, Python.

### Web Development
- Frontend: HTML, CSS, Vue.js
- Backend: Node.js

### Tools & Platforms
- Git, Docker, NPM

### Database Technologies
- SQL (MySQL), NoSQL (MongoDB)

## 🔥 GitHub Stats
![Your GitHub Stats](https://github-readme-stats.vercel.app/api?username=tgavri&show_icons=true&hide_title=true&hide=prs&count_private=true&theme=dark)

## 🚀 Current Projects
- **[Guessr](https://github.com/tgavri/guessr)**: A guessr game, created in collab with student group.

## 🌱 Fun Facts
- I enjoy traveling, cooking, and mountainbiking.
- I love exploring new places and trying different cuisines.

## 📫 How to Reach Me
- **Email**: [tgruch@gmail.com](mailto:tgruch@gmail.com)
- **Website**: [thomasgav.com](http://thomasgav.com)

## 📚 Connect with Me
<!-- - [LinkedIn](https://www.linkedin.com/in/YourLinkedIn/)
- [Twitter](https://twitter.com/YourTwitterHandle)
- [Portfolio](https://thomasgav.com)

## 👁️ Profile Views
![Profile views](https://komarev.com/ghpvc/?username=tgavri&color=brightgreen)

---

Thanks for stopping by! Let's build something amazing together! 😊

<!--
**tgavri/tgavri** is a ✨ _special_ ✨ repository because its README.md (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I'm currently working on ...
- 🌱 I'm currently learning ...
- 👯 I'm looking to collaborate on ...
- 🤔 I'm looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
--/>

============================================================ -->
