<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:808000,50:6B8E23,100:333D1A&height=220&section=header&text=Sara%20Manzoor&fontSize=55&fontAlignY=35&desc=AI-Powered%20Full%20Stack%20Developer%20%7C%20ML%20Engineer&descAlignY=55&animation=fadeIn&fontColor=F5F1E3" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=20&pause=1000&color=8A9A5B&center=true&width=800&lines=AI-Powered+Full+Stack+Developer;Machine+Learning+Engineer;Building+Real-World+AI+Systems;Python+%7C+TensorFlow+%7C+React+%7C+Next.js" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Sara12-2&label=Profile+Views&color=6B8E23&style=flat-square" />
  <img src="https://img.shields.io/github/followers/Sara12-2?label=Followers&style=flat-square&logo=github&color=6B8E23" />
  <img src="https://img.shields.io/github/stars/Sara12-2?label=Stars&style=flat-square&logo=github&color=808000" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sara-manzoor-3a8a56365"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:saramanzoor76@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://www.kaggle.com/sara765"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white"/></a>
  <a href="https://leetcode.com/u/Sara_34/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black"/></a>
</p>

---

## 👋 About Me

COO at **DevHatch Labs**, building intelligent systems where **AI (ML, NLP, Computer Vision, RAG/LLMs)** meets modern **full stack web development**. I turn real-world problems into working, deployed solutions — not just notebooks.

🔭 **Currently Exploring:** Agentic AI &nbsp;•&nbsp; LLM Fine-Tuning &nbsp;•&nbsp; Production Deployment (Docker/CI-CD)

---

##  Featured Projects — AI / ML

<table>
<tr>
<td width="50%" valign="top">

### 🚑 High-Cost Patient Prediction
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5E28?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-4285F4?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Problem:** Healthcare payers can't identify which members will become high-cost (>$30k/year) until the cost has already happened — too late for proactive care management.

**Solution:** A LightGBM + XGBoost ensemble on 336 engineered features (cost ratios, code diversity, HCC risk scores), with the decision threshold tuned to maximize recall — catching over 82% of true high-cost members before costs occur.

**Result:** Recall 0.825 · F1 0.563 · 🏅 Softtec 2026 ML Competition, FAST NUCES Lahore

[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/High_Cost_Patient_prediction_Softtec_Competition_Project)

</td>
<td width="50%" valign="top">

### 📄 PaperMind AI
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NextJS](https://img.shields.io/badge/Next.js_16-black?style=flat-square&logo=next.js)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_Llama3-F55036?style=flat-square&logo=meta&logoColor=white)

**Problem:** Reading long research papers to find one fact is slow, and asking a general LLM instead risks a confident, hallucinated answer with no way to verify it.

**Solution:** A RAG pipeline — PDF split into page-aware chunks, embedded locally (zero-cost, no API calls), retrieved by cosine similarity, and answered by an LLM instructed to cite the exact page it used.

**Result:** Every answer is grounded in the actual document, with inline `(p. 3)`-style citations

[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/PaperMind-AI)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 📦 StockFlow AI
![NextJS](https://img.shields.io/badge/Next.js-14-black?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black)
![Flask](https://img.shields.io/badge/Flask-3-000000?style=flat-square&logo=flask)
![Redis](https://img.shields.io/badge/Redis-7-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

**Problem:** Small e-commerce teams outgrow spreadsheets for inventory but can't justify the cost or complexity of a full ERP system.

**Solution:** A full-stack SaaS where every number that matters — forecasts, reorder quantities — is computed deterministically; an LLM is used *only* to narrate the trend, never to invent a figure. Real-time Socket.IO alerts, full RBAC.

**Result:** 42 backend tests, CI pipeline, and graceful degradation if Redis/Groq are unavailable

[![Watch Demo](https://img.shields.io/badge/🔗_Watch_Demo-6B8E23?style=for-the-badge)](https://drive.google.com/file/d/1HHUJQYC6oSzfxB-GVjuexE-uqA_HF_8g/view?usp=sharing)
[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/Full-Stack-Inventory-Management-SaaS-with-AI-Forecasting)

</td>
<td width="50%" valign="top">

### 🎓 UoL AI Assistant
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_Llama3-F55036?style=flat-square&logo=meta&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Problem:** Students, applicants, and visitors couldn't get quick, role-relevant answers about University of Layyah — info was scattered across static pages nobody reads in full.

**Solution:** A bilingual (EN/UR) AI assistant grounded in real scraped university data, with role-based responses (student/applicant/visitor) and an offline keyword-matching fallback when the API is unreachable.

**Result:** 🏅 Top 10 out of 23+ teams, South Punjab Generative AI Hackathon 2026

[![Live Demo](https://img.shields.io/badge/🔗_Live_Demo-6B8E23?style=for-the-badge)](https://uo-l-ai-assistant-hackathon-2026.vercel.app/)
[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/UoL-AI-Assistant-Hackathon-2026)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🖐 ASL Sign Language Recognition
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Problem:** Most people can't understand American Sign Language, creating a real communication barrier with no accessible, real-time translation tool at hand.

**Solution:** A CNN trained on class-balanced, augmented ASL image data (with horizontal flip intentionally disabled, since mirroring changes a sign's meaning), served through CLI, image-upload, and live webcam inference.

**Result:** Shared inference code across all three interfaces, unit tests + CI pipeline

[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/ASL_Sign_Language_Recognition)

</td>
<td width="50%" valign="top">

### 🛒 Smart Retail Shelf Monitoring
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-3776AB?style=flat-square&logo=python&logoColor=white)

**Problem:** Manual shelf audits are slow and easy to skip, so stockouts often go unnoticed until a customer complains or a sale is lost.

**Solution:** A real-time YOLOv8 detection pipeline that counts items per frame and triggers color-coded low-stock alerts — architected so the detection model can be swapped for a custom-trained, SKU-specific model with zero code changes.

**Result:** CLI-configurable (video/model/threshold), includes a ready-to-use custom fine-tuning script

[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/Smart_Retail_Shelf_Monitoring_with_YOLOv8)

</td>
</tr>
</table>

---

##  Featured Projects — Full Stack & Web

<table>
<tr>
<td width="50%" valign="top">

### 🎟 EventSphere Pro
![React](https://img.shields.io/badge/React-19-149ECA?style=flat-square&logo=react&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-3-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

**Problem:** Small event organizers need real ticketing infrastructure — booking, seat tracking, revenue — but existing options are either an expensive platform or a form bolted onto a calendar.

**Solution:** A multi-role (attendee/organizer/admin) booking platform with seat-locked bookings that can't overbook, JWT auth with httpOnly + CSRF-protected refresh cookies, and a revenue analytics panel.

**Result:** 11 passing pytest tests, one-command Docker setup (Postgres + Flask + Vite together)

[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/EventSphere-Pro)

</td>
<td width="50%" valign="top">

### ☕ Smart Cafeteria System
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chart.js&logoColor=white)

**Problem:** Campus/office cafeterias running orders manually leads to mistakes and zero visibility into what's actually selling.

**Solution:** A full-stack ordering system with role-based access (admin/customer), bcrypt-hashed auth, a live order-tracking flow, and a revenue analytics dashboard.

**Result:** Coupons, verified reviews, and full cart-to-checkout flow

[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/Smart_Cafeteria_Full_Stack_Website)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🛒 Grocery Store Website
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

**Problem:** Small grocery businesses need an online storefront, but affordable e-commerce options rarely come with real security or delivery logistics built in.

**Solution:** A full-stack platform (42+ products, 12+ tables, 50+ endpoints) with bcrypt hashing, login-attempt lockout, delivery-slot scheduling, and an admin analytics dashboard.

**Result:** ~5,900 lines of code, transaction rollback support, stock validation before every order

[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/Grocery_Store_Website-)

</td>
<td width="50%" valign="top">

### 🌐 Personal Portfolio
![NextJS](https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38BDF8?style=flat-square&logo=tailwindcss&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_Llama3-F55036?style=flat-square&logo=meta&logoColor=white)

**Problem:** Static portfolios make visitors dig through sections to find what they actually want to know about a candidate.

**Solution:** A portfolio with a real AI chat assistant (Groq-powered, grounded in my actual background) that answers any question conversationally and attaches project cards automatically when relevant.

**Result:** Runs as a single Vercel Edge Function — no separate backend to host

[![Live Demo](https://img.shields.io/badge/🔗_Live_Demo-6B8E23?style=for-the-badge)](https://my-personal-portfolio-five-zeta.vercel.app/)
[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/My_Personal_Portfolio)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 💰 AURUM Finance Dashboard
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chart.js&logoColor=white)

**Problem:** Most people avoid tracking personal finances because every tool demands a signup and a subscription just to log an expense.

**Solution:** A zero-backend, browser-based finance dashboard — full transaction CRUD, category budgets with color-coded alerts, and multi-currency support, all persisted locally.

**Result:** CSV/JSON export, print-ready reports, dark/light mode

[![Live Demo](https://img.shields.io/badge/🔗_Live_Demo-6B8E23?style=for-the-badge)](https://expense-tracer-dashboard.vercel.app/)
[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/Expense_Tracer_Dashboard)

</td>
<td width="50%" valign="top">

### 🚀 Apex — Appointment Dashboard
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chart.js&logoColor=white)

**Problem:** Small service businesses (salons, clinics, gyms) need appointment scheduling without paying for a heavyweight SaaS subscription.

**Solution:** A single-file dashboard with a FullCalendar-powered visual schedule, complete appointment CRUD, and dynamic accent-color theming — drop the file anywhere and it runs.

**Result:** Honest in-memory data model, clearly documented rather than disguised as persistent

[![Live Demo](https://img.shields.io/badge/🔗_Live_Demo-6B8E23?style=for-the-badge)](https://appointment-booking-dashboard-ten.vercel.app/)
[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/Appointment_booking_Dashboard)

</td>
</tr>

<tr>
<td colspan="2" valign="top">
<tr>
<td width="50%" valign="top">

### 🛍 TechNest — E-Commerce Store
![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Problem:** Small e-commerce businesses need a modern, engaging storefront to compete with bigger brands, but generic templates look dated and don't convert.

**Solution:** A React + Vite storefront with a glassmorphism UI, real-time search/category filtering, cart + wishlist management, and a persistent dark/light theme.

**Result:** Full checkout flow with order confirmation, cart/wishlist persisted via localStorage

[![Live Demo](https://img.shields.io/badge/🔗_Live_Demo-6B8E23?style=for-the-badge)](https://tech-nest-ecommerce.vercel.app/)
[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/TechNest_Ecommerce_Website)

</td>
<td width="50%" valign="top">

### 🍔 SwiftEats — Food Delivery Landing Page
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Problem:** Restaurant startups need a premium, trustworthy landing page to convert visitors into orders, without the cost of a full custom build.

**Solution:** A fully responsive landing page with live menu filtering, an animated FAQ accordion, cart-add simulation with toast feedback, and scroll-triggered animations via the Intersection Observer API.

**Result:** Sticky nav with active-section highlighting, smooth-scroll navigation throughout

[![Live Demo](https://img.shields.io/badge/🔗_Live_Demo-6B8E23?style=for-the-badge)](https://restaurant-food-delivery-website-la.vercel.app/)
[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/Swifteats_Premium_food_delievery_landing_page)

</td>
</tr>

### 🏰 LuxEstate — Real Estate Landing Page
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38BDF8?style=flat-square&logo=tailwindcss&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chart.js&logoColor=white)

**Problem:** Real estate listings need to convert international buyers, but most landing pages show one currency and give no way to estimate real monthly costs.

**Solution:** An interactive landing page with live search/filter across price, location and type, a real-time mortgage calculator, and a multi-currency switcher (USD/AED/GBP).

**Result:** Full accessibility support (skip links, focus trap, `aria-live` regions), Chart.js market-growth visualization

[![Live Demo](https://img.shields.io/badge/🔗_Live_Demo-6B8E23?style=for-the-badge)](https://luxury-real-estate-landing-page-drk.vercel.app/)
[![GitHub](https://img.shields.io/badge/📁_Source_Code-333D1A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sara12-2/luxury-real-estate-landing-page)

</td>
</tr>
</table>

---

## 🚧 In Progress

- **ResumeMatch AI** — NLP tool scoring resume-to-job-description fit using TF-IDF/embedding similarity + spaCy skill extraction
- **JobScout AI** — an autonomous multi-step agent that searches, scores, and drafts outreach for job/freelance postings

---

## 🛠 Tech Stack

<table width="100%">
  <tr>
    <td align="center" valign="top" width="50%">
      <strong>⚡ Frontend</strong><br/><br/>
      <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,tailwind,bootstrap,vite" />
    </td>
    <td align="center" valign="top" width="50%">
      <strong>🛠️ Backend &amp; Databases</strong><br/><br/>
      <img src="https://skillicons.dev/icons?i=py,flask,mysql,postgres,sqlite,redis" /><br/>
      <img src="https://img.shields.io/badge/-REST_APIs-8B9A6B?style=flat-square"/>
      <img src="https://img.shields.io/badge/-SQLAlchemy-D71F00?style=flat-square"/>
      <img src="https://img.shields.io/badge/-JWT_Auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
      <img src="https://img.shields.io/badge/-bcrypt-8B9A6B?style=flat-square"/>
      <img src="https://img.shields.io/badge/-Socket.IO-010101?style=flat-square&logo=socket.io&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="50%">
      <strong>🤖 AI / Machine Learning</strong><br/><br/>
      <img src="https://skillicons.dev/icons?i=py,tensorflow,sklearn,opencv" /><br/>
      <img src="https://img.shields.io/badge/-Keras-D00000?style=flat-square&logo=keras&logoColor=white"/>
      <img src="https://img.shields.io/badge/-XGBoost-EB5E28?style=flat-square"/>
      <img src="https://img.shields.io/badge/-LightGBM-4285F4?style=flat-square"/>
      <img src="https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
      <img src="https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/-SMOTE-8B9A6B?style=flat-square"/>
      <img src="https://img.shields.io/badge/-NLP-8B9A6B?style=flat-square"/>
      <img src="https://img.shields.io/badge/-spaCy-09A3D5?style=flat-square"/>
      <img src="https://img.shields.io/badge/-Computer_Vision-8B9A6B?style=flat-square"/>
      <img src="https://img.shields.io/badge/-YOLOv8-00BFFF?style=flat-square"/>
      <img src="https://img.shields.io/badge/-Deep_Learning-8B5CF6?style=flat-square"/><br/>
      <img src="https://img.shields.io/badge/-RAG_Systems-8B9A6B?style=flat-square"/>
      <img src="https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square"/>
      <img src="https://img.shields.io/badge/-Groq_API-F55036?style=flat-square"/>
      <img src="https://img.shields.io/badge/-Sentence_Transformers-8B9A6B?style=flat-square"/>
      <img src="https://img.shields.io/badge/-ChromaDB-8B9A6B?style=flat-square"/>
    </td>
    <td align="center" valign="top" width="50%">
      <strong>☁️ DevOps, Testing &amp; Tools</strong><br/><br/>
      <img src="https://skillicons.dev/icons?i=git,github,docker,vercel,netlify,vscode,figma" /><br/>
      <img src="https://img.shields.io/badge/-GitHub_Actions_CI-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
      <img src="https://img.shields.io/badge/-Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white"/>
      <img src="https://img.shields.io/badge/-Nginx-009639?style=flat-square&logo=nginx&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/-Chart.js-FF6384?style=flat-square&logo=chart.js&logoColor=white"/>
      <img src="https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
      <img src="https://img.shields.io/badge/-Jupyter_Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white"/>
      <img src="https://img.shields.io/badge/-Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white"/>
      <img src="https://img.shields.io/badge/-Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white"/>
    </td>
  </tr>
</table>

<p align="center"><i>🌱 Currently learning: Agentic AI (LangGraph) &nbsp;·&nbsp; Hugging Face fine-tuning (LoRA/PEFT)</i></p>

---

## 📊 GitHub Stats

## 📊 GitHub Stats

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=Sara12-2&show_icons=true&theme=transparent&hide_border=true&title_color=BFCC94&icon_color=D4AF37&text_color=F5F1E3&bg_color=1A1F13&rank_icon=github" />
  <img width="49%" src="https://github-readme-streak-stats.demolab.com?user=Sara12-2&theme=transparent&hide_border=true&background=1A1F13&stroke=6B8E23&ring=D4AF37&fire=D4AF37&currStreakNum=F5F1E3&currStreakLabel=BFCC94&sideNums=F5F1E3&sideLabels=BFCC94&dates=8A9A5B" />
</p>

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sara12-2&layout=compact&theme=transparent&hide_border=true&title_color=BFCC94&text_color=F5F1E3&bg_color=1A1F13&langs_count=8" />
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Sara12-2&theme=github_dark" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Sara12-2&bg_color=1A1F13&color=BFCC94&line=808000&point=F5F1E3&area=true&hide_border=true" />
</p>

---

## 📫 Connect

<p align="center">
  <a href="https://github.com/Sara12-2"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/sara-manzoor-3a8a56365"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:saramanzoor76@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:808000,50:6B8E23,100:333D1A&height=100&section=footer" width="100%"/>
</p>
