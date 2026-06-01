# Profile README Guide

這份文件是 `README.md` 的維護說明，不建議直接放進 GitHub profile 首頁。

## 圖片與 SVG 使用方式

- Hero typing animation: 使用 `readme-typing-svg` 產生動態 SVG，URL 已放在 `README.md` Hero section。
- Tech Stack icons: 使用 Devicon CDN，每個分類以 icon 加文字呈現，不只是一整排 logo。
- GitHub Stats: 使用 `github-readme-stats` 產生 stats 與 top languages SVG。
- Contribution Graph: 使用 `github-readme-activity-graph` 產生近 31 天活動圖。
- Contribution Snake: 使用 `.github/workflows/snake.yml` 產生 `github-contribution-grid-snake.svg` 與 dark mode 版本，並發布到 `output` branch。
- Snake 圖片引用路徑:
  - `https://raw.githubusercontent.com/chenpoyu/chenpoyu/output/github-contribution-grid-snake.svg`
  - `https://raw.githubusercontent.com/chenpoyu/chenpoyu/output/github-contribution-grid-snake-dark.svg`

## GitHub Action 設定檔

完整設定已建立在:

```text
.github/workflows/snake.yml
```

目前設定使用 `Platane/snk/svg-only@v3` 產生 SVG，並使用 `crazy-max/ghaction-github-pages@v5` 發布到 `output` branch。

第一次使用時:

1. Push 到 `main`。
2. 到 GitHub repository 的 Actions 頁面啟用 workflow。
3. 手動執行 `Generate contribution snake`。
4. 確認 repository 出現 `output` branch。
5. 回到 profile 頁面確認 snake SVG 是否正常顯示。

## TODO

- 將三個 Featured Projects 的 public-safe `Repo Placeholder` 或 case summary 補齊。
- 補上每個 Featured Project 的真實 Tech Stack，不要只保留 placeholder。
- 如果專案是 private、organization repository、政府標案或內部系統，確認哪些資訊可以公開，避免放出客戶敏感細節。
- 將最符合定位的 repository pin 到 GitHub profile。
- 定期更新 `Currently Exploring`，避免它變成過期清單。
- Snake workflow 第一次跑完後，檢查 `output` branch 的兩個 SVG 是否存在。
- 檢查外部 SVG 服務是否在 GitHub profile 上正常渲染。

## 建議放入哪些實際 Repository

以下是根據公開 GitHub API 讀到的 public repositories。不要直接硬塞進 Featured Projects，先確認內容是否符合你想呈現的定位。

- `https://github.com/chenpoyu/MemberManagerSystem`
  - 可評估放入 `Membership & Access Platform`。
  - 只有在內容真的包含會員、身份、角色、權限或管理流程時再放進去。

- `https://github.com/chenpoyu/tools`
  - 可評估放入 `Internal & Government Systems` 或 `Operational Platform Architecture` 的輔助工具。
  - 若它是工具箱或自動化集合，可以補上具體場景與使用方式。

- `https://github.com/chenpoyu/my-blog`
  - 不一定適合放 Featured Projects，但很適合在 profile 中作為技術輸出入口。
  - 若部落格內有營運平台、內部系統、政府標案、系統整合或 IAM 文章，可以未來自動抓最新文章。

- `https://github.com/chenpoyu/chenpoyu.github.io`
  - 可作為個人網站或作品入口，不建議放在三個核心 Featured Projects 裡，除非它本身就是產品平台展示。

- `games-*` repositories
  - 目前與 IAM、Platform Engineering、Workflow Automation 定位較遠。
  - 可以保留在 GitHub profile pinned repos 之外，除非你想增加 side project 趣味性。

- `Coursera-*` repositories
  - 建議視為學習歷程，不放在首頁核心區塊。

公開 API 沒有回傳 public organizations。若你有 private 或 organization repository，建議優先放真正能代表以下能力的專案:

- 營運平台與內部系統設計
- 政府標案或長期維運專案的 public-safe case summary
- 跨系統整合、資料流與 API Gateway 設計
- 內部流程與營運工具
- 跨角色 workflow 與審核流程
- 身份與權限模型設計
- 可維護的後端架構
- 有清楚 README、截圖、架構圖或設計說明的 repo

可轉成 public-safe case summary 的既有專案類型:

- 車聯網/物聯網事件流與遠端服務平台
- 零售電商、物流、充電站或會員營運平台
- 政府公文交換、邊坡/隧道管理、電子簽核等內部流程系統
- 跨品牌會員、SSO、Token 狀態與會員資料流整合

## 未來可以自動化更新的區塊

- Blog 最新文章: 用 GitHub Actions 從 RSS 或網站資料產生 Markdown。
- Currently Exploring: 用一份 `profile-data/exploring.yml` 管理，再由 workflow 寫回 README。
- Featured Projects: 用 `profile-data/projects.yml` 管理 repo、focus、tech stack 與描述。
- GitHub Activity: 目前已透過外部 SVG 自動更新。
- Contribution Snake: 目前已透過 `.github/workflows/snake.yml` 每天自動更新。
- Last Updated: 可以加在 HTML comment 裡，避免 profile 頁面顯得像自動產生文件。

## References

- GitHub public repositories API: `https://api.github.com/users/chenpoyu/repos?per_page=100&sort=updated`
- Platane/snk: `https://github.com/Platane/snk`
- crazy-max/ghaction-github-pages: `https://github.com/crazy-max/ghaction-github-pages`
- GitHub Readme Stats: `https://github.com/anuraghazra/github-readme-stats`
- GitHub Readme Activity Graph: `https://github.com/ashutosh00710/github-readme-activity-graph`
- Personal profile page: `https://poyu-chen.pyvot.uk/#/profile`
- Architecture cases page: `https://poyu-chen.pyvot.uk/#/tech-architecture`
