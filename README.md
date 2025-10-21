<!-- PROFILE README -->

<h1 align="center">Hi 👋, I'm Cameron Rader</h1>
<h3 align="center">ML-minded SWE building useful AI systems — from medical imaging to search, RL, and HPC tooling</h3>

- 🔭 I’m currently working on **a Reinforcement Learning agent for 2048** and **GAN variants** for the “I’m Something of a Painter Myself” challenge.
- 🎓 M.S. CS (Machine Learning) @ **UT Knoxville** (in progress); B.S. CS @ **Christian Brothers University** (NCAA soccer alum).
- 🧠 Interests: **ML systems, medical AI, NLP/RAG, RL, MLOps, HPC**.
- 📍 Knoxville, TN (open to relocate) • 🇺🇸 Work authorization: **U.S. citizen/authorized**.
- 📫 Reach me: **Cameronrader11@outlook.com**
- <img width="25" height="25" alt="image" src="https://github.com/user-attachments/assets/99db9721-ac1f-491f-bd91-207a35fdc38d" /> Lets connect: www.linkedin.com/in/cameron-rader-b69b2b1ba


---

## 🚀 Highlights
- **Medical Imaging**: Built an end-to-end MRI knee abnormality classifier (MRNet) reaching **~0.91 AUC** on validation with attention and transfer learning.
- **Search & QA**: Fine-tuned **BERT** for QA with custom **RAG** pipelines on long-context text (“A Study in Scarlet”).
- **Full-Stack + Optimization**: Shipped an **EA FC 24 SBC** solver (Flask + Next.js + Selenium + Genetic Algo) to cut solve time from minutes to seconds.
- **HPC & Reliability**: Contributed to UTK’s HPSC migration from **Gold → ColdFront**, integrating different technologies that come along with HPC management like Slurm, Ldap, etc.
- **Content Automation**: Built an AI video pipeline that hit **3.1M views** and **12K+ followers** in <30 days.


---

## 🧩 Featured Projects
<!-- Keep 3–6 and lead with value; include tech + a tiny metric if available. -->

### 1) MRNet — Knee MRI Classification (DL from scratch, attention + transfer learning)
Repo: https://github.com/Cameronr11/DL_Project_Team15  
**What it is:** Deep-learning pipeline to detect ACL/meniscus/abnormalities across **axial/coronal/sagittal** views.  
**How it works:** Pretrained CNN backbones (ResNet/DenseNet), attention-weighted slice pooling, augmentation scheduling, ensemble across views.  
**Results:** ~**0.91 AUC** on validation; class imbalance handled with weighted losses and stratified sampling.  
**Stack:** PyTorch, torchvision, Optuna, TensorBoard.

### 2) BERT + RAG — Long-context QA on “A Study in Scarlet”
Repo: https://github.com/Cameronr11/COSC524_Team9_Project2  
**What it is:** Fine-tuning **bert-base-uncased** for extractive QA with **custom RAG** to overcome token limits.  
**How it works:** Sentence/scene chunking, retrieval pipeline, and QA fine-tuning notebooks; install script for repro.  
**Stack:** Hugging Face Transformers, Python.

### 3) SBC Auto — EA FC 24 Squad Builder Challenge Solver (full-stack + GA)
Repo: https://github.com/Cameronr11/SBCAUTO  
**What it is:** End-to-end system that **scrapes inventory** and uses a **genetic algorithm** to build valid, **cost-efficient** squads meeting SBC constraints.  
**Stack:** **Next.js** (TypeScript, Tailwind, Chakra UI) + **Flask** API, Selenium, SQLite/Pandas, Socket.IO (real-time progress).  
**Impact:** Reduces solve time from ~10 minutes to **<45 seconds** (typical runs).

### 4) 2048 — Reinforcement Learning Agent (in progress; repo will be public)
Repo: https://github.com/Cameronr11/2048_RL  
**Focus:** DQN/dueling/CNN variants; training curriculum aimed at consistent 1024→2048 tiles; symmetry augmentation & target update schedules.  
**Stack:** PyTorch, Gymnasium-style envs, NumPy.  
**Status:** Hardening training loop & evaluation harness; code will be opened soon.

### 5) Monet-Style GANs — “I’m Something of a Painter Myself” (in progress)
Repo: https://github.com/Cameronr11/Team12_GAN  
**Focus:** Multiple GAN variants for style transfer & generation; local + cluster training workflows.  
**Status:** Private while polishing baselines and evaluation; will open with reproducible configs.

### 6) ColdFront Migration & HPC Tooling (work project; code private)
**What it is:** Migration from legacy **Gold** to **ColdFront** for UTK’s HPSC portal
**Impact:** Smoother access management and more stable workflows for SLURM-based research jobs.  
**Role:** Graduate Research Assistant (HPSC).  
**Stack:** Python, SLURM, plugins, infra scripting (details redacted).

---

## 💼 Experience
**Graduate Research Assistant — High-Performance Scientific Computing, UTK**  
*Aug 2024 – Present*  
- Supported researchers with job orchestration, **SLURM** troubleshooting, and workload optimization on multi-GPU clusters.  
- Unified our project/access management with the HPC stack and standardized software installs (modules, dependencies, CUDA stacks), enabling faster onboarding, consistent runs, and fewer support escalations.  

**Software Developer Intern — Product Discovery, AutoZone**  
*May 2023 – Aug 2023*  
- Contributed to backend modules powering **semantic search** used by millions of customers.  
- Built an automated unit-testing framework to reduce deployment errors; improved **synonym handling** for better precision.

---

## 🛠️ Languages and Tools
<p align="left">
  <a href="https://aws.amazon.com" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/>
  </a>
  <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/>
  </a>
  <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/>
  </a>
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>
  </a>
  <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/>
  </a>
  <a href="https://www.java.com" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/>
  </a>
  <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/>
  </a>
  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/>
  </a>
  <a href="https://nextjs.org/" target="_blank" rel="noreferrer">
    <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/>
  </a>
  <a href="https://nodejs.org" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/>
  </a>
  <a href="https://www.postgresql.org" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/>
  </a>
  <a href="https://www.python.org" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>
  </a>
  <a href="https://pytorch.org/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/>
  </a>
  <a href="https://reactjs.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/>
  </a>
  <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/>
  </a>
  <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/>
  </a>
  <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/>
  </a>
</p>

---

## 📊 GitHub Stats
<p>
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=cameronr11&show_icons=true&hide_title=true&hide=contribs&include_all_commits=true" alt="cameronr11" />
</p>
<!-- Optional: add top-langs card after a few more public repos to avoid skew -->
<!-- <p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=cameronr11&layout=compact" /></p> -->

---

### ☕ Now
- Improving my 2048 RL evaluation and training throughput.
- Researching different variations of the GAN architecture
- Helping UTK researchers sharpen SLURM workflows.
- Side Project: Working with the new Wan2.2 Animate 14B model to upgrade my Tiktok Automation pipeline for better Ai related content

