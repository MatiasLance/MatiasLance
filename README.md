# 👋 Hi, I'm Marcelo Matias

### DevOps Engineer · Full-Stack Web Developer

**Laravel · Nuxt.js · Vue.js · Docker · Docker Compose · Nginx · DigitalOcean · Linux**

I'm a **DevOps Engineer and Full-Stack Web Developer with 4+ years of experience** designing, building, and deploying scalable web applications.

My work bridges **application development and infrastructure operations**—from building Laravel APIs and Nuxt.js/Vue.js applications to containerizing environments, configuring Nginx and Nginx Proxy Manager, managing Linux servers, and automating deployments.

I'm currently expanding my hands-on knowledge in **Kubernetes and AI-assisted development**.

📍 Davao City, Philippines

<p>
  <a href="https://github.com/MatiasLance">
    <img src="https://img.shields.io/badge/GitHub-MatiasLance-181717?style=for-the-badge&logo=github&logoColor=white">
  </a>
  <a href="https://www.linkedin.com/in/marcelo-matias-38618a274/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
</p>

---

## 🧑‍💻 About Me

I design, build, and deploy web applications and infrastructure across the full lifecycle.

My primary areas of work are:

- 🐘 **Backend development** with Laravel (PHP), RESTful APIs, and MySQL / SQL optimization
- 🟢 **Frontend development** with Nuxt.js and Vue.js
- 📝 **WordPress development** (custom coding, Elementor, Divi, WPBakery)
- 🐳 **Containerization & orchestration** with Docker, Docker Compose, and Kubernetes (learning)
- 🌐 **Web infrastructure & reverse proxying** with Nginx and Nginx Proxy Manager (NPM)
- 🐧 **Server & hosting administration** across Linux/Ubuntu servers, DigitalOcean Droplets, and cPanel
- ⚙️ **Deployment automation** using custom Bash scripts
- 🔐 **DNS & SSL implementation** across Cloudflare, Hostgator, and Hostinger
- 🤖 **AI-assisted development workflows** using ChatGPT, GitHub Copilot, Codex, OpenCode, Cursor, and DeepSeek

---

# 🚀 Featured & Key Projects

Highlights from my public repositories and production/key engineering work.

---

## 🎯 TFW9S (Staging & Production Deployment)

### Full-Stack Application · Laravel · Vue · Docker · Nginx · Socket.IO

TFW9S is organized across frontend and backend repositories alongside deployment and real-time infrastructure components.

Key highlights from this work include:
- Provisioned a staging environment to validate the **"Waiting Lounge"** feature prior to production release.
- Implemented real-time data rendering with **Socket.IO** to improve user engagement.

### Architecture

```text
                    TFW9S
                      │
          ┌───────────┴───────────┐
          │                       │
          ▼                       ▼
     Vue Frontend           Laravel Backend
          │                       │
          └───────────┬───────────┘
                      │
                      ▼
                Real-Time Layer
                   Socket.IO
                      │
          ┌───────────┴───────────┐
          ▼                       ▼
       Docker                  Nginx
          │                       │
          └───────────┬───────────┘
                      ▼
               Deployment
                Environments
