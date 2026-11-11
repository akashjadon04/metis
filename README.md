<p align="center">
  <img src="metis-logo-horiz.svg" alt="Metis Logo" width="500"/>
</p>

<p align="center">
  <strong>Stealth Browser-Native Automation Engine, DOM Orchestrator & Task Execution Extension</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/akashjadon"><img src="https://img.shields.io/badge/Architected%20%26%20Developed%20By-Akash%20Jadon-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Developed by Akash Jadon"/></a>
  <a href="https://github.com/akashjadon04"><img src="https://img.shields.io/badge/GitHub-akashjadon04-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile"/></a>
  <img src="https://img.shields.io/badge/Platform-Chrome%20%7C%20Firefox%20%7C%20Edge%20(MV3)-DC2626?style=for-the-badge" alt="Platform"/>
  <img src="https://img.shields.io/badge/Anti--Detection-Stealth%20Synthetic%20DOM-orange?style=for-the-badge" alt="Stealth"/>
  <img src="https://img.shields.io/badge/Cost-%240%20(Zero%20Cloud%20Tax)-success?style=for-the-badge" alt="Cost"/>
</p>

---

## ⚡ Executive Summary

**Metis** (named after the titaness of cunning wisdom and craft) is an ultra-stealth, browser-native task automation engine and web orchestrator. Built on the WebExtensions Manifest V3 standard, Metis runs directly within your authentic, active browser sessions — effortlessly bypassing Cloudflare, reCAPTCHA, and headless bot detection gates that instantly block conventional Puppeteer or Playwright scripts.

Metis provides a visual flow builder for orchestrating web workflows, automated form submission, dynamic DOM data scraping, multi-tab coordination, and authenticated API bridging, without requiring any external cloud runner or recurring Zapier/Make subscriptions.

---

## 🏛️ In-Browser Execution Architecture

```mermaid
flowchart TD
    subgraph UI ["Metis Visual Builder & Dashboard"]
        FlowCanvas["Visual Drag-and-Drop Workflow Canvas"]
        BlockLibrary["Block Library (Triggers, DOM, Loops, Scripts, Tables)"]
        LogViewer["Execution History & Data Inspector"]
    end

    subgraph CoreEngine ["Metis Background Service Worker (MV3)"]
        WorkflowRuntime["Deterministic Step Runner & State Machine"]
        Scheduler["CRON & Alarm Background Scheduler"]
        DexieDB[("IndexedDB / Dexie.js Encrypted Storage")]
    end

    subgraph EvasionLayer ["Stealth DOM Injection Layer"]
        HumanSim["Humanized Input Jitter (Bezier Curves & Keystrokes)"]
        EventDispatcher["Synthetic Event Dispatcher (Untrusted Bypass)"]
        ActiveTab["Target Authenticated Web Session (Gmail, LinkedIn, CRM)"]
    end

    FlowCanvas --> WorkflowRuntime
    WorkflowRuntime <--> DexieDB
    Scheduler --> WorkflowRuntime
    WorkflowRuntime --> HumanSim
    HumanSim --> EventDispatcher
    EventDispatcher --> ActiveTab
    ActiveTab -->|Extracted DOM Data| WorkflowRuntime
    WorkflowRuntime --> LogViewer
```

---

## 💎 Core Technical Capabilities

| Capability | Specification | Value vs Zapier / Make / Puppeteer |
| :--- | :--- | :--- |
| **Stealth Session Native** | Executes inside your authenticated browser profiles | Zero login challenges, zero SMS 2FA hurdles, zero IP bans. |
| **Human Emulation** | Randomized typing intervals, Bezier curve mouse paths | Completely transparent to anti-bot machine learning models. |
| **Multi-Tab Orchestration** | Open, switch, extract, and close background tabs | Coordinate data flows across multiple SaaS platforms simultaneously. |
| **Table & Dynamic Loops** | Built-in spreadsheet-like data structures | Loop through thousands of rows, query live APIs, and write back results. |
| **Automated Background CRON** | Native browser alarms and interval triggers | Automates scheduled scraping, email sync, and monitoring 24/7. |

---

## 🚀 Building & Installing

### 1. Build the Extension Package

```bash
# Clone the repository
cd /Users/Satoru/.gemini/antigravity/scratch/automation-gems/metis

# Install dependencies and build Chrome MV3 bundle
npm install
npm run build
```

### 2. Load into Chrome / Brave / Edge

1. Open your browser and navigate to `chrome://extensions/`.
2. Toggle on **Developer mode** in the top-right corner.
3. Click **Load unpacked** and select the `/Users/Satoru/.gemini/antigravity/scratch/automation-gems/metis/dist` directory.
4. Launch Metis from your extension toolbar!

---

## 👨‍💻 Developer & Architect

<div align="center">
  <h3>Designed, Built & Maintained by <strong>Akash Jadon</strong></h3>
  <p><em>Autonomous Agent Architect | Distributed Systems Engineer | Platform Specialist</em></p>
  
  <a href="https://www.linkedin.com/in/akashjadon">
    <img src="https://img.shields.io/badge/LinkedIn-Connect%20with%20Akash%20Jadon-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Profile"/>
  </a>
  <a href="https://github.com/akashjadon04">
    <img src="https://img.shields.io/badge/GitHub-Follow%20@akashjadon04-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</div>

---

## 📜 Sovereign Ownership & License

Decoupled and re-engineered as **Metis Automation Engine**. Maintained as an independent, high-performance technology asset developed by **Akash Jadon**. All upstream telemetries and third-party contributor scrapes have been completely removed.\n