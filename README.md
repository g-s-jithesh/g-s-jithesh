<div align="center">

<!-- CUSTOM ANIMATED HERO BANNER -->
<img src="./assets/banner.svg" alt="Gopalan Srinivasan Jithesh — AI & Systems Engineer" width="100%" />

<br />

<!-- DYNAMIC TYPING SUBTITLE -->
<a href="https://github.com/g-s-jithesh">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3200&pause=900&color=38BDF8&center=true&vCenter=true&width=850&lines=Shipping+End-to-End+Desktop+Apps+%26+Release+Pipelines+%F0%9F%9A%80;Building+Autonomous+MCP+Agents+%26+Multimodal+AI+Systems+%F0%9F%A7%A0;Open-Source+Contributor+to+the+Official+MCP+Python+SDK+%E2%9A%A1;177%2B+Commits+%26+43%2B+Merged+PRs+Across+22+Repositories+in+2026+%F0%9F%94%A5" alt="Typing SVG" />
</a>

<br />

<!-- SOCIAL & CONTACT PILLS -->
<p align="center">
  <a href="https://www.linkedin.com/in/jithesh-g-s-702689355/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-G_S_Jithesh-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:gsjithesh2006@gmail.com">
    <img src="https://img.shields.io/badge/Email-gsjithesh2006%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/g-s-jithesh/blendex/releases" target="_blank">
    <img src="https://img.shields.io/badge/Flagship_App-Blendex_3D-38BDF8?style=for-the-badge&logo=blender&logoColor=white" alt="Blendex" />
  </a>
  <a href="https://github.com/modelcontextprotocol/python-sdk/pull/3725" target="_blank">
    <img src="https://img.shields.io/badge/MCP_Python_SDK-PR_%233725_Merged-A855F7?style=for-the-badge&logo=python&logoColor=white" alt="MCP PR #3725" />
  </a>
</p>

</div>

---

### ⚡ Engineering Telemetry & Profile Spec

<div align="center">
  <img src="./assets/telemetry.svg" alt="Engineering Telemetry & Architecture Split" width="100%" />
</div>

---

### 🚀 Flagship Systems & Production Shipments

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">🎨 <a href="https://github.com/g-s-jithesh/blendex">Blendex</a> — Local 3D Asset Manager</h3>
      <p>
        <img src="https://img.shields.io/github/v/release/g-s-jithesh/blendex?style=flat-square&color=38bdf8&label=Release" />
        <img src="https://img.shields.io/github/actions/workflow/status/g-s-jithesh/blendex/ci.yml?style=flat-square&label=Win%20%26%20Linux%20CI" />
        <img src="https://img.shields.io/badge/PRs-25_Merged-a855f7?style=flat-square" />
      </p>
      <p><b>Zero-cloud desktop 3D asset manager for Windows & Linux</b> that indexes <code>.blend</code>, <code>.fbx</code>, <code>.obj</code>, <code>.ma/.mb</code>, <code>.glb</code>, and <code>.usd</code> libraries with instant thumbnails and <b>hover-to-orbit Three.js 3D previews</b>.</p>
      <ul>
        <li><b>One-Click Bridge Plug-ins:</b> Drag-and-drop or import directly into an active <b>Blender</b> or <b>Maya</b> session.</li>
        <li><b>Production Engineering:</b> Shipped <b>6 releases</b> across 25 merged PRs with automated Windows installer (<code>Setup.exe</code>) pipelines, paged large-library loading, and untrusted scene guards.</li>
      </ul>
      <p><code>Python</code> <code>TypeScript</code> <code>Three.js</code> <code>GitHub Actions</code></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">🎙️ <a href="https://github.com/g-s-jithesh/encore">Encore</a> — Voice Study Coach for Alexa+</h3>
      <p>
        <img src="https://img.shields.io/badge/Amazon_Hackathon-Alexa%2B_Track-FF9900?style=flat-square&logo=amazon&logoColor=white" />
        <img src="https://img.shields.io/badge/Protocol-MCP_Server-38bdf8?style=flat-square" />
        <img src="https://img.shields.io/badge/Tests-Playwright_E2E-10b981?style=flat-square" />
      </p>
      <p><b>MCP-powered voice study coach</b> that transforms raw notes, PDFs, and lecture transcripts into LLM-generated flashcards and quizzes you by voice on a persistent <b>spaced-repetition schedule</b>.</p>
      <ul>
        <li><b>Resilient Agent Loop:</b> Engineered the MCP-client agent loop supporting <b>Google Gemini</b> & <b>Amazon Bedrock</b> with automatic self-healing retry logic for malformed model outputs.</li>
        <li><b>Full Test Pyramid:</b> Backed by unit, integration, and automated <b>Playwright</b> end-to-end tests in CI.</li>
      </ul>
      <p><code>Python</code> <code>Model Context Protocol</code> <code>Gemini</code> <code>Bedrock</code> <code>Playwright</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">👁️ <a href="https://github.com/g-s-jithesh/omni-sight">Omni-Sight</a> — Real-Time Desktop AI Copilot</h3>
      <p>
        <img src="https://img.shields.io/badge/Architecture-Zero--Freeze_CV-10b981?style=flat-square" />
        <img src="https://img.shields.io/badge/UI-PyQt6_HUD_Overlay-38bdf8?style=flat-square" />
      </p>
      <p><b>Autonomous desktop vision copilot</b> that detects meaningful structural shifts on screen (terminal tracebacks, live telemetry, UI states) without manual screenshots.</p>
      <ul>
        <li><b>10 FPS Producer-Consumer Pipeline:</b> Uses asynchronous <code>mss</code> frame capture + OpenCV grayscale frame-diffing (<code>absdiff</code>) for zero CPU/GPU stutter.</li>
        <li><b>Rate-Limit Aware Debouncer:</b> Dynamically throttles multimodal <b>Gemini Flash</b> calls and renders contextual insights onto a transparent, click-through <b>PyQt6 HUD</b>.</li>
      </ul>
      <p><code>Python</code> <code>OpenCV</code> <code>PyQt6</code> <code>Gemini Vision</code></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">⚡ <a href="https://github.com/g-s-jithesh/Amazing-Coders">Project Kilowatt</a> — EV Fleet Intelligence</h3>
      <p>
        <img src="https://img.shields.io/badge/Motorq_Hackathon-CVI_Track-6366f1?style=flat-square" />
        <img src="https://img.shields.io/badge/Scale-100K_Vehicle_Sim-38bdf8?style=flat-square" />
      </p>
      <p><b>End-to-end EV fleet battery health & intelligent charging dispatch platform</b> engineered for the Motorq Connected Vehicle Intelligence Hackathon.</p>
      <ul>
        <li><b>High-Throughput Telemetry:</b> Simulates 100K vehicles across 3 OEM schemas with real-time fault injection, DTC decoding, and battery safety alerts.</li>
        <li><b>ML & Optimization:</b> Combines State-of-Health (SoH) & 7-day fault risk ML models with a health-aware depot charging optimizer.</li>
      </ul>
      <p><code>Go</code> <code>Python</code> <code>Docker</code> <code>ScyllaDB</code> <code>Machine Learning</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">✍️ <a href="https://github.com/g-s-jithesh/manage-linkedin">Manage LinkedIn</a> — AI Post Studio</h3>
      <p>
        <img src="https://img.shields.io/badge/Desktop-Electron_Installer-a855f7?style=flat-square" />
        <img src="https://img.shields.io/badge/Inference-Groq_LPU-f97316?style=flat-square" />
      </p>
      <p><b>Full-stack & desktop LinkedIn publishing suite</b> with OAuth 2.0 integration that drafts posts via LLM, remixes existing posts from URLs, and publishes directly with multi-image/video attachments.</p>
      <ul>
        <li>Includes <b>3 humanizer modes</b>, API rate limiting, and a standalone Windows desktop installer wrapping the Next.js server in <b>Electron</b>.</li>
      </ul>
      <p><code>Next.js</code> <code>TypeScript</code> <code>Electron</code> <code>Tailwind CSS</code> <code>Groq</code></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">🛡️ <a href="https://github.com/g-s-jithesh/guidewire-hackathon">Kavach AI</a> & <a href="https://github.com/g-s-jithesh/Blockchain-Enabled-Federated-AI-Framework">Federated AI</a></h3>
      <p>
        <img src="https://img.shields.io/badge/Guidewire-DevTrails_2026-38bdf8?style=flat-square" />
        <img src="https://img.shields.io/badge/Security-DP--SGD_%2B_Web3-10b981?style=flat-square" />
      </p>
      <p><b>Applied AI for Social & Enterprise Resilience:</b></p>
      <ul>
        <li><b>Kavach AI:</b> Zero-touch parametric income protection for gig workers triggered by 6 live environmental signals (Wet-Bulb Heat Stress Index, rainfall, AQI, outages) + GPS fraud verification.</li>
        <li><b>Federated Threat Intelligence:</b> Privacy-preserving intrusion detection across Hospital/Bank/IoT silos using <b>DP-SGD</b> and permissioned smart contracts on CICIDS2017.</li>
      </ul>
      <p><code>FastAPI</code> <code>PyTorch</code> <code>Differential Privacy</code> <code>Smart Contracts</code></p>
    </td>
  </tr>
</table>

---

### 🧩 Open Source & Upstream Contributions

> **[`modelcontextprotocol/python-sdk` — Issue & Fix #3725](https://github.com/modelcontextprotocol/python-sdk)**  
> Diagnosed and reported a subtle serialization bug in the official **Model Context Protocol (MCP) Python SDK** where bare `dict`, `list`, and `tuple` return annotations silently dropped structured tool output—fixed upstream in the official SDK.

- **G-SQL (Natural Language to SQL Engine):** Architected a schema-aware NL-to-SQL pipeline translating plain-English queries into complex relational joins via semantic tagging, schema linking, and graph-based join inference (`Python`, `FastAPI`, `React`).
- **Awards & Honors:** 🏆 **3rd Place — Bug Busters '26** (CINTEL, SRM Institute of Science and Technology).

---

### 🛠️ Technical Arsenal

<div align="center">

| Layer | Technologies & Tools |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![SQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) |
| **AI, Agents & CV** | ![MCP](https://img.shields.io/badge/Model_Context_Protocol-000000?style=flat-square&logo=anthropic&logoColor=white) ![Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![AWS Bedrock](https://img.shields.io/badge/Amazon_Bedrock-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) |
| **Frontend, Desktop & 3D** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white) ![Qt](https://img.shields.io/badge/PyQt6-41CD52?style=flat-square&logo=qt&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) |
| **Backend & DevOps** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) |

</div>

---

### 📊 GitHub Analytics & Contribution Velocity

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=g-s-jithesh&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0a0e17&title_color=38bdf8&icon_color=a855f7&text_color=c9d1d9&include_all_commits=true&count_private=true" alt="GitHub Stats" />
  <img height="165" src="https://streak-stats.demolab.com?user=g-s-jithesh&theme=tokyonight&hide_border=true&background=0A0E17&ring=38BDF8&fire=A855F7&currStreakLabel=38BDF8" alt="GitHub Streak" />
</div>

<div align="center">
  <img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=g-s-jithesh&bg_color=0a0e17&color=9ca3af&line=38bdf8&point=a855f7&area=true&hide_border=true&custom_title=2026%20Contribution%20%26%20Release%20Velocity" alt="Contribution Graph" />
</div>

<!-- Animated Contribution Snake (Auto-generated via GitHub Actions on the output branch) -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/g-s-jithesh/g-s-jithesh/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/g-s-jithesh/g-s-jithesh/output/github-contribution-grid-snake.svg" />
    <img alt="github-snake" src="https://raw.githubusercontent.com/g-s-jithesh/g-s-jithesh/output/github-contribution-grid-snake-dark.svg" width="100%" />
  </picture>
</div>

---

<div align="center">
  <sub>⚡ Crafted with custom SVG telemetry & automated workflows by <b>Gopalan Srinivasan Jithesh</b> · <a href="mailto:gsjithesh2006@gmail.com">Let's build something impactful →</a></sub>
</div>
