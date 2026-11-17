<h1 align="center">Hey, I'm Prisha 👋</h1>
<p align="center"><b>Software Engineering @ University of Waterloo</b><br/>I build fullstack products that fight fraud and build trust, from phishing detection to on-chain identity, and ship AI into them.</p>

<p align="center">
  <a href="https://linkedin.com/in/prisha-lala"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:prisha.lala@uwaterloo.ca"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/></a>
</p>

---

### ⚡ What I've been up to

- 🏆 **Top 16** in the UW Velocity × Stellar Blockchain Innovation Challenge with **[Kredo](https://github.com/prishalala/kredo)**, a Rust smart contract that makes identity verifiers put real money behind their checks
- 🏢 Built auth, billing and portal features for a fraud-resistant hiring platform at **HuntigoX**
- 🎓 Shipped **SkillShift+**, a Next.js career-pathways SaaS with Stripe payments and AI-driven assessments, at **Intellidu Education**
- 📱 Shipped **2 cross-platform apps** to the Play Store: a Capacitor (iOS + Android) app and a React Native (Expo) app
- 🛡️ Built **Redflag**, a hybrid phishing detector (**16+ heuristics** + a Groq LLM layer), because fraud prevention keeps pulling me in
- 🤖 Side projects: an AI resume analyser and a RAG chatbot, both powered by the Anthropic API

---

### 🚀 Projects I'm proud of

**[Kredo: Reusable, Bonded Identity on Stellar](https://github.com/prishalala/kredo)** · [Live app](https://kredo-stellar.vercel.app) · 🏆 Top 16, UW Velocity × Stellar Challenge
Banks re-verify the same person from scratch, which shuts out newcomers and refugees. With Kredo, an organization verifies someone once and **locks a 100 XLM bond** behind it in a **Soroban smart contract (Rust)** on Stellar Testnet. Any bank checks it in seconds for **under a cent**. A **2-of-3 dispute panel** decides between 3 outcomes, and negligent verifiers get **50% of their bond slashed** automatically. Duplicate IDs are blocked with **HMAC-SHA256 keyed hashes**, so **0 personal documents** go on-chain. **28 unit tests**, a **10-step end-to-end flow** verified on testnet, and a React/TypeScript frontend with the Stellar SDK and Freighter.

**[Redflag: Hybrid Phishing Detector](https://github.com/prishalala/redflag-phishing-checker)**
Paste a URL, email or SMS and get a typed JSON verdict: a **0–100 score** across **4 risk levels**, not just safe/unsafe. **16+ weighted heuristics** (lookalike domains, **17-brand** impersonation checks, urgency patterns, shorteners, IP hosts, redirect chains, RDAP domain age) run server-side, with an LLM layer on Groq on top. The `POST /api/analyze` endpoint uses Zod validation and parallel async lookups with timeouts and fallbacks, and drops to heuristics-only mode when no LLM key is set. Next.js + TypeScript.

**[AI Resume Analyser](https://github.com/prishalala/resume-analyser)**
Upload a resume and get a scored breakdown (ATS fit, skills, grammar, keywords) in **under 10 seconds**. Flask API on the backend, the Anthropic API doing the reading.

**[RAG Chatbot](https://github.com/prishalala/rag-chatbot)**
A chatbot that only talks about *your* documents. Feed it PDFs or URLs; it chunks and embeds them, then retrieves the right context before Claude answers, so answers stay grounded in your sources.

---

### 🧰 Tech I work with

**Languages**
<p>
  <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
</p>

**Frontend & Mobile**
<p>
  <img src="https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
  <img src="https://img.shields.io/badge/-React%20Native-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/-Expo-000020?style=flat-square&logo=expo&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/>
</p>

**Backend, Data & Payments**
<p>
  <img src="https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white"/>
</p>

**Blockchain**
<p>
  <img src="https://img.shields.io/badge/-Stellar-7D00FF?style=flat-square&logo=stellar&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Soroban%20Smart%20Contracts-000000?style=flat-square"/>
  <img src="https://img.shields.io/badge/-Freighter%20Wallet-391F75?style=flat-square"/>
</p>

**AI, Security & Tooling**
<p>
  <img src="https://img.shields.io/badge/-Anthropic%20API-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/-RAG%20%26%20Embeddings-6E40C9?style=flat-square"/>
  <img src="https://img.shields.io/badge/-Groq-F55036?style=flat-square"/>
  <img src="https://img.shields.io/badge/-Zod-3E67B1?style=flat-square&logo=zod&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Phishing%20Detection-C0392B?style=flat-square"/>
  <img src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Google%20Play%20Console-414141?style=flat-square&logo=googleplay&logoColor=white"/>
</p>

---

### 📫 Reach me

[LinkedIn](https://linkedin.com/in/prisha-lala) · prisha.lala@uwaterloo.ca
