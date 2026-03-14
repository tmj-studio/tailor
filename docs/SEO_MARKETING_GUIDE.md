# SEO 行銷懶人指南

部署完成後，按以下步驟推廣（不需要行銷背景）。

---

## 1. Google Search Console（必做，免費）

1. 到 https://search.google.com/search-console 登入
2. 新增 `tailor.tailormyjob.com` 網站
3. 用 DNS TXT 記錄驗證（在 Route53 加一條記錄）
4. 提交 sitemap：`https://tailor.tailormyjob.com/sitemap.xml`
5. 等 1-2 週讓 Google 索引你的頁面

### 驗證步驟（Route53）

```
記錄名稱: tailor.tailormyjob.com
類型: TXT
值: （Google Search Console 提供的驗證碼）
TTL: 300
```

---

## 2. 免費發文平台（每篇文章同步發一次）

把 blog 文章的內容稍微改寫後，發到這些平台：

| 平台 | 說明 | 注意事項 |
|------|------|----------|
| **Medium** | 發英文版 | 加上 canonical link 指回你的網站 |
| **Dev.to** | 技術導向社群 | 適合 ATS/resume 技術文章 |
| **LinkedIn Article** | 直接在 LinkedIn 發長文 | 可觸及專業人士 |
| **Reddit** | r/resumes、r/jobs、r/cscareerquestions | 不要太廣告感，提供價值 |

### Medium Canonical Link 設定

在 Medium 發文時，到 Story Settings → Advanced Settings → 填入原文 URL：
```
https://tailor.tailormyjob.com/blog/resume-tips-2026
```
這樣 Google 不會把 Medium 版本視為重複內容。

---

## 3. 社群媒體曝光（每週花 15 分鐘）

### 每週行程

| 日期 | 任務 |
|------|------|
| 週一 | LinkedIn 發 1 篇短貼文，附上 blog 連結 |
| 週三 | Twitter/X 分享一個求職小技巧 + blog 連結 |
| 週五 | 到 Facebook 求職社團分享有價值的內容 |

### LinkedIn 貼文模板

```
🎯 [引人注目的統計數據或問題]

[2-3 句描述問題或趨勢]

[你的解決方案/建議]

👉 完整文章：[blog 連結]

#resume #jobsearch #careertips #AI
```

---

## 4. 後續內容策略

### 發文頻率
- 每月新增 2-4 篇 blog 文章
- 可以用 AI 輔助撰寫初稿，但務必人工審核

### 關鍵字方向

以下是搜尋量較高的目標關鍵字：

| 關鍵字 | 月搜尋量（估計） | 競爭度 |
|--------|------------------|--------|
| resume tips | 40,000+ | 中 |
| ATS resume | 20,000+ | 中 |
| cover letter template | 50,000+ | 高 |
| job interview tips | 30,000+ | 中 |
| resume format 2026 | 10,000+ | 低 |
| how to write a resume | 60,000+ | 高 |
| ATS friendly resume | 15,000+ | 低-中 |

### 內容創作流程

1. 用 Google Search Console 觀察哪些關鍵字帶來流量
2. 找出排名 5-20 的關鍵字（有改善空間）
3. 寫更多相關文章強化這些關鍵字
4. 更新舊文章加入新資訊

### 文章類型建議

- **How-to 指南**：「如何寫出 ATS 友善的履歷」
- **清單文章**：「2026 年 10 大履歷趨勢」
- **比較文章**：「PDF vs DOCX：哪種格式更好？」
- **案例研究**：「如何靠優化履歷拿到 3 倍面試邀約」
- **常見問題**：「履歷要不要放照片？」

---

## 5. 進階技巧（選做）

### 5.1 Google Analytics 4 事件追蹤

確認以下事件有在追蹤：
- Blog 文章閱讀時間
- CTA 按鈕點擊率
- 文章分享次數

### 5.2 結構化資料驗證

用 Google Rich Results Test 驗證你的 Blog 頁面：
https://search.google.com/test/rich-results

確認 `BlogPosting` JSON-LD 正確顯示。

### 5.3 內部連結策略

- 每篇 blog 文章至少連結 1-2 篇其他文章
- 從 blog 連結到產品頁面（/tailor, /pricing）
- 從 FAQ 頁面連結到相關 blog 文章

---

## 工具推薦

| 工具 | 用途 | 費用 |
|------|------|------|
| Google Search Console | SEO 監控 | 免費 |
| Google Analytics 4 | 流量分析 | 免費 |
| Ubersuggest | 關鍵字研究 | 免費方案可用 |
| Canva | 社群媒體圖片 | 免費方案可用 |
| Buffer | 社群媒體排程 | 免費方案可用 |

---

## 檢查清單

- [ ] Google Search Console 已設定並驗證
- [ ] Sitemap 已提交
- [ ] 第一篇文章已發到 Medium
- [ ] LinkedIn 公司頁面已建立
- [ ] 第一週社群貼文已排程
- [ ] Google Analytics 4 事件追蹤已確認
- [ ] Rich Results Test 通過
