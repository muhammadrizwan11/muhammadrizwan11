<div align="center">

# Muhammad Rizwan
### AI Solutions Engineer · Computer Vision · AI Agents & Automation

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/muhammad-rizwan-ai)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail)](mailto:rizwan.ai.engineer@gmail.com)
[![Calendly](https://img.shields.io/badge/Book_a_Call-Calendly-006BFF?style=for-the-badge)](https://calendly.com/rizwan44007)
[![Dev.to](https://img.shields.io/badge/Dev.to-Articles-0A0A0A?style=for-the-badge&logo=devdotto)](https://dev.to/muhammad_rizwan_ce847d2a2)

📍 Lahore, Pakistan

</div>

---

## 🚀 About Me

I build AI systems that work in production — not just in notebooks.

I am an **AI Solutions Engineer at Vaival Technologies**, where I build Shopify and Wix apps and agentic AI tools. Before that, I worked on LLM and RAG systems at Axix Technology. I am also a co-author of a peer-reviewed journal paper on fruit quality inspection with YOLOv11 and U-Net.

**10+ AI systems built and deployed to production.**

- 🤖 **AI Automation & Agents** — n8n agentic workflows, RAG pipelines, LLM apps, MCP integrations
- 👁️ **Computer Vision** — YOLO v5–v11, DINOv3 embeddings, OCR, U-Net segmentation, deployment
- 🧠 **ML Engineering** — end-to-end pipelines, model training, experiment tracking, cloud deploy
- 🛒 **E-commerce Apps** — Shopify & Wix embedded apps with Node.js, TypeScript, and React

---

## 💼 Experience

| Role | Company | Period |
|------|---------|--------|
| AI Solutions Engineer | Vaival Technologies, Lahore | Jul 2026 – Present |
| AI / ML Engineer | Axix Technology (Pvt) Ltd, Lahore | Dec 2025 – Mar 2026 |
| Machine Learning Intern | Ezitech Software House, Rawalpindi | Jul 2024 – Sep 2024 |

---

## 📄 Research & Education

- 📑 **Publication** — *"Comparative Evaluation of YOLOv11 and U-Net for Automated Fruit Detection, Quality Classification, and Defect Segmentation"*
  *Notulae Botanicae Horti Agrobotanici Cluj-Napoca*, Vol. 54, Issue 3, Article no. 15337 — published 11 September 2026.
  Co-author (3rd of 14). The work grew out of my final-year project.

  [![DOI](https://img.shields.io/badge/DOI-10.15835%2Fnbha54315337-1F6FEB?style=flat-square)](https://doi.org/10.15835/nbha54315337)
  [![Read the Paper](https://img.shields.io/badge/Read-Journal_Article-2E7D32?style=flat-square)](https://www.notulaebotanicae.ro/index.php/nbha/article/view/15337)

- 🎓 **BS Software Engineering** — The Islamia University of Bahawalpur (2021–2025), CGPA 3.77 / 4.00

---

## 🔍 Featured Project — Retail Shelf Intelligence

A multi-stage computer vision system that finds products on crowded retail shelves and identifies the **exact SKU** (flavour × pack size) of each one.

```
Shelf photo → YOLO detection → DINOv3 embeddings → gating → SKU matching → English + Arabic OCR check → decision
```

- Recognises **32 fine-grained SKUs** that often share the same box design and differ only by a flavour word or pack size.
- Embeds each crop with a frozen **DINOv3 ViT-B/16** and matches it against a **4,800-vector** reference bank using cosine similarity.
- Confirms each match by reading the pack text in **English and Arabic** with PaddleOCR. Two image versions (upscaled colour and CLAHE greyscale) must both agree.
- **Abstains** (`UNKNOWN`) when the evidence is unclear — a wrong SKU is worse than no answer.
- Includes dataset tools (label checks, SHA-256 de-duplication, seeded splits), pseudo-labelling scripts that grow the dataset, and a **Streamlit** review app with a human accept/reject loop.

**Tech:** Python · PyTorch · Ultralytics YOLO · DINOv3 (Hugging Face Transformers) · PaddleOCR · OpenCV · Streamlit

---

## ⚡ Production Projects

| Project | Tech | Result |
|---------|------|--------|
| AI Sales Agent | n8n + GPT-4 + Apify | 30hrs → 25min/week |
| RAG Knowledge Chatbot | LangChain + Supabase + FastAPI | 200+ queries/day |
| Fruit Quality Inspection (research) | YOLOv8 / YOLOv11 + U-Net + Hugging Face | 94% accuracy · published |
| Medical Pills Detection | YOLOv11 + FastAPI | 91% precision |
| Stroke Prediction | Scikit-learn + XGBoost + LightGBM + MLflow | 89% accuracy · 0.85 F1 |
| HR Automation System | n8n + Google Workspace | Full dept automated |
| SEO AI Agent | GPT-4 + Python | URL → full rewrite |

---

## 🆕 Recent Work (2026)

| Project | What it does | Tech |
|---------|--------------|------|
| **Store Health Scanner** (Shopify app) | Scans themes, products, scripts, metafields, discounts and broken links; scheduled scans, email reports, cart-abandonment analytics | Node.js · Express 5 · TypeScript · MySQL · Shopify GraphQL |
| **Sold Counter** (Shopify app) | "X sold" badge on product pages from real order data, with settings preview and an analytics page | Remix · React · Prisma · Theme App Extension · App Proxy |
| **All Carts** (Wix app) | Abandoned-cart dashboard with real-time webhook tracking and an email capture popup | Node.js · Express · React (Vite) · MySQL · JWT (RS256) |
| **HisaabPro** (ERP for SMEs) | Accounting and inventory system — sales, purchases, invoices, ledgers, reports; moved from desktop to web | Supabase · Vercel (earlier: Electron + SQLite) |
| **Shopify Scraper Agent** | Automated store-data collection that runs on a daily schedule | Playwright · Node.js · cron |
| **Announcement Bar** (Wix app) | Site-wide announcement and shipping bar | Wix CLI · Embedded Script |

> Some source code is private. I am happy to show demos and walk through the architecture in a call.

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv,sklearn,fastapi,docker,ts,nodejs,react,mysql,supabase,vercel,git" />
</p>

```python
ai_and_agents   = ["LLMs (OpenAI API, Claude API)", "LangChain", "LlamaIndex",
                   "RAG", "ChromaDB", "FAISS", "n8n", "MCP"]

computer_vision = ["YOLO v5-v11", "U-Net", "DINOv3 (ViT)", "PaddleOCR",
                   "OpenCV", "PyTorch", "Hugging Face Transformers",
                   "TensorFlow", "Detectron2", "MediaPipe"]

ml_engineering  = ["Scikit-learn", "XGBoost", "LightGBM", "MLflow"]

backend_and_web = ["FastAPI", "Flask", "Streamlit", "Node.js", "Express",
                   "React", "Remix", "Prisma", "Electron"]

ecommerce       = ["Shopify Admin GraphQL API", "Theme App Extensions",
                   "App Proxy", "Wix CLI", "Webhooks"]

data_and_cloud  = ["MySQL", "SQLite", "Supabase", "Firebase", "Docker",
                   "AWS", "Vercel", "Hugging Face"]

automation      = ["Playwright", "cron jobs", "Google Workspace APIs"]

languages       = ["Python", "TypeScript", "JavaScript", "SQL", "Dart/Flutter"]
```

---

## 🧩 How I Work

- I use **Claude Code** for most of my development work, with a documentation-driven workflow: structured project docs, reusable prompts, and handoff files that keep context between sessions.
- I connect my tools through **MCP servers** — Jira, Notion, Supabase, Shopify, and Wix.
- I write my own **custom Claude Code skills** for repeat tasks such as reviews and problem-solving.
- I test for security, not only features — including cross-store (multi-tenant) access checks on Shopify apps.

---

## 📊 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=muhammadrizwan11&show_icons=true&theme=radical&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://streak-stats.demolab.com/?user=muhammadrizwan11&theme=radical"/>
</div>

---

## 📝 Latest Articles

<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

▶ [How I Automated 30 Hours of Manual Sales Work Into 25 Minutes Using n8n and GPT-4](https://dev.to/muhammad_rizwan_ce847d2a2/how-i-automated-30-hours-of-manual-sales-work-into-25-minutes-using-n8n-and-gpt-4-52a2)

---

## 🤝 Let's Work Together

- 💼 **Currently:** AI Solutions Engineer at Vaival Technologies, Lahore
- 💰 **Freelance:** AI Automation, AI Agents, Computer Vision, and Shopify/Wix app projects
- 🔬 **Research:** Open to collaboration in computer vision and applied AI
- 📅 **Book a call:** [calendly.com/rizwan44007](https://calendly.com/rizwan44007)
- 📧 **Email:** rizwan.ai.engineer@gmail.com

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=muhammadrizwan11&color=blueviolet&style=for-the-badge" />
</div>
