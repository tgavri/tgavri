<div align="center">

# Thomas

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=2D9EF7&center=true&vCenter=true&width=480&lines=IT+Security+Student;CS+Graduate;Network+%26+Self-hosted+Infrastructure" alt="Typing SVG" />

<p>
  <a href="https://thomasgav.com">
    <img src="https://img.shields.io/badge/Portfolio-2D9EF7?style=flat-square&logo=google-chrome&logoColor=white" alt="Portfolio" />
  </a>
  <a href="mailto:tgruch@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

</div>

---

## About

Computer Science graduate now specializing in **IT security** — networking, offensive and defensive
security, and secure development. My CS background is full-stack (Java/Spring Boot, Python,
TypeScript), which I'm increasingly pointing at the infrastructure and security side.

Most of what I build lately runs on hardware I own: DNS infrastructure, self-hosted LLM deployment,
and a home lab I use to apply coursework to a live network instead of a sandbox.

**Currently working on** — recursive DNS with DNSSEC validation, WireGuard mesh networking, and
network segmentation for untrusted IoT devices.

---

## 🚀 Projects

### 🔒 Home Network Security Lab

> Self-hosted DNS infrastructure and network segmentation on a Raspberry Pi 5, built to apply
> coursework to a live network rather than a sandbox.

**DNS infrastructure**
- **Pi-hole** as a network-wide DNS sinkhole, serving all clients via DHCP-advertised DNS
- **Unbound** as a local recursive resolver — queries resolve from the root servers down rather than
  being forwarded to a third-party provider, with **DNSSEC** validated at the network edge
- Closed client-side bypass paths: disabled the router's secondary-DNS advertisement (clients were
  silently falling back past the sinkhole) and disabled IPv6 to prevent ISP-supplied resolvers
  arriving via router advertisements

**Remote access**
- **Tailscale** (WireGuard) mesh with the Pi as exit node and subnet router — DNS filtering that
  follows the device onto mobile networks, and LAN access with no inbound port exposed

**Router hardening** — ASUS RT-AX53U
- Disabled **WPS** (Pixie Dust / Reaver PIN recovery), replaced a weak WPA2 passphrase, reviewed
  DHCP scope and client isolation

**Traffic analysis**
- Query-log analysis to profile device behaviour — identified smart-TV telemetry and ACR endpoints,
  and traced an unrecognised domain to its parent application by correlating DNS against running
  processes
- Audited local listening services with `lsof` / `ss`; found a message broker bound to all
  interfaces rather than loopback

**In progress** — Proxmox cluster on repurposed hardware (Pi as corosync QDevice) · OpenWrt flash
for transparent DNS redirection · 802.1Q VLAN segmentation for IoT isolation

<sub>`Pi-hole` · `Unbound` · `DNSSEC` · `WireGuard` · `Linux` · `Bash` · `OpenWrt`</sub>

<br/>

### 🤖 [QwenBot](https://github.com/tgavri/qwenbot)

> Self-hosted LLM chat interface for **Qwen 2.5** models (0.5B → 72B parameters), deployed on
> datacenter GPUs (NVIDIA A100 80GB).

- Real-time token streaming over **WebSockets**
- Dynamic model switching from the UI — pick the model size that fits the task
- Dockerized deployment with HTTPS and a persistent local model cache

<sub>`Python` · `Docker` · `WebSockets` · `CUDA`</sub>

<br/>

### ⌨️ [Perplexity Alfred Workflow](https://github.com/tgavri/Perplexity-Alfred) ⭐

> My most-starred repo: an **Alfred workflow** for macOS that puts Perplexity AI one keystroke away.
> Type `p <query>` and get answers without opening a browser.

- Instant queries from anywhere in macOS
- Copy results to clipboard or open the full answer in the browser

<sub>`Alfred` · `Shell` · `macOS`</sub>

<br/>

### 🎙️ [Whisper Fun](https://github.com/tgavri/whisper-fun)

> Speech-to-text experiments with **OpenAI Whisper**, comparing different ways to serve the same
> model.

- **Flask** web UI and a **Streamlit** variant for side-by-side comparison
- Reproducible dev environment with a Nix shell

<sub>`Python` · `Flask` · `Streamlit` · `Nix`</sub>

<br/>

### 🗺️ [ML Travel Game](https://github.com/tgavri/TravelAppExam)

> Exam project for my Machine Learning and Mobile Development electives (spring 2025): a travel
> guessing game backed by a machine-learning model.

- ML pipeline in **Python** — data preparation, training, evaluation
- **React Native / Expo** mobile frontend
- Includes the full write-up and presentation material (Danish and English)

<sub>`Python` · `React Native` · `Expo`</sub>

<details>
<summary><b>📦 Earlier CS coursework</b></summary>

<br/>

- **[DronePizza](https://github.com/tgavri/DronePizza)** — 24-hour exam project: REST API for a drone-based pizza delivery system. Java, Spring Boot, JPA, Docker.
- **[KinoXP](https://github.com/tgavri/KinoXP)** — Cinema booking system with seat selection and scheduling. Java, Spring Boot, MySQL.
- **[Vegan Recipe Generator](https://github.com/tgavri/Vegan-Recipe-Generator)** — Ingredient-based recipe generation with Llama 2. Python, Flask, Replicate API.
- **[Guessr](https://github.com/tgavri/guessr)** — Guessing game built with a student group.

</details>

---

## 🛠️ Tech

| | |
|---|---|
| **Security & Networking** | Wireshark · nmap · tcpdump · DNS / DNSSEC · Pi-hole · Unbound · WireGuard · OpenWrt · Linux hardening |
| **Languages** | Java · Python · TypeScript · JavaScript · Bash |
| **Backend** | Spring Boot · FastAPI · Flask · Node.js |
| **Data** | MySQL · MongoDB · Redis |
| **Frontend & Mobile** | React Native · Expo · Vue.js · Tailwind CSS |
| **Infrastructure** | Linux · Docker · Proxmox · Git · Nix |

---

## 📊 GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=tgavri&show_icons=true&theme=dark&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats" />
</div>

---

## Outside the terminal

Traveling · cooking · mountain biking · swimming

<div align="center">
<br/>
<sub>Open to internships and student positions in IT security — <a href="mailto:tgruch@gmail.com">get in touch</a>.</sub>
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
