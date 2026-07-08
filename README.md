# <p align="center"><img src="https://readme-typing-svg.herokuapp.com?font=Outfit&size=32&duration=2000&pause=1000&color=7aa2f7&center=true&vCenter=true&width=900&height=60&lines=%F0%9F%91%8B+Hi%2C+I%27m+Harshal+Jariwala;CTO+%40+Magnyte+Software;Building+High-Performance+SaaS" alt="Typing Banner" /></p>

<p align="center">
  <img src="https://img.shields.io/badge/Role-CTO%20%40%20Magnyte%20Software-bb9af3?style=for-the-badge&logoColor=white" alt="Role Badge" />
  <img src="https://img.shields.io/badge/Location-Surat%2C%20India-7aa2f7?style=for-the-badge&logoColor=white" alt="Location Badge" />
  <img src="https://img.shields.io/badge/Experience-3%2B%20Years-9ece6a?style=for-the-badge&logoColor=white" alt="Experience Badge" />
</p>

<p align="center">
  <a href="https://github.com/Hjgaming">
    <img src="https://komarev.com/ghpvc/?username=Hjgaming&label=PROFILE%20VIEWS&color=2ac3de&style=for-the-badge" alt="Profile Views" />
  </a>
</p>

<p align="center">
  <a href="mailto:harshal@magnytesolution.com"><img src="https://img.shields.io/badge/Email-harshal%40magnytesolution.com-f7768e?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://linkedin.com/in/harshal-jariwala-cto"><img src="https://img.shields.io/badge/LinkedIn-Harshal%20Jariwala-7aa2f7?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://magnytesolution.com"><img src="https://img.shields.io/badge/Portfolio-magnytesolution.com-9ece6a?style=for-the-badge&logo=chrome&logoColor=white" alt="Portfolio" /></a>
</p>

---

## 🚀 About Me

<table width="100%">
  <tr>
    <td width="60%" valign="top">
      <h3>👨‍💻 Professional Philosophy</h3>
      <p>
        As the Chief Technology Officer at Magnyte Software, I specialize in building highly scalable, resilient, and secure systems that bridge the gap between complex engineering challenges and high-value business outcomes. I lead engineering teams, design microservices, and deploy production-grade software architectures from the ground up.
      </p>
      <p>
        I believe in code craftsmanship, rigorous automated verification, and architecting for security-first applications. I am passionate about developer productivity, local server hosting, and low-latency system communications.
      </p>
      <ul>
        <li>🏫 <b>Education:</b> Bachelor of Technology (B.Tech) in Computer Engineering</li>
        <li>💡 <b>Engineering Mindset:</b> Clean architectural abstractions, zero-knowledge safety, and predictable execution.</li>
        <li>🎯 <b>Current Goal:</b> Harnessing system-level integrations and browser/IDE sandbox development workflows.</li>
      </ul>
    </td>
    <td width="40%" valign="top">
      <h3>⚡ Areas of Expertise</h3>
      <ul>
        <li>🛡️ <b>Secure Folder Systems:</b> Zero-knowledge AES-256 encryption, local Wi-Fi bounds.</li>
        <li>🔌 <b>Local Server Engines:</b> Running sandboxed Node.js runtimes natively inside Android.</li>
        <li>🖥️ <b>VPS Management:</b> Client-side SSH/SFTP and PTY terminals with no gateway servers.</li>
        <li>🌐 <b>Networking & Multi-WAN:</b> Windows Filtering Platform rules and packet steering.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🏆 Competitive Programming & Achievements

<p align="left">
  <a href="https://leetcode.com/u/hjgaming/"><img src="https://img.shields.io/badge/LeetCode-hjgaming-FFA116?style=flat-square&logo=leetcode&logoColor=white" alt="LeetCode" /></a>
  <a href="https://www.codechef.com/users/hjgaming"><img src="https://img.shields.io/badge/CodeChef-hjgaming-5B4636?style=flat-square&logo=codechef&logoColor=white" alt="CodeChef" /></a>
  <a href="https://www.geeksforgeeks.org/user/hjgaming/"><img src="https://img.shields.io/badge/GeeksforGeeks-hjgaming-298D46?style=flat-square&logo=geeksforgeeks&logoColor=white" alt="GeeksforGeeks" /></a>
  <a href="https://www.hackerrank.com/profile/hjgaming"><img src="https://img.shields.io/badge/HackerRank-hjgaming-2EC866?style=flat-square&logo=hackerrank&logoColor=white" alt="HackerRank" /></a>
</p>

*   🚀 **B2B SaaS Architecture:** Designed and scaled **MySecureFolder** from scratch, building advanced security controls, licensing systems, and Razorpay transaction networks.
*   🔒 **Enterprise Dev Tooling:** Built **Magnyte Preview** from the ground up, utilizing Cloudflare tunnels to stream secure localhost environments without complex deployments.
*   🔌 **Local Dataplane Steering:** Engineered the **WiFi Balance** multi-WAN platform in Rust, using Windows Filtering Platform hooks to route app-specific traffic.
*   🤖 **Twilio OpenAI Realtime API:** Designed **Ava**, a low-latency voice-driven AI call assistant that handles conversations using real-time Twilio Audio Streams.

---

## 💼 Featured Projects

<details>
<summary><b>🛠️ Project 1: MagnyteForge (GitVexo) — Enterprise SCM & DevOps</b></summary>
<br>

*   **Project Overview**: An enterprise-grade, multi-tenant source code management (SCM) and DevOps platform built to optimize team collaboration and version control operations.
*   **Business Problem Solved**: Offers a fully self-hosted, secure GitHub/GitLab alternative that enforces strict role-based/attribute-based access controls (RBAC + ABAC) and cloud-insulated repository compilation.
*   **Architecture**: Modular API gateway built with Fastify, combined with simple-git for file system repository interaction, Redis for tasks queueing, and Prisma ORM for database connectivity.
*   **Tech Stack**: React 18, Vite, Fastify, TypeScript, Prisma, MySQL 8.4, Redis, BullMQ, simple-git.
*   **Key Features**:
    *   Isomorphic-Git sandboxed repositories.
    *   Granular RBAC + ABAC permissions.
    *   Session cookies, Argon2 hashing, TOTP MFA, and secure API keys.
*   **Scalability Considerations**: Offloaded git sync computations to edge workers; asynchronous background workers handled intensive build payloads.
*   **Security Considerations**: Integrated row-level security structures and cloud-insulated compilation environments.
*   **Engineering Challenges**: Bypassing Git CPU spikes during concurrent requests. Solved by managing pre-warmed repository pools.
*   **Production-Readiness Highlights**: Automated health check dashboards and zero-downtime rolling updates.
</details>

<details>
<summary><b>🛡️ Project 2: MySecureFolder — AES-256 Folder Lock & Zero-Knowledge SaaS</b></summary>
<br>

*   **Project Overview**: An enterprise-grade desktop folder locker and secure synchronization client with dual-layer Wi-Fi bound security and zero-knowledge privacy.
*   **Business Problem Solved**: Protects critical files locally against unauthorized physical access and network intrusion, while providing secure automated backups to the cloud.
*   **Architecture**: Electron-based desktop app running native file system listeners and AES-256-GCM encryption threads, syncing with a Node.js SaaS API.
*   **Tech Stack**: Electron, React, Node.js, Express, MongoDB, AWS S3, Razorpay, WebSockets.
*   **Key Features**:
    *   Zero-knowledge encryption: Files encrypted client-side using user-held keys.
    *   Face Authentication and biometric logins.
    *   Wi-Fi bound local locking: Automatically locks folders if disconnected from authorized office/home Wi-Fi networks.
    *   Razorpay payment gates for SaaS subscriptions.
*   **Scalability Considerations**: Implemented websocket-based real-time notification push to synchronize file statuses between client instances.
*   **Security Considerations**: Dual-layer encryption (AES-256-GCM) with key stretching (PBKDF2) and secure on-device hardware storage.
*   **Engineering Challenges**: Ensuring folder locking was bulletproof against Windows Explorer bypasses. Resolved by registering low-level system watcher hooks.
*   **Production-Readiness Highlights**: Complete test suite spanning FaceAuth, cryptomanager, and Wi-Fi detector modules.
</details>

<details>
<summary><b>🖥️ Project 3: VPS Commander — Client-Side Mobile VPS Orchestrator</b></summary>
<br>

*   **Project Overview**: A client-side, terminal-inspired Android mobile application designed to manage, monitor, and configure VPS servers remotely.
*   **Business Problem Solved**: Eliminates the need for intermediary backend gateways by establishing direct, secure SSH/SFTP tunnels from the mobile client to hoster instances.
*   **Architecture**: A fully client-side architecture with encrypted storage of credentials, running direct socket connections.
*   **Tech Stack**: React Native, Expo, `@dylankenneally/react-native-ssh-sftp`, `expo-secure-store`, JetBrains Mono.
*   **Key Features**:
    *   Encrypted multi-profile VPS store using Android Keystore.
    *   Dynamic Dashboard: Real-time CPU, RAM, disk, load averages, and uptime streaming.
    *   Interactive Terminal: Full PTY shell, exec-fallback, and ANSI color parsing.
    *   SFTP File Manager: Upload, download, edit, and share directory structures.
    *   PM2 Manager: List, restart, stop, and monitor live process logs.
*   **Scalability Considerations**: Client-side execution eliminates the server scaling bottleneck entirely.
*   **Security Considerations**: Credentials encrypted using AES-256 on-device via Android Keystore.
*   **Engineering Challenges**: Maintaining active SSH channels and streaming terminal logs across mobile navigation screens without losing state. Solved using background navigation state-caching.
*   **Production-Readiness Highlights**: Preconfigured EAS build pipelines for immediate APK compilation.
</details>

<details>
<summary><b>📞 Project 4: Ava — Twilio & OpenAI Realtime Phone Voice Agent</b></summary>
<br>

*   **Project Overview**: A responsive AI phone assistant designed to handle voice calls, collect information, and answer customer queries naturally.
*   **Business Problem Solved**: Automates incoming support lines with conversational AI, offering low-latency responses that mimic human operators.
*   **Architecture**: Real-time bi-directional streaming pipeline linking Twilio's Audio Streams to OpenAI's Realtime WebSocket interface.
*   **Tech Stack**: Node.js, WebSockets, Twilio Media Streams, OpenAI Realtime API (GPT-4o-mini-realtime-preview).
*   **Key Features**:
    *   Low-latency bi-directional voice conversation.
    *   Intelligent interruption handling (stops speaking when user interrupts).
    *   Multi-threaded user state tracking and secure data harvesting.
*   **Scalability Considerations**: Scaled websocket event handlers using stateless Node processes.
*   **Security Considerations**: Secured webhook routes using cryptographic signature validation from Twilio.
*   **Engineering Challenges**: Keeping latency below 300ms. Solved by streaming raw audio buffers directly without intermediate disk writes or conversion.
*   **Production-Readiness Highlights**: Custom exception handling for connection dropouts and auto-reconnections.
</details>

<details>
<summary><b>🌍 Project 5: LocalNet Mobile — On-Device Mobile Web Server</b></summary>
<br>

*   **Project Overview**: An Android application that transforms any smartphone into an offline local server capable of hosting full-stack codebases.
*   **Business Problem Solved**: Facilitates developers and teams working in disconnected environments by enabling localized server infrastructure.
*   **Architecture**: Embedded Node.js runtime thread running on-device, interacting with native storage and network interfaces.
*   **Tech Stack**: React Native, Expo, `@comapeo/nodejs-mobile-react-native`, Express, SQLite, Python.
*   **Key Features**:
    *   Run full Node.js or Python Flask backend servers on-device.
    *   Upload ZIP file codebases, extract, and statically host them.
    *   Automated server port isolation and crash auto-restarts.
*   **Scalability Considerations**: Zero server footprint; load is distributed to on-device hardware.
*   **Security Considerations**: Isolated sandbox storage directory on Android to prevent server processes from accessing unauthorized directories.
*   **Engineering Challenges**: Compiling and running standard npm dependencies on an ARM-based Android CPU. Resolved by pre-bundling a node asset directory.
*   **Production-Readiness Highlights**: Lightweight execution optimized to prevent battery drain.
</details>

<details>
<summary><b>🦀 Project 6: WiFi Balance — Desktop Multi-WAN Routing Controller</b></summary>
<br>

*   **Project Overview**: A fully local desktop application designed to orchestrate and balance network traffic across multiple internet connections.
*   **Business Problem Solved**: Combines multiple Wi-Fi, Ethernet, and mobile hotspot connections to increase bandwidth and provide automatic failover.
*   **Architecture**: Master-agent architecture where a local Rust daemon executes system routing changes, communicating with an Electron interface via IPC Named Pipes.
*   **Tech Stack**: Electron, React, Rust (`network-engine`), Windows WFP (Windows Filtering Platform), WinDivert.
*   **Key Features**:
    *   Per-process routing using Windows Filtering Platform policies.
    *   Experimental packet steering with WinDivert capture and reinjection.
    *   Local configuration storage (no external server dependency).
*   **Scalability Considerations**: Native Rust background daemon ensures negligible CPU and RAM overhead.
*   **Security Considerations**: Requires administrative privileges; IPC communication is restricted to local Named Pipes.
*   **Engineering Challenges**: Bypassing Windows routing table limitations to route individual apps through specific adapters. Resolved using low-level WFP connection policies (`FwpmConnectionPolicyAdd0`).
*   **Production-Readiness Highlights**: Fully packaged MSI and EXE installers with automatic daemon lifecycles.
</details>

<details>
<summary><b>📋 Project 7: Svayam CMS — Command Center Complaint Portal</b></summary>
<br>

*   **Project Overview**: An enterprise Complaint Management System (CMS) backend and frontend designed for municipal Integrated Command and Control Centers (ICCC).
*   **Business Problem Solved**: Modernized a legacy Django administration portal into a lightweight, high-performance Node.js service without altering existing API routes or schemas.
*   **Architecture**: Node.js/Express service utilizing raw MySQL connection pools to maximize query speeds and match legacy database schemas.
*   **Tech Stack**: Express.js, React (Vite), mysql2/promise, JWT, Multer, Nodemailer.
*   **Key Features**:
    *   Live complaint tracking and technician assignment logs.
    *   Custom JWT session middleware with in-memory OTP verification.
    *   Raw SQL query architecture for high database throughput.
*   **Scalability Considerations**: Replaced Django's ORM overhead with raw, indexed MySQL queries, achieving a 5x increase in response times.
*   **Security Considerations**: Clean middleware authorization layers restricting access based on user role rankings.
*   **Engineering Challenges**: Replicating Django's custom cryptographic password hashing and schema structures. Solved by implementing compatible pbkdf2 and bcrypt wrappers.
*   **Production-Readiness Highlights**: Thoroughly unit-tested to ensure API parity with the legacy Django service.
</details>

<details>
<summary><b>🎱 Project 8: 8-Ball Multiplayer Pool — Real-time Web Game</b></summary>
<br>

*   **Project Overview**: A web-based multiplayer 8-ball pool game with interactive 2D physics and real-time multiplayer lobbies.
*   **Business Problem Solved**: Demonstrates real-time state synchronization and client-side physics simulation.
*   **Architecture**: Server-side room manager routing gameplay events to Matter.js physical engines, synchronized via WebSockets.
*   **Tech Stack**: React 19, Vite, Matter.js (2D Physics), Socket.io.
*   **Key Features**:
    *   Dynamic rigid-body physics for pool ball collisions, friction, and table bounces.
    *   Multi-user lobbies with matchmaking.
    *   Low-latency state synchronization.
*   **Scalability Considerations**: Game state calculations minimized to run on the client, with validation checks on the server to prevent cheating.
*   **Security Considerations**: Server-controlled authorization keys for room access.
*   **Engineering Challenges**: Eliminating visual lag and stuttering in ball movements due to websocket latency. Solved by implementing client-side interpolation and physics extrapolation.
*   **Production-Readiness Highlights**: Smooth 60fps canvas render loop.
</details>

<details>
<summary><b>💎 Project 9: G9 Jewellery — Custom E-Commerce Suite</b></summary>
<br>

*   **Project Overview**: A specialized, high-traffic e-commerce storefront and admin control panel designed for custom jewelry retail.
*   **Business Problem Solved**: Automates inventory listings, image uploads, price conversions, and client payments for high-value jewelry.
*   **Architecture**: Multi-tier architecture splitting administrative portals, customer storefronts, and payment webhooks.
*   **Tech Stack**: Node.js, Express, Knex, PostgreSQL/MySQL, AWS S3, Razorpay, Twilio, Puppeteer.
*   **Key Features**:
    *   Automatic currency conversions and real-time pricing estimators.
    *   Integrated S3 image upload and resizing pipelines.
    *   Razorpay checkout flows with order tracking SMS notifications.
*   **Scalability Considerations**: Implemented database pooling and query index optimization to handle high traffic spikes.
*   **Security Considerations**: Strict JWT authentication, session handling, and Razorpay webhook signature verification to prevent transaction spoofing.
*   **Engineering Challenges**: Generating high-fidelity invoice PDFs dynamically. Solved by using headless Puppeteer to print styled HTML pages.
*   **Production-Readiness Highlights**: Integrated Swagger-UI documentation and automated transaction logs.
</details>

---

## ⚡ Engineering Stack

<table>
  <tr>
    <td valign="top" width="50%">
      <h4>💻 Programming Languages</h4>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
      <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
      <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart" />
      <img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift" />
      <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
    </td>
    <td valign="top" width="50%">
      <h4>🎨 Frontend Development</h4>
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
      <img src="https://img.shields.io/badge/React%20Native-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React Native" />
      <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
      <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" alt="Electron" />
      <img src="https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white" alt="Redux" />
      <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h4>⚙️ Backend Engineering</h4>
      <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white" alt="Express.js" />
      <img src="https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white" alt="Fastify" />
      <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" alt="GraphQL" />
      <img src="https://img.shields.io/badge/REST%20APIs-7aa2f7?style=flat-square" alt="REST APIs" />
      <img src="https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white" alt="WebRTC" />
      <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="WebSockets" />
    </td>
    <td valign="top" width="50%">
      <h4>🗄️ Databases & Caching</h4>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
      <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
      <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase" />
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h4>☁️ Cloud & DevOps</h4>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
      <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" />
      <img src="https://img.shields.io/badge/NixOS-5277C3?style=flat-square&logo=nixos&logoColor=white" alt="NixOS" />
      <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
    </td>
    <td valign="top" width="50%">
      <h4>🤖 AI & Systems</h4>
      <img src="https://img.shields.io/badge/OpenAI%20Realtime-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI Realtime" />
      <img src="https://img.shields.io/badge/LangChain-1C3C3A?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
      <img src="https://img.shields.io/badge/Agentic%20AI-9ece6a?style=flat-square" alt="Agentic AI" />
      <img src="https://img.shields.io/badge/System%20Design-bb9af3?style=flat-square" alt="System Design" />
      <img src="https://img.shields.io/badge/Distributed%20Systems-2ac3de?style=flat-square" alt="Distributed Systems" />
    </td>
  </tr>
</table>

---

## 🏗️ Engineering Experience

*   **Production Backend Systems:** Extensive expertise in Node.js runtime environments using Fastify and Express to build low-latency, highly concurrent API microservices.
*   **Database Architectures:** Designing secure MySQL, PostgreSQL, and SQLite databases using Knex or Prisma, combined with raw indexed SQL optimizations to speed up relational data fetches.
*   **Authentication & Access Control:** Implementing JWT tokens, session cookies, TOTP MFA, face authentication, and granular multi-tenant row-level access control filters.
*   **Mobile & Desktop Sandboxing:** Porting standalone Node.js and Python environments directly to Android devices via Expo, and implementing secure local folder lockers using Electron.
*   **Low-Level Networking:** Orchestrating per-process and adapter-level routing tables in Windows using Windows Filtering Platform hooks and WinDivert packet captures.

---

## 🏆 Professional Highlights

*   **3+ Years** of professional engineering and technology leadership experience as a CTO.
*   **10+ Real Production Systems** designed, shipped, and actively maintained.
*   **99.9% Service Uptime** maintained across production SaaS and enterprise portfolios.
*   **10k+ Active Users** served daily via compliant business databases.

---

## 📈 GitHub Metrics

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=Hjgaming&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" height="195" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs?username=Hjgaming&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="195" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Hjgaming&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Hjgaming&theme=tokyonight&hide_border=true&bg_color=1a1b26" alt="Activity Graph" />
</p>

<p align="center">
  <img src="https://github-profile-trophy-liard-delta.vercel.app/?username=Hjgaming&theme=tokyonight&no-bg=true&no-frame=true&margin-w=15" alt="GitHub Trophies" />
</p>

### 👾 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hjgaming/Hjgaming/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Hjgaming/Hjgaming/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Hjgaming/Hjgaming/output/github-contribution-grid-snake.svg">
  </picture>
</p>

---

## 🌱 Currently Exploring

*   🤖 **Agentic AI & Multi-Agent Workflows:** Developing autonomous developer-agent tools utilizing LangChain and function-calling LLM models.
*   🧠 **RAG (Retrieval-Augmented Generation):** Designing high-efficiency semantic vector search indexes for legacy business compliance documents.
*   ☁️ **Nix & Declarative Environments:** Engineering developer execution environments leveraging the reproducibility of Nix flakes.
*   ⛓️ **WebAssembly at the Edge:** Exploring fast, lightweight execution of compiled C/Rust modules in web sandboxes.

---

## 🤝 Let's Connect

<p align="center">
  <a href="mailto:harshal@magnytesolution.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://linkedin.com/in/harshal-jariwala-cto">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/Hjgaming">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://magnytesolution.com">
    <img src="https://img.shields.io/badge/Portfolio-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://leetcode.com/u/hjgaming/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode" />
  </a>
</p>

---

<p align="center">
  <i>"Software engineering is not just about writing lines of code; it is the art of translating human intent into highly optimized, fault-tolerant digital infrastructure."</i>
</p>
