<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&height=280&color=gradient&text=Paul%20Mathew&desc=Senior%20Android%20Engineer%20|%20AI-Agent%20Mobile%20UX%20|%20Realtime%20Architecture%20|%20Premium%20UI/UX&descAlign=50&descAlignY=65&textBg=false&fontSize=66&descSize=20&animation=fadeIn&section=header&fontColor=FFF" width="100%" />
</div>

<br />

<div align="center">

### Architecting resilient Android systems across AI-agent UX, realtime communication, offline-first sync, and premium mobile experiences.

Senior Android Engineer with 12+ years of experience building large-scale consumer-facing Android applications, realtime communication systems, offline-first mobile architectures, and production-style AI-agent interaction flows used across global environments.

My work combines deep mobile systems engineering with high-quality Jetpack Compose product experiences — focusing on realtime behavior, synchronization reliability, AI-stream resilience, interaction quality, scalable architecture, and calm user experiences under unreliable mobile conditions.

I enjoy solving difficult distributed mobile systems problems while ensuring the final product experience feels intuitive, responsive, observable, and trustworthy to end users.

<br />

<a href="https://www.linkedin.com/in/impaulmathew/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:mpaul97@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

---

# 🚀 Featured Projects

## ResilientAIStreamer

> A production-style Android AI-agent vertical slice focused on on-device ML, resilient streaming UX, partial failure recovery, retry-from-failure, and observability.

ResilientAIStreamer explores what happens when AI interactions are not perfectly deterministic — when responses stream slowly, fail midway, or need to recover without losing user trust.

### Highlights

- **On-Device ML Input Layer:** Uses Google ML Kit Text Recognition for local image-to-text extraction without sending image payloads to a backend.
- **AI-Agent Streaming UX:** Streams mocked AI responses incrementally using Kotlin Flow to simulate LLM-style token/chunk delivery.
- **Partial Failure Recovery:** Deliberately introduces stream interruptions and preserves the successfully generated partial response.
- **Retry from Failure Point:** Resumes streaming from a stable failed chunk index instead of restarting the full response.
- **StateFlow-Driven State Containment:** Converts non-deterministic stream behavior into explicit UI state snapshots.
- **Observability & Diagnostics:** Logs stream start, chunk latency, latency spikes, interruptions, retries, and completion events.
- **TensorFlow Lite-Ready Architecture:** Keeps the ML layer behind a clean domain boundary so a TensorFlow Lite/LiteRT implementation can replace ML Kit without changing UI or business logic.

### Built With

`Kotlin` · `Jetpack Compose` · `StateFlow` · `Coroutines / Flow` · `Hilt` · `Google ML Kit` · `On-device ML` · `AI-agent UX` · `Retry / Recovery` · `Observability`

<div align="center">
  <a href="https://github.com/paulmathew/ResilientAIStreamer">
    <img src="https://img.shields.io/badge/View_ResilientAIStreamer-238636?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</div>

<br />

## PulseSync

> A premium offline-first collaborative Android experience designed for unreliable mobile networks.

PulseSync explores how sophisticated synchronization systems can quietly create calmer, more trustworthy collaborative mobile experiences.

### Highlights

- **Optimistic Interactions:** Instant-feeling UI states designed to preserve flow and responsiveness during background synchronization.
- **Calm Synchronization UX:** Elegant loading states and subtle interaction feedback built specifically for unstable mobile environments.
- **Realtime Collaborative Workspace Flows:** Collaborative interaction patterns designed for smooth multi-user editing experiences.
- **Offline-First Persistence:** Reliable local-first state handling with graceful retry and synchronization recovery behaviors.
- **Elegant Conflict Resolution:** Trust-preserving collaborative recovery experiences for overlapping user changes.
- **Lightweight Mini-App Architecture:** Composable workspace modules designed to scale product experiences cleanly without overwhelming the interface.

### Built With

`Kotlin` · `Jetpack Compose` · `StateFlow` · `Hilt` · `Room` · `Offline-first synchronization`

<p align="center">
  <img src="https://raw.githubusercontent.com/paulmathew/PulseSync/main/docs/screenshots/v2/workspace-feed.png" width="260"/>
  <img src="https://raw.githubusercontent.com/paulmathew/PulseSync/main/docs/screenshots/v2/focus-session.png" width="260"/>
  <img src="https://raw.githubusercontent.com/paulmathew/PulseSync/main/docs/screenshots/v2/conflict-resolution-v2.png" width="260"/>
</p>

<div align="center">
  <a href="https://github.com/paulmathew/PulseSync">
    <img src="https://img.shields.io/badge/Explore_PulseSync-238636?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</div>

<br />

## CallInspector

> Android diagnostics and realtime communication reliability tooling.

CallInspector focuses on:

- Realtime communication diagnostics and media routing visibility
- Device-level hardware testing and OS component validation
- Network-state analysis and mobile runtime reliability debugging
- Production-style observability patterns for unstable call environments

### Built With

`Jetpack Compose` · `Zoom Video SDK` · `Hilt` · `Room` · `Multi-module Architecture` · `Realtime Diagnostics`

<div align="center">
  <a href="https://github.com/paulmathew/CallInspector">
    <img src="https://img.shields.io/badge/View_CallInspector-238636?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</div>

---

# 🛠 Core Technologies

<div align="center">

<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
<img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" />
<img src="https://img.shields.io/badge/Coroutines%20%26%20Flow-00599C?style=for-the-badge&logo=kotlin&logoColor=white" />
<img src="https://img.shields.io/badge/StateFlow-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
<img src="https://img.shields.io/badge/Hilt-D00000?style=for-the-badge&logo=android&logoColor=white" />
<img src="https://img.shields.io/badge/Room-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
<img src="https://img.shields.io/badge/Google%20ML%20Kit-4285F4?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/On--Device%20ML-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
<img src="https://img.shields.io/badge/TensorFlow%20Lite--Ready-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
<img src="https://img.shields.io/badge/AI--Agent%20UX-8E44AD?style=for-the-badge" />
<img src="https://img.shields.io/badge/Realtime%20Systems-2D8CFF?style=for-the-badge" />
<img src="https://img.shields.io/badge/Offline--First%20Architecture-5C6BC0?style=for-the-badge" />
<img src="https://img.shields.io/badge/Zoom%20Video%20SDK-2D8CFF?style=for-the-badge&logo=zoom&logoColor=white" />
<img src="https://img.shields.io/badge/Multi--Module%20Architecture-5C6BC0?style=for-the-badge&logo=gradle&logoColor=white" />

</div>

---

# 📊 Engineering Activity

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=paulmathew&theme=tokyonight&hide_border=true" height="180"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=paulmathew&theme=tokyonight" height="180" />

</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/paulmathew/paulmathew/output/github-contribution-grid-snake.svg" />
</div>

---

# ⚡ Engineering Philosophy

- Build products that preserve user trust under failure conditions.
- AI-agent experiences should be resilient, observable, and recoverable.
- Realtime systems should feel calm, not fragile.
- Great infrastructure should become invisible inside the product experience.
- Premium UI/UX should feel effortless, responsive, and reliable.
- Fast iteration matters, but interaction quality matters equally.
- Reliability and UX are deeply connected problems.

---

# 🌱 Currently Exploring

- Android AI-agent interaction patterns
- On-device ML and TensorFlow Lite-ready mobile architecture
- Resilient streaming UX with Kotlin Flow
- Offline-first collaborative mobile UX
- Realtime synchronization systems
- Premium Jetpack Compose interaction design
- AI-assisted product engineering workflows
- Trust-preserving mobile product experiences

---

<div align="center">
  <sub>Building resilient Android systems across AI-agent UX, realtime communication, offline-first sync, and premium product experiences.</sub>
</div>

![](https://hit.yhype.me/github/profile?account_id=3655706)
