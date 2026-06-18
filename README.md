<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:388bfd&height=200&section=header&text=Mostafa%20Ayman&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Software%20Engineer%20%E2%80%94%20Cairo%2C%20Egypt&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mostafa-ayman-98b554309)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://mostafa-ayman-portofolio.vercel.app)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mostafaayman14g@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](#)

</div>

---

## About Me

Final-year Software Engineering student at **Misr International University**, Cairo — actively seeking backend and full-stack engineering roles.

I build systems end-to-end: from ML inference pipelines running on GPU infrastructure to microservice architectures orchestrated over message queues. My focus is on the intersection of backend engineering and applied AI — designing systems that are fast, observable, and production-ready.

- 🎓 B.Sc. Software Engineering — Misr International University *(graduating 2025)*
- 💼 Interned at **Commercial International Bank (CIB)** — Sustainable Finance & FinTech ESG
- 🌍 Languages: Arabic · English
- 📬 Open to backend and full-stack engineering roles — Cairo or remote

---

## 🔨 What I'm Building

### Scenolytics — AI Audition Evaluation Platform

> A distributed system that evaluates acting performances across four dimensions: script alignment, vocal emotion, video emotion, and eye expressiveness.

The architecture spans several independent microservices connected via RabbitMQ. Each service owns a slice of the analysis pipeline:

| Service | What it does |
|---|---|
| **ASR + Alignment** | Transcribes audio with SeamlessM4T, aligns words to script via WhisperX |
| **Tone Analysis** | Scores vocal emotion per sentence using pitch, energy & prosody signals |
| **Video Emotion** | BiLSTM model trained on RAVDESS classifies facial emotion frame-by-frame |
| **Eye Expressiveness** | MediaPipe iris tracking computes gaze transitions and EAR-based blink patterns |
| **Orchestrator** | Node.js gateway coordinates scoring, aggregates results, persists to PostgreSQL |

GPU inference (SeamlessM4T ~2.6 GB) runs on **Modal's serverless GPU infrastructure** — eliminating cold-start overhead without managing servers.

---

## 🛠 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & APIs**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-005571?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Modal](https://img.shields.io/badge/Modal-000000?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=MostafaAyman-14&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=388bfd&icon_color=388bfd&text_color=c9d1d9&ring_color=1f6feb" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MostafaAyman-14&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=388bfd&text_color=c9d1d9&langs_count=6" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=MostafaAyman-14&theme=github-dark-blue&hide_border=true&background=0d1117&ring=388bfd&fire=1f6feb&currStreakLabel=388bfd" />

</div>

---

## 🌱 Currently Learning

- Advanced GPU inference optimization on serverless infrastructure (Modal)
- Distributed tracing and observability for microservice systems
- System design patterns for high-throughput ML pipelines

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:388bfd,50:1f6feb,100:0d1117&height=100&section=footer" width="100%"/>

</div>
