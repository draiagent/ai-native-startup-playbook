# AI Native Startup Playbook

一個可直接部署至 GitHub Pages 的互動式單頁網站，整合：

- AI 原生創業的四大核心價值
- 創新創業 12 個階段
- AI Startup 工具地圖
- 公司從 `$0` 到 `$100K MRR` 的五個成長階段
- 企業級 AI 導入框架

## 線上網站

部署後網址通常為：

```text
https://<你的 GitHub 帳號>.github.io/<repository-name>/
```

## 專案結構

```text
ai-native-startup-playbook/
├─ index.html
├─ README.md
└─ LICENSE
```

本專案採用純 HTML、CSS 與 JavaScript，不依賴任何框架或建置工具。

## 本機預覽

直接雙擊 `index.html` 即可開啟。

亦可使用簡易伺服器：

```bash
python -m http.server 8000
```

瀏覽器開啟：

```text
http://localhost:8000
```

## 上傳 GitHub

### 1. 建立 Repository

建議名稱：

```text
ai-native-startup-playbook
```

建議 Description：

```text
Interactive AI-native startup playbook covering 4 core values, 12 startup stages, AI tool stack, $0–$100K MRR growth roadmap, and enterprise AI adoption framework.
```

### 2. 上傳檔案

將以下檔案上傳至 Repository 根目錄：

- `index.html`
- `README.md`
- `LICENSE`

### 3. 啟用 GitHub Pages

1. 進入 Repository 的 **Settings**
2. 點選 **Pages**
3. 在 **Build and deployment** 選擇 **Deploy from a branch**
4. Branch 選擇 `main`
5. Folder 選擇 `/ (root)`
6. 點選 **Save**

等待數分鐘後即可取得公開網址。

## 主要互動功能

- 置頂導覽列與平滑捲動
- 12 個創業階段點選切換
- 工具地圖分類篩選
- 五個 MRR 成長階段互動說明
- 響應式版面，支援桌機、平板與手機
- 無外部套件，部署與維護成本低

## 內容框架

### 四大核心價值

1. Faster Execution
2. Better Decisions
3. Lower Risk
4. Scale Smart

### 創業 12 階段

1. 找到高價值問題
2. PRD 與系統架構
3. UI / UX
4. 建立 MVP
5. QA 與驗證
6. 數據分析
7. 內容引擎
8. 行銷
9. AI SDR 銷售
10. 客戶成功
11. 營運管理
12. 規模化至 `$100K MRR`

### 企業 AI 導入框架

企業級導入在商業應用之外，需補足：

- Context Engineering
- RAG 與知識治理
- Agent Orchestration
- MCP 與工具連接
- Evaluation
- Security 與 Governance
- Observability
- ROI / SROI 與持續優化

## 自訂方式

可直接編輯 `index.html` 內的資料陣列：

```javascript
const stages = [...]
const toolGroups = [...]
const growth = [...]
```

調整網站色彩時，可修改 `:root` 內的 CSS 變數。

## License

MIT License
