# 專業倫理 LLM Wiki — 維護日誌（Changelog & Operations Log）

本文件記錄知識庫所有 Ingest（資料攝取）、Query（思辨沉澱）與 Lint（健康巡檢）操作紀錄。

---

## [2026-11-23] init | 系統初始化與 Agent.md 架構建立
- **操作類型**：系統初始化 (Initialization)
- **變更內容**：
  - 建立知識庫三層架構規範手冊 [[Agent.md]]。
  - 定義四大哲學學派分析透鏡：[[kantian-deontology]]、[[ross-deontology]]、[[moral-relativism]]、[[moral-absolutism]]。
  - 定義專業人士五大基本特質與義務原則：[[qualifications]]、[[autonomy]]、[[fiduciary-duty]]、[[informed-consent]]。
  - 初始化全域導航索引 [[index]] 與本維護日誌 [[log]]。
  - 規劃畢業生五大職場真實兩難案例骨架與 Slide-ready 案例模板。

## [2026-11-23] update | Agents.md 建立與 PDF 自動繁中化流程就緒
- **操作類型**：規範升級 (Schema Enhancement)
- **變更內容**：
  - 正式建立 [[Agents.md]]，確立完整知識庫治理與自動化作業手冊。
  - 新增 `rawpapers/` 資料夾，專門存放 PDF 教學講義與學術文獻。
  - 確立 PDF 自動化 SOP：接收 PDF 或下載 URL $\rightarrow$ 自動翻譯為臺灣繁體中文習慣用語 $\rightarrow$ 依六大設定維度（四大哲學、專業原則、畢業生兩難案例、法規守則、決策模型）結構化萃取為 `*_zh.md` $\rightarrow$ 聯動編譯回 `wiki/` 核心頁面。

## [2026-11-23] ingest | PDF: [[rawpapers/2026-fall-what-are-ethics-and-professional-ethics_zh]] | 秋季講義解析與 Wiki 概念擴充
- **操作類型**：PDF 攝取與知識編譯 (PDF Ingestion & Compounding)
- **來源文件**：`CLASS NOTES • FALL 2026: WHAT ARE ETHICS? & PROFESSIONAL ETHICS` (3 頁 PDF 講義)
- **繁中萃取成果**：存入 `rawpapers/2026-fall-what-are-ethics-and-professional-ethics_zh.md`。
- **Wiki 聯動擴充**：
  - 新增概念頁面：[[moral-temptation-vs-dilemma]]（剖析道德誘惑與道德兩難，引證米爾格倫服從實驗與史丹佛監獄實驗）。
  - 新增概念頁面：[[ethical-continuum]]（定義道德軟弱、道德底線與道德勇氣之三階光譜）。
  - 新增概念頁面：[[ethics-beyond-the-law]]（闡述法律為最低道德標準、道德能動者之積極抗惡責任）。
  - 更新導航索引 [[index]]。

## [2026-11-23] synthesis | HTML 簡報生成：康德義務論的核心理念與職場實踐
- **操作類型**：簡報生成 (Slide Generation)
- **產出檔案**：`slides/kantian-deontology.html` 與 `slides/index.html`。
- **內容特色**：
  - 共 11 張現代化互動簡報投影片（支援全螢幕、鍵盤換頁、縮圖總覽、動態進度條）。
  - 理論維度：動機論純粹性、定言令式 vs 假言令式、普遍法則公式、目的自身公式、局限與反思。
  - 整合 Wiki 四大畢業生真實案例：
    1. 辦公室微腐敗（私帶公物回家「大家都拿」）
    2. 醫療知情權（家屬要求瞞病 vs 病患自主權）
    3. 學術生存戰（資深教授評分放水 vs Tenure 威脅）
    4. 科技交付壓力（資安越權漏洞 vs 上線融資壓力）
  - 完美調用並嵌入專案 `assets/` 視覺插圖。

## [2026-11-23] ingest | URL: [[rawpapers/2021-06-udayakumar-kant-deontology_zh]] | IJRAR 康德義務論學術論文下載與精讀
- **操作類型**：外部論文攝取與知識庫深化 (URL Ingestion & Deep Compounding)
- **來源網址**：`https://www.ijrar.org/papers/21B2505_252105.pdf`
- **下載存檔**：`rawpapers/21B2505_252105.pdf` (352 KB)
- **繁中萃取成果**：存入 `rawpapers/2021-06-udayakumar-kant-deontology_zh.md`。
- **Wiki 聯動升級**：
  - 深化 [[kantian-deontology]]：補強定言令式第三公式「目的王國（Kingdom of Ends）」、動機反事實檢驗、完全義務 vs 不完全義務之劃分。
  - 升級 [[fiduciary-duty]]：引入「普遍義務（General Obligations）」與「角色特殊義務（Special Obligations）」之理論辯護，確立專業人士的受託義務地位。
  - 更新全局導航索引 [[index]]。

## [2026-11-23] ingest | URL: [[raw/theories/ethics-explainer-deontology_zh]] | The Ethics Centre 義務論導讀解析
- **操作類型**：權威網路文獻攝取與知識庫擴充 (Web Ingestion & Theoretical Refinement)
- **來源網址**：`https://ethics.org.au/ethics-explainer-deontology/`
- **發表機構**：The Ethics Centre (澳大利亞倫理學中心)
- **繁中萃取成果**：存入 `raw/theories/ethics-explainer-deontology_zh.md`。
- **Wiki 聯動升級**：
  - 更新 [[kantian-deontology]]：補充現代「界限義務論（Threshold Deontology）」概念以緩解純粹義務論的極端僵化；補充拉丁箴言 *Fiat justitia, ruat caelum*。
  - 連結普世人權體系（世界人權宣言）與宗教法典（十誡）之義務論脈絡。
  - 更新導航索引 [[index]]。

## [2026-11-23] ingest | URL: [[raw/theories/sep-william-david-ross_zh]] | 史丹佛哲學百科（SEP）W. D. 羅斯專題解析
- **操作類型**：權威哲學詞條攝取與理論深化 (SEP Ingestion & Theoretical Refinement)
- **來源網址**：`https://plato.stanford.edu/entries/william-david-ross/`
- **發表平台**：Stanford Encyclopedia of Philosophy (SEP)（執筆學者：Anthony Skelton）
- **繁中萃取成果**：存入 `raw/theories/sep-william-david-ross_zh.md`。
- **Wiki 聯動升級**：
  - 深化 [[ross-deontology]]：補強對功利主義的「回溯性義務（Backward-Looking Duties）」批判與「義務的高度個人特質（The Highly Personal Character of Duty）」；闡述顯見義務自明性 vs 實際義務仰賴亞里斯多德「實踐智慧（Phronesis）」之知識論架構；引入道德殘留（Moral Residue）與四大內在價值。
  - 更新全局導航索引 [[index]]。

## [2026-11-23] ingest | URL: [[raw/theories/1000word-prima-facie-duties_zh]] | 千字哲學 Matthew Pianalto 羅斯顯見義務解析
- **操作類型**：哲學專欄攝取與決策框架升級 (Web Ingestion & Framework Enhancement)
- **來源網址**：`https://1000wordphilosophy.com/2023/07/03/prima-facie-duties/`
- **發表平台**：1000-Word Philosophy: An Introductory Anthology（作者：Matthew Pianalto 教授）
- **繁中萃取成果**：存入 `raw/theories/1000word-prima-facie-duties_zh.md`。
- **Wiki 聯動升級**：
  - 升級 [[prima-facie-balancing-framework]]：融入「道德天平秤量（Moral Weighing）」模型與深思熟慮理性意見（Considered Opinions）。
  - 更新 [[ross-deontology]]：補充對「直覺論」質疑的正面辯護（直覺即正常理性思維，非神秘第六感）。
  - 更新全局導航索引 [[index]]。

## [2026-11-23] ingest | URL: [[raw/theories/sep-moral-relativism_zh]] | 史丹佛哲學百科（SEP）道德相對主義專題解析
- **操作類型**：權威哲學詞條攝取與核心學派深化 (SEP Ingestion & Theoretical Refinement)
- **來源網址**：`https://plato.stanford.edu/entries/moral-relativism/`
- **發表平台**：Stanford Encyclopedia of Philosophy (SEP)（執筆學者：Chris Gowans 教授）
- **繁中萃取成果**：存入 `raw/theories/sep-moral-relativism_zh.md`。
- **Wiki 聯動升級**：
  - 深化 [[moral-relativism]]：精確建立描述性（DMR）、後設倫理（MMR，Harman/Wong）、規範性（NMR）三階模型；引入分析哲學對相對主義的四大反駁（寬容悖論、道德進步難題、群體界定困境、混淆實然與應然）。
  - 對照破除職場「大家都這樣拿/做」的微腐敗次文化催眠。
  - 更新全局導航索引 [[index]]。

## [2026-11-23] ingest | URL: [[raw/theories/ethics-explainer-moral-absolutism_zh]] | The Ethics Centre 道德絕對主義導讀解析
- **操作類型**：權威理論攝取與四大支柱補強 (Web Ingestion & Core Theory Finalization)
- **來源網址**：`https://ethics.org.au/ethics-explainer-moral-absolutism/`
- **發表機構**：The Ethics Centre (澳大利亞倫理學中心)
- **繁中萃取成果**：存入 `raw/theories/ethics-explainer-moral-absolutism_zh.md`。
- **Wiki 聯動升級**：
  - 深化 [[moral-absolutism]]：系統性梳理絕對道德律的四大來源依據（康德理性義務論、宗教神聖命令、自然法、不可克減之人權）；深入分析「說謊」作為經典試金石與功利論、相對論的三方交鋒；闡述斬斷職場微腐敗「滑坡謬誤（Slippery Slope）」的核心防線功能。
  - 四大哲學學派（康德義務論、羅斯直覺義務論、道德相對主義、道德絕對主義）至此全部完成權威文獻深度鏈結。
  - 更新全局導航索引 [[index]]。

## [2026-11-23] synthesis | 溫暖馬卡龍粉彩版圖文講義生成
- **操作類型**：視覺風格改版與簡報生成 (Pastel UI Redesign & Slide Generation)
- **產出檔案**：`slides/pastel-kantian-handout.html` 與導航中心 `slides/index.html`。
- **嚴格貫徹之設計規範**：
  1. **色彩系統**：溫暖馬卡龍粉彩風格（奶油白底色、櫻花粉、薄荷綠、奶鵝黃、天空藍、柔和紫羅蘭圓角卡片）。
  2. **文字排版**：導入 Google Fonts 可愛日系圓體 `Zen Maru Gothic` 與 `M PLUS Rounded 1c`，字體圓潤親和。
  3. **箭頭防護**：全面避免任何字符箭頭，改以圓形號碼牌（`1`、`2`、`3`）與清晰分塊呈現流程，徹底杜絕 `/right arrow/` 異常字樣。
  4. **專屬插圖**：深度結合專案 `assets/` 中的いらすとや（Irasutoya）手繪貼圖，包括違規塗鴉男、黑心企業勞檢、男護理師、女教授、女工程師等。

## [2026-11-23] synthesis | 圖譜導向三階段工作流落地：粉彩圖文講義正式交付
- **操作類型**：標準化流程實踐 (Graph-Driven Production & Quality Verification)
- **產出檔案**：`slides/pastel-kantian-handout.html`
- **全流程三階段回顧**：
  - **階段一（大綱與圖表規劃）**：梳理 11 頁結構大綱，建立每頁核心傳達目標，指定 10 組無箭頭卡片圖表（階梯卡、雙軌盒、邏輯檢驗盒、天平盒、漏斗盒、防護網）。
  - **階段二（逐頁腳本與視覺規格）**：產出 11 頁精細台詞、嚴謹哲學名詞、無箭頭圖表詳細字樣，並完成 9 幅 Irasutoya 貼圖素材對齊。
  - **階段三（HTML 代碼編譯與品質巡檢）**：
    - 實現溫暖馬卡龍粉彩主題與 Google Fonts 可愛圓體。
    - 通過自動化代碼掃描：確認完全零「/right arrow/」或殘留字串，確認 9 幅圖片路徑 100% 存在無死鏈。

## [2026-11-23] update | Git & GitHub 版本控制協定納入系統規範
- **操作類型**：規範升級 (Schema Enhancement)
- **變更內容**：
  - 在 [[Agents.md]] 增訂第 7 節「Git & GitHub 版本控制協定 (Git & GitHub Automation Protocol)」。
  - 明確定義使用者指令觸發詞法、SOP 五大執行步驟、語意化 Conventional Commit 規範與自動推播機制。

