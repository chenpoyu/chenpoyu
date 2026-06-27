<div align="center">

# Poyu Chen 陳柏妤

### Building maintainable systems, tools, and notes around internal complexity.

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&amp;size=22&amp;duration=2300&amp;pause=700&amp;color=0969DA&amp;center=true&amp;vCenter=true&amp;width=720&amp;height=48&amp;lines=Identity+%26+Access+Management;Internal+Platforms;Workflow+Automation;System+Boundaries;Operational+Clarity" alt="Typing SVG: Identity and Access Management, Internal Platforms, Workflow Automation, System Boundaries, Operational Clarity" />

我關注那些藏在系統背後、但會決定它能不能長期維護的東西：<br/>
身份權限、內部流程、服務邊界、維運工具與交接文件。

<details>
<summary>English Version</summary>

I focus on the parts behind software systems that determine whether they can be maintained over time: identity, internal workflows, service boundaries, operational tools, and handover documentation.

</details>

</div>

---

## What I Work On

### 🔐 Identity & Access Management

身份、驗證與授權不只是登入功能，而是產品、團隊與責任邊界的一部分。
我整理 IAM、SSO、Keycloak、JWT 與 role model 相關的設計，讓權限邊界在系統成長後仍然能被理解與維護。

Identity and access management is not only about login. It defines product boundaries, team responsibilities, and operational risk.
I work on IAM, SSO, Keycloak, JWT, and role models that stay understandable as systems and teams grow.

常用技術：`Java` · `.NET Core` · `PostgreSQL` · `IAM` · `SSO` · `Keycloak` · `JWT`

---

### ⚙️ Internal Platforms

很多重要的系統問題不在產品畫面上，而是在內部流程、資料狀態、權限邊界與日常作業裡。
我喜歡把這些分散的流程整理成可追蹤、可維護、能交接的內部工具與平台。

Many important system problems do not appear on the product surface. They live in internal workflows, data states, access boundaries, and daily operations.
I build internal platforms and tools that make those workflows traceable, maintainable, and easier to hand over.

常用技術：`React` · `.NET Core` · `PostgreSQL` · `Redis` · `Docker`

---

### 🔄 Workflow Automation

重複流程如果沒有被整理，最後會變成團隊每天都要承擔的隱性成本。
我把容易漏接、難追蹤、需要跨系統協作的流程，整理成可靠、可觀測、能持續調整的系統。

Repetitive workflows become hidden operational cost when they are not organized.
I turn fragile, cross-system processes into reliable, observable, and adjustable workflows.

常用技術：`Docker` · `GitHub Actions` · `API Design` · `System Integration`

---

### 🧭 System Notes & Handover

好的交接文件比聰明的架構更重要。
我會把系統設計、重構決策、維運經驗與團隊流程寫下來，讓後面接手的人不用重新踩一次相同的坑。

Good handover documentation is often more valuable than clever architecture.
I write system notes about design decisions, refactoring, operations, and team workflows so that future maintainers do not need to rediscover the same context.

常見主題：`System Design` · `Refactoring` · `Maintenance` · `Documentation` · `Operational Clarity`

---

## Workbench

Not every system problem becomes a product feature. Some become tools, experiments, diagrams, notes, or rules of thumb.

不是每個系統問題最後都會變成產品功能。有些會變成工具、實驗、圖、筆記，或某種反覆被驗證的判斷方式。

### 🧰 Tools

日常開發中反覆出現的小問題：格式轉換、token 檢查、資料整理、時間換算、JSON、SQL、JWT。
這些東西不大，但會打斷工作。我把它們整理成可以重複使用的小工具。

Small utilities for repetitive development tasks: formatting, token inspection, data cleanup, timestamp conversion, JSON, SQL, and JWT.
They are not large systems, but they reduce small interruptions that accumulate over time.

→ [chenpoyu/tools](https://poyu-chen.pyvot.uk/tools)

---

### 🧪 Labs

一些 local-first 的系統實驗，用來拆解平常藏在企業系統背後的問題：gateway、API、database、cache、metrics、dashboard、CI、IAM 與服務邊界。

Local-first system experiments for making hidden infrastructure concerns visible: gateway, API, database, cache, metrics, dashboards, CI, IAM, and service boundaries.

* [local-platform-engineering-lab](https://github.com/chenpoyu/local-platform-engineering-lab) — local environment covering gateway, API, database, cache, metrics, dashboards, and CI wiring
* [local-platform-iam-lab](https://github.com/chenpoyu/local-platform-iam-lab) — local IAM experiment with Keycloak, SSO, JWT, and role model exploration; companion to the IAM work above

---

### 🏗️ Architecture Bases

一些可以被重複拿來討論、修改或延伸的後端架構底稿。  
它們不是追求最新寫法的樣板，而是用來整理企業內部系統常見的限制：舊資料庫、身份驗證、交接維護、本機開發、設定管理與部署邊界。

Reusable backend architecture bases for discussing, adapting, and extending enterprise internal systems.  
They are not meant to be perfect greenfield templates. They are shaped around common enterprise constraints: existing databases, authentication, handover, local development, configuration, and deployment boundaries.

- [NETCoreBase](https://github.com/chenpoyu/NETCoreBase) — legacy-friendly ASP.NET Core enterprise API base for JWT auth, DB First workflows, Docker-based local development, and handover-ready maintenance.
- [JavaSpringBase](https://github.com/chenpoyu/JavaSpringBase) — Spring Boot enterprise API base for JWT auth, IAM integration, layered architecture, and handover-ready Java backend maintenance.

---

### ✍️ Writing

工程工作裡留下來的筆記。
系統維護、重構決策、交接文件、團隊流程。不是教學文，更多是實際遇到問題之後的整理。

Notes from engineering work: system maintenance, refactoring decisions, handover documentation, and team workflows.
They are less like tutorials and more like records of what became clear after dealing with real problems.

→ [my-blog](https://poyu-chen.pyvot.uk/my-blog)

---

## Explore More

* 🌐 [Website](https://poyu-chen.pyvot.uk) — 工具、實驗、文章與更完整的整理
* ✍️ [Blog](https://poyu-chen.pyvot.uk/my-blog) — 系統設計、IAM、平台工程與維護筆記
* 🧰 [GitHub](https://github.com/chenpoyu) — 工具、實驗與公開專案
* 💼 [LinkedIn](https://www.linkedin.com/in/poyu-chen-207204191) — 工作經歷與專業連結

---

## GitHub Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=chenpoyu&theme=github_dark" alt="Poyu Chen GitHub profile summary" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=chenpoyu&theme=github_dark" alt="Repos per language" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=chenpoyu&theme=github_dark" alt="Most commit language" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/chenpoyu/chenpoyu/output/github-contribution-grid-snake.svg" alt="github contribution snake animation" />
</p>

---

## Contact

* Email: [chenpoyu1123@gmail.com](mailto:chenpoyu1123@gmail.com)
* Website: [poyu-chen.pyvot.uk](https://poyu-chen.pyvot.uk)
* Blog: [poyu-chen.pyvot.uk/my-blog](https://poyu-chen.pyvot.uk/my-blog)
* LinkedIn: [poyu-chen-207204191](https://www.linkedin.com/in/poyu-chen-207204191)
