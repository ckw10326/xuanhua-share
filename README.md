# 烜華的知識分享

這是對外公開的知識分享網站，收錄投資、工具、旅遊、心理、工程等文章，供大家閱讀。倉庫名稱為 `xuanhua-share`，公開（Public）。

## 網址

- 網站：https://ckw10326.github.io/xuanhua-share/
- 倉庫：https://github.com/ckw10326/xuanhua-share

## 分類

- 投資（`articles/`）
- 工具（`tools/`）
- 旅遊（`travel/`）
- 心理（`psychology/`）
- 工程（`engineering/`）

## 資料夾結構

```
├── index.html                 # 首頁
├── README.md
├── WORKLOG.md                 # 工作紀錄
├── articles/                  # 投資
│   ├── tsmc_2330_valuation.html
│   ├── vis_5347_valuation.html
│   └── who_is_on_the_other_side_1.html
├── tools/                     # 工具
│   └── badminton-index.html
├── travel/                    # 旅遊
│   ├── index.html
│   └── airfare_promo_20261029.html
├── psychology/                # 心理
│   ├── attachment_anxious.html
│   ├── attachment_dismissive.html
│   ├── attachment_secure.html
│   └── chat_boundaries.html
└── engineering/               # 工程
    └── power-plant-grounding/
```

## 新增頁面規則

任何 AI 接手時，請依下列規則新增或修改頁面：

- **公開頁面**：放到對應分類資料夾，並在 `index.html` 首頁加上卡片。
- **Markdown 不能直接當網頁**：本站以 GitHub Pages 發布靜態檔，不會用 Jekyll 把 `.md` 轉成網頁。若內容是 Markdown，必須另外做一份 HTML 閱讀頁，並讓首頁或目錄連到 HTML。
- **私人頁面**：放在 `p/` 底下難以猜測的隱藏路徑；頁面要加 noindex 的 meta；不在首頁或任何公開頁放連結；不在 README、WORKLOG 或其他說明裡描述內容或完整路徑。提交與 PR 標題只用中性用詞（例如「新增頁面」「更新頁面」）。
- **工作紀錄**：每次改動都要在 `WORKLOG.md` 最上方新增一筆。公開頁寫清楚改了什麼與路徑；私人頁面只寫「新增頁面（隱藏）」或「更新頁面（隱藏）」，不寫人名與路徑。

## 維護者

Github大師（Grok Bot）

## 請勿刪除

這是正在運作的公開知識分享網站。刪除後網站會下線，且無法復原。
