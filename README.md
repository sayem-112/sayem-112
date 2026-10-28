<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:11111b,50:1e1e2e,100:313244&height=200&section=header&text=Mofftasim%20Hossain%20Sayem&fontSize=40&fontColor=cdd6f4&fontAlignY=38&desc=Backend%20Engineer%20%C2%B7%20Distributed%20Systems%20%C2%B7%20AI%20Infrastructure&descSize=16&descAlignY=58&animation=fadeIn" alt="Mofftasim Hossain Sayem" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mofftasim-hossain-sayem/"><img src="https://img.shields.io/badge/LinkedIn-89b4fa?style=for-the-badge&logo=linkedin&logoColor=1e1e2e" alt="LinkedIn" /></a>
  <a href="mailto:muftasimhossain@gmail.com"><img src="https://img.shields.io/badge/Email-f38ba8?style=for-the-badge&logo=gmail&logoColor=1e1e2e" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Dhaka%2C%20Bangladesh-b4befe?style=for-the-badge&logo=googlemaps&logoColor=1e1e2e" alt="Dhaka, Bangladesh" />
  <img src="https://img.shields.io/badge/Open%20to%20work-a6e3a1?style=for-the-badge" alt="Open to work" />
</p>

---

### About me

I'm a Computer Science and Engineering graduate from **BRAC University**, interested in building software that is reliable, maintainable, and useful.

My primary focus is **backend engineering with Go**, with additional experience building full-stack applications and integrating LLMs into real-world workflows.

I'm particularly interested in:

- Backend architecture, APIs, and data-intensive applications
- Concurrency, distributed systems, and reliability
- AI-powered developer tools and LLM infrastructure
- Database design, search, and performance optimization

I'm currently improving my engineering fundamentals, building practical projects, and looking for opportunities to grow as a software engineer.

---

### Tech stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=go,ts,js,python,react,html,css,mysql,postgres,sqlite,mongodb,docker,git,github,vscode&perline=8" alt="Technology stack"/>
  </a>
</p>

---

### Featured projects

<table>
<tr>
<td width="50%" valign="top">

### SortWise

<img src="https://img.shields.io/badge/Release%3A%20v0.6.0-a6e3a1?style=flat-square" alt="Release: v0.6.0" /> <img src="https://img.shields.io/badge/Go%20%7C%20SQLite%20%7C%20React%20%7C%20LLMs-89b4fa?style=flat-square&logo=go&logoColor=1e1e2e" alt="Go | SQLite | React | LLMs" />

**An open-source, local-first app that turns X bookmarks into an AI-organized, searchable knowledge base.**

- Built a multimodal AI pipeline to summarize, tag, and categorize posts and images.
- Combined vector search with SQLite FTS5 for semantic and full-text retrieval.
- Engineered durable Go background workers to process AI tasks independently of API requests.

<a href="https://github.com/sayem-112/SortWise"><img src="https://img.shields.io/badge/View%20Code-45475a?style=for-the-badge&logo=github&logoColor=cdd6f4" alt="View Code" /></a> <a href="https://github.com/sayem-112/SortWise/releases"><img src="https://img.shields.io/badge/Download-a6e3a1?style=for-the-badge&logo=github&logoColor=1e1e2e" alt="Download" /></a>

</td>
<td width="50%" valign="top">

### Polaris

<img src="https://img.shields.io/badge/BuildFest%202026%20Finalist-f9e2af?style=flat-square" alt="BuildFest 2026 Finalist" /> <img src="https://img.shields.io/badge/Next.js%20%7C%20MongoDB%20%7C%20Gemma%204-89b4fa?style=flat-square&logo=nextdotjs&logoColor=1e1e2e" alt="Next.js | MongoDB | Gemma 4" />

**A Bengali-first platform that turns students' goals, constraints, and deadlines into actionable application roadmaps.**

- Built a Gemma 4 strategist using typed tool calling over structured student data.
- Implemented persistent memory to maintain student context across planning sessions.
- Fused BM25 and vector retrieval using Reciprocal Rank Fusion (RRF).
- Built retry-safe, batched LLM generation with atomic MongoDB claims and deduplication.

<a href="https://github.com/DesignNovae/Polaris"><img src="https://img.shields.io/badge/View%20Code-45475a?style=for-the-badge&logo=github&logoColor=cdd6f4" alt="View Code" /></a> <a href="https://polaris-ai-academy.vercel.app"><img src="https://img.shields.io/badge/Live%20Demo-89b4fa?style=for-the-badge&logo=vercel&logoColor=1e1e2e" alt="Live Demo" /></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Rift

<img src="https://img.shields.io/badge/Status%3A%20In%20progress-fab387?style=flat-square" alt="Status: In progress" /> <img src="https://img.shields.io/badge/Go%20%7C%20PostgreSQL%20%7C%20React%20%7C%20S3-89b4fa?style=flat-square&logo=go&logoColor=1e1e2e" alt="Go | PostgreSQL | React | S3" />

**A self-hosted reader that synchronizes PDFs and EPUBs across devices, including offline changes.**

- Designed per-user, versioned change feeds with compaction and tombstones for offline-safe synchronization.
- Streamed real-time updates through PostgreSQL and Server-Sent Events.
- Implemented AES-GCM envelope encryption and resumable, client-encrypted multipart uploads to S3.
- Built a PostgreSQL job queue for horizontally scalable Go workers.

<a href="https://github.com/sayem-112/Rift"><img src="https://img.shields.io/badge/View%20Code-45475a?style=for-the-badge&logo=github&logoColor=cdd6f4" alt="View Code" /></a>

</td>
<td width="50%" valign="top">

### Multi-Portrait Biometric Unlinkability Under Generative Editing

<img src="https://img.shields.io/badge/Thesis%3A%20A%2B-cba6f7?style=flat-square" alt="Thesis: A+" /> <img src="https://img.shields.io/badge/PyTorch%20%7C%20Stable%20Diffusion-89b4fa?style=flat-square&logo=pytorch&logoColor=1e1e2e" alt="PyTorch | Stable Diffusion" />

**Mitigating facial re-identification in group photos subjected to generative editing.**

- Developed face-localized perturbations to protect multiple identities within a single image.
- Designed a teacher–student pipeline distilling diffusion-guided privacy optimization into a lightweight model.
- Evaluated identity protection through open source models and an ensemble of face-recognition models.
- Assessed robustness to cropping, JPEG/WebP compression, denoising, and successive generative edits.

<sub>Biometric privacy · Computer vision · Diffusion models · Knowledge distillation<br/>Four-member BRAC University thesis · Manuscript in preparation</sub>

</td>
</tr>
</table>

---

### Recognition

- **Finalist**, Infinity AI BuildFest 2026: national AI hackathon with 3,500+ registrants
- **Special Recognition (Top Projects)**, Build with Gemma AI Innovation Challenge 2026
- **National Finalist**, Techathon Nationals 2026, IUT Robotics Society

---

### GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sayem-112&show_icons=true&include_all_commits=true&count_private=true&theme=catppuccin_mocha&hide_border=true" alt="GitHub stats" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sayem-112&layout=compact&theme=catppuccin_mocha&hide_border=true" alt="Top languages" height="170" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=sayem-112&hide_border=true&background=1e1e2e&stroke=313244&ring=cba6f7&fire=fab387&currStreakNum=cdd6f4&sideNums=cdd6f4&currStreakLabel=cba6f7&sideLabels=a6adc8&dates=6c7086" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:313244,50:1e1e2e,100:11111b&height=110&section=footer" alt="" width="100%" />
</p>
