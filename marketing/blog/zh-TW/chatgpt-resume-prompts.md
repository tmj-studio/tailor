---
title: "12 個真的有用的 ChatGPT 履歷 Prompt（可直接複製貼上）"
meta_description: "12 個實測過、可直接複製的 ChatGPT 履歷 prompt：對齊 JD、找關鍵字缺口、改弱詞、寫 summary，含完整工作流範例。"
language: "zh-TW"
slug: chatgpt-resume-prompts
category: resume
date: 2026-04-27
author: TMJ Studio
cover_image: /images/blog/chatgpt-resume-prompts.jpg
---

# 12 個真的有用的 ChatGPT 履歷 Prompt（可直接複製貼上）

網路上多數「ChatGPT 履歷 prompt」文章給的是通用指令，產出也是通用內容。這篇的 prompt 不一樣：經過實測、結構讓模型拿到需要的脈絡、可以直接貼進 ChatGPT、Claude、Gemini 或任何現代 LLM。

核心原則：**模型的好壞取決於你給的輸入**。模糊的 prompt 產出模糊的履歷。具體的 prompt（含真實經歷、真實 JD、清楚約束）產出具體可用的 bullet。

底下是我最常用的 12 個 prompt，按用途分類。

## 怎麼用這些 Prompt

三個產出可用結果的規則：

1. **替換掉中括號裡的占位符**：占位符存在是因為模型需要實質內容才能運作
2. **要求 JD 的時候永遠貼完整版**：摘要會丟掉模型需要鏡像的關鍵字
3. **迭代，不要接受第一版**：第一版只是起點。回 "把第 3 條 bullet 量化" 或 "summary 壓 2 行" 直到對位

ChatGPT（或任何 LLM）是寫稿夥伴不是神諭。它產出的 bullet 還是需要你判斷。聽起來灌水或不對就推回去。

## Prompt 1：把 Bullet 對齊 JD

```
You are a senior resume editor. I will give you (1) a bullet from my current resume and (2) a job description. Rewrite the bullet so it mirrors the JD's language and emphasizes the most relevant aspect of the work, while staying truthful to what I actually did. Do not invent facts.

Original bullet: [貼 bullet]

Job description:
[貼完整 JD]

Output: rewritten bullet, 1-2 lines max, with at least one quantified outcome and at least one keyword from the JD's "Requirements" section.
```

這是主力 prompt。投特定職位時，最近一份工作的每條 bullet 都跑一次。

## Prompt 2：產出客製化 Summary

```
Write a 2-3 sentence professional summary for my resume, targeted at this job description. Use language and emphasis from the JD. Reference my actual experience, not generic claims.

My background:
- [年資] in [function/industry]
- [具體工具、框架、領域]
- [2-3 個有量化的代表性成就]

Job description:
[貼完整 JD]

Output: a tight 2-3 sentence summary, no fluff, no "results-driven professional" language.
```

「no fluff」那行很重要。不寫的話 ChatGPT 會預設輸出企業套話，加了之後產出才能用。

## Prompt 3：給弱 Bullet 加量化成果

```
Rewrite the following bullets to include quantified outcomes (numbers, percentages, time saved, revenue impact). Where I do not provide a number, ask me a clarifying question instead of inventing one.

Bullets:
1. [貼 bullet]
2. [貼 bullet]
3. [貼 bullet]

Output: rewritten bullets with quantified outcomes, or specific clarifying questions where you need data from me.
```

「ask me clarifying questions」這個指令是關鍵，能阻止模型編造數字 — 那是 AI 履歷 prompt 最常見的失敗模式。

## Prompt 4：找出缺少的關鍵字

```
Compare my current resume bullets against this job description. List the keywords and phrases that appear in the JD's "Requirements" or "Responsibilities" sections but do NOT appear in my resume. Categorize each missing keyword as:
- "Critical" (likely a must-have for ATS screening)
- "Important" (mentioned multiple times in JD)
- "Nice to have" (mentioned once, peripheral)

My resume bullets:
[貼相關 bullet]

Job description:
[貼完整 JD]

Output: a categorized list of missing keywords, with a one-sentence recommendation for each on whether and how to integrate it.
```

這個 prompt 做的事跟多數 ATS 檢查工具類似但更細緻。分類能幫你排序：critical 一定要補、nice-to-have 通常可以忽略。

關於 ATS 系統怎麼算關鍵字權重，看 [什麼是 ATS](/blog/what-is-ats)。

## Prompt 5：把「Responsible for」變成行動導向語言

```
Rewrite this bullet to lead with a strong action verb and emphasize what I accomplished, not what I was responsible for. Keep the underlying facts unchanged.

Original: [貼 bullet]

Output: rewritten bullet, lead with a strong verb (led, built, designed, scaled, reduced, etc.), avoid "responsible for", "worked on", "helped with".
```

如果你寫過「Responsible for managing the team」，這個 prompt 5 秒幫你改掉。

## Prompt 6：壓縮 Bullet 變成一頁履歷

```
I need to fit my resume on one page. Rewrite each of these bullets to be one line maximum (about 15-20 words) while preserving the most important content: action verb, quantified outcome, and one JD-relevant keyword. If a bullet has multiple achievements, keep only the strongest.

Bullets:
1. [貼 bullet]
2. [貼 bullet]
3. [貼 bullet]

Output: tightened one-line versions.
```

長度決策的更多討論看 [履歷應該寫多長](/blog/how-long-should-a-resume-be)。

## Prompt 7：寫轉職履歷的 Summary

```
I am changing careers from [現在領域] to [目標領域]. Write a 2-3 sentence summary for my resume that:
- Names the pivot directly without sounding apologetic
- Highlights transferable skills relevant to the target role
- Uses language from the target role's job description below

Target JD:
[貼完整 JD]

Relevant transferable experience:
- [可轉移技能/成就 1]
- [可轉移技能/成就 2]
- [可轉移技能/成就 3]

Output: tight summary that positions the career change as an asset, not a deficit.
```

完整轉職履歷做法看 [career change resume](/blog/career-change-resume)。

## Prompt 8：產出 Bullet 變體做 A/B 測試

```
Give me 3 variations of this bullet, each emphasizing a different aspect:
- Version 1: emphasizes scale (size of team, scope, budget)
- Version 2: emphasizes outcome (revenue, growth, retention metric)
- Version 3: emphasizes process (how I did it, methodology, cross-functional aspect)

Original bullet: [貼 bullet]

Output: three labeled variations.
```

當你有強的成就但不確定哪個切角最對位時很好用。把每個變體丟去比對不同 JD，用 JD 強調什麼就用對應版本。

## Prompt 9：審查履歷段落的弱詞語

```
Review the following resume section and flag every instance of weak language. For each, suggest a stronger replacement. Specifically look for:
- "Responsible for" / "duties included"
- Vague verbs like "worked on", "helped with", "involved in"
- Unsubstantiated adjectives ("excellent", "strong", "results-driven")
- Bullets without quantified outcomes
- Buzzwords that add no information

Section to audit:
[貼段落]

Output: a numbered list of issues with proposed rewrites.
```

最後一輪清理很好用。投遞前分段在整份履歷上跑一次。

## Prompt 10：寫對齊特定職位的 Cover Letter 開頭

```
Write a cover letter opening paragraph (3-4 sentences) for the following role. The opening should:
- Reference a specific aspect of the company or product (not generic flattery)
- State the role I am applying for
- Connect one specific accomplishment from my background to the role's stated needs

Role: [職稱]
Company: [公司名]
Why this company excites me: [1-2 個具體原因 - 產品、使命、近期新聞]

Job description:
[貼完整 JD]

My most relevant accomplishment: [貼 1 條 bullet]

Output: a tight 3-4 sentence opening, no "I am writing to apply for".
```

Cover letter 在某些產業在式微，某些產業還是必要的。需要寫的時候，這個 prompt 產出的開頭不會跟其他申請者一樣。常見錯誤看 [cover letter mistakes](/blog/cover-letter-mistakes)。

## Prompt 11：把履歷翻譯到不同產業

```
I am applying for a [目標職位] in [目標產業] but my background is in [現在產業]. Rewrite the following bullet so a hiring manager in the target industry will understand the value, using terminology from the target industry where appropriate. Do not invent facts.

Original bullet: [貼 bullet]

Target industry context (key terms, KPIs, or concepts they care about):
[列 3-5 個你知道目標產業在乎的概念]

Output: rewritten bullet that translates the achievement for the target audience.
```

這個是轉職者最有用的 prompt。ChatGPT 沒辦法猜目標產業的術語，你得餵它詞彙。

## Prompt 12：最終比對分數估算

```
Estimate a match score (0-100) between my resume and this job description, based on:
- Keyword overlap (40% of score)
- Experience level alignment (30% of score)
- Specific skills/tools alignment (20% of score)
- Soft-skills alignment (10% of score)

Then list the 3 highest-impact changes I could make to raise the score.

My resume:
[貼完整履歷]

Job description:
[貼完整 JD]

Output: numeric score, breakdown by category, and 3 prioritized recommendations.
```

這是 sanity check 不是最終答案。模型給的分數是估算。價值在排序過的建議，通常會浮現你漏掉的 1-2 個改動。

## ChatGPT 履歷 Prompt 失敗的常見原因

### 沒給脈絡就要「一份好履歷」
模型不知道你投什麼職位、實際經歷什麼、想要什麼語氣。通用輸入產出通用輸出。永遠附 JD 和底層事實。

### 讓它編造數字
「銷售提升 47%」聽起來很棒，但你沒測過就無法在面試時辯護。永遠告訴模型：「沒給數字就問我」。

### 相信第一版輸出
任何 LLM 的第一版都只是起點。迭代。「壓緊第 2 條 bullet」、「summary 不要那麼企業化」、「拿掉第 4 條的 buzzword」。三輪迭代後才有可用的東西。

### 一個 prompt 包整份履歷
叫模型「寫一份履歷給我」是通用輸出的配方。把任務拆開：summary、bullet 改寫、技能區、缺口分析，一個 prompt 一個任務。

### 沒約束語氣
沒明確約束，LLM 預設會輸出企業 buzzword 湯。要禁的詞：「results-driven」、「synergy」、「leveraged」、「cutting-edge」、「passionate about」。

## 對台灣使用者的補充

如果你用 ChatGPT 改中文履歷，提示語可以用中文，但建議要求模型「保持台灣繁體中文用語、不要用大陸用語」。另外台灣 104 履歷有平台格式，prompt 改寫的內容主要用在自傳和工作經歷敘述。如果你準備英文履歷投外商，上面 12 個 prompt 直接英文跑效果最好。

## ChatGPT 結合比對工具的工作流

ChatGPT 擅長產出和改寫，但沒那麼可靠在準確評分履歷對 JD 的匹配度，因為它不一定照真 ATS 引擎的方式算關鍵字權重。

最強的工作流是兩者結合：用 ChatGPT 起草和改寫（Prompt 1-9），結果丟去 [Tailor](/tailor) 跑真正 ATS 風格的比對分數和剩下的關鍵字缺口清單。ChatGPT 負責產出，專門工具負責驗證。

更多 AI 輔助履歷的內容看 [AI resume optimization guide](/blog/ai-resume-optimization-guide)。

## 完整工作流範例

這是我投單一職位時，從頭到尾怎麼用這些 prompt：

1. **Prompt 4**（缺失關鍵字）— 先看缺什麼
2. **Prompt 1**（每條 bullet 客製化）— 跑最近 5 條 bullet
3. **Prompt 2**（客製化 summary）— bullet 對齊後再做
4. **Prompt 9**（弱詞語審查）— 最後一輪清理
5. **Prompt 12**（比對分數）— 投遞前 sanity check

總時間：每份申請大概 25-30 分鐘做完整客製化。比手動快、產出通常更銳利，前提是你給真實輸入並編輯輸出。

底層的客製化方法論看 [如何客製化履歷對齊 JD](/blog/tailor-resume-to-job-description)。

## ChatGPT 做不到的事

對極限要誠實：

- **不能驗證你的數字是不是真的**。那是你的責任。
- **不能真的判斷適配度**。任何 LLM 給的比對分數都是近似值。
- **不能取代你對語氣的人類判斷**。同一條 bullet 對 A 招募人員是自信、對 B 招募人員是自負。還是你自己判斷。
- **看不到 JD 以外的公司文化**。有內部資訊就要自己整合。

LLM 是機械化部分的槓桿：改寫、鏡像、找缺口、壓緊。策略部分 — 講什麼故事、瞄什麼職位、什麼時候推回 bullet — 還是你的。

## 結論

ChatGPT 履歷 prompt 有用的前提是：把 LLM 當成快速、流暢、有點過度自信的寫稿助理。餵它真實內容、貼真實 JD、明確約束輸出。上面 12 個 prompt 涵蓋 90% 的履歷寫作任務。用上面的工作流組合來提升每份申請效率。

ATS 友善格式可以搭配這些內容 prompt 一起用，看 [ATS 友善履歷模板](/blog/ats-friendly-resume-template)。

## 常見問題

### ChatGPT、Claude、Gemini 哪個最適合寫履歷？

三個給同樣結構良好的 prompt 時產出差不多。ChatGPT (GPT-4) 和 Claude 比較會照約束、Gemini 比較快但稍微沒那麼精確。模型的差異比輸入品質的差異小。用你能取得的就好。

### 用 ChatGPT 寫履歷會不會傷我的錄取機率？

只在你接受第一版、把 AI buzzword 湯交出去的時候會。ATS 不會偵測 AI 寫的履歷。招募人員會察覺通用感，不論是誰寫的。用 ChatGPT 起草和改寫，然後編輯到聽起來像你、有真實數字和具體成就。

### 可以直接貼完整履歷叫它重寫嗎？

不行。單一 prompt 重寫整份履歷會產出通用內容，因為模型缺少具體方向。把任務拆成幾個（summary、bullet、技能、缺口分析），一個 prompt 一個任務，附 JD 和你的真實內容當輸入。上面 12 個 prompt 就是這個拆分。

### ChatGPT 會編造我沒有的經驗嗎？

會，如果你讓它做。解法是明確告訴它「do not invent facts」和「沒給數字就問我」。加了這兩個約束，模型會把缺口浮給你回答而不是捏造數據。

### ChatGPT 知道 ATS 在找什麼嗎？

大致上知道。ChatGPT 能辨識關鍵字缺口、建議標準的 ATS 友善措辭。做不到的是模擬特定 ATS 引擎的實際評分，因為各家廠商不同。內容用 ChatGPT、最終評分用專門的 ATS 檢查工具。

### 一條 bullet 通常要迭代幾次才會好？

通常 2-3 次。第一版通用、第二版加細節、第三版調語氣。三輪後還不滿意，問題通常是你沒給夠具體輸入，不是模型不行。

### 我該告訴 ChatGPT 我的真實數字嗎？

告訴它。模型不會把你的資料拿去 ATS 用，只是需要數字才能寫出更好的 bullet。擔心隱私的話可以模糊化或用範圍，但輸入越準確、輸出越準確。

### ChatGPT 寫 cover letter 跟寫履歷一樣容易嗎？

一樣，方法也一樣：具體公司資訊、具體成就、貼 JD、明確語氣約束。Cover letter 的風險是模型預設會用公式化語句（「I am writing to apply for...」）。在 prompt 裡禁掉這類語句，輸出會明顯變好。
