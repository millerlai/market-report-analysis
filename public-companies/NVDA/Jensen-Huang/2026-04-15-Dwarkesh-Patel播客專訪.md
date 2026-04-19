# 2026-04-15 Dwarkesh Patel 播客專訪

- **發言者**：黃仁勳（Jensen Huang）
- **公司 / Ticker**：NVIDIA / NVDA
- **職稱**：創辦人、總裁暨執行長
- **發言日期**：2026-04-15（原始播客發布日期）
- **發言場合**：Dwarkesh Patel 播客（Dwarkesh Podcast）
  - 長度約 2 小時，無腳本、無讀稿機
  - 中文媒體轉述於 2026-04-16（鉅亨號等）
- **訪問者 / 主持人**：Dwarkesh Patel（美國知名科技／AI 議題播客主持人，以高資訊密度、不迴避尖銳提問聞名）
- **來源連結**：
  - ✅ 一手／高可信：[Dwarkesh Podcast 官方文章頁](https://www.dwarkesh.com/p/jensen-huang)
  - ✅ 一手／高可信：[Apple Podcasts](https://podcasts.apple.com/us/podcast/jensen-huang-tpu-competition-why-we-should-sell-chips/id1516093381?i=1000761582962)
  - ✅ 一手／高可信：[YouTube 影片](https://www.youtube.com/watch?v=wzxcpdc5opA)
  - ◯ 二手／中可信：[鉅亨號中文整理（RexAA，2026-04-16）](https://hao.cnyes.com/post/242581)
  - ◯ 二手／中可信：[Zvi Substack 評論](https://thezvi.substack.com/p/on-dwarkesh-patels-podcast-with-nvidia)
  - ◯ 二手／中可信：[Techloy 整理](https://www.techloy.com/jensen-huang-on-dwarkesh-patel-podcast-8-revelations-on-anthropic-china-and-nvidias-roadmap/)

## 核心訊息
1. **供應鏈護城河**：Nvidia 已透過上千億美元採購承諾綁定 TSMC、Micron 等上游產能，護城河已延伸至供應鏈深處
2. **CUDA 生態系統**：數億顆 GPU 裝機量、遍佈所有雲端，是 Nvidia 最大財富
3. **反對嚴格出口管制**：中國以規模彌補性能差距，全面限制反而會迫使中國自建計算架構並輸出全球南方，長期傷害美國技術領導力
4. **產品路線圖承諾**：Vera Rubin（2026）→ Vera Rubin Ultra（2027）→ Feynman（2028），每年新架構、token 成本降一個數量級
5. **投資基礎模型公司的策略轉向**：承認過去未意識到 OpenAI、Anthropic 難以獲得風投級資金，現在主動投資以鎖定客戶關係（OpenAI 約 300 億、Anthropic 約 100 億美元）

## 對自家公司的論述

### 營運現況
- 在五大超大規模雲廠商的收入佔比約 60%
- 與 TSMC、Micron 等供應商累計上千億美元採購承諾（SemiAnalysis 估可達 2500 億美元）
- TSMC N3 節點目前 60% 產能給 AI，2027 年將升至 86%

### 產品 / 技術進展
- **Hopper**：當前仍為大模型主要訓練架構
- **Blackwell**：已推出，相較 Hopper 效能提升 30-50 倍
- **Vera Rubin**：2026 年推出
- **Vera Rubin Ultra**：2027 年推出
- **Feynman**：2028 年推出
- **NVLink、NVLink Switch、Spectrum-X**：網路與計算解除安裝技術
- 最近納入 Groq 技術（高速推理 Token）
- 摩爾定律年度進步約 25%

### 財務展望 / 財測
- 本次訪談未提供季度／年度具體財測數字
- 透過採購承諾金額間接暗示未來收入規模

### 資本配置
- 對 OpenAI 投資約 300 億美元
- 對 Anthropic 投資約 100 億美元
- 對 CoreWeave、Nscale、Nebius 等新雲廠商提供支援
- 對 TSMC、Micron 等上游進行大規模投資

### 風險與挑戰
- **能源**：黃仁勳主動提出「最讓我擔心的是能源政策阻止能源擴展」，承認晶片 2-3 年可解決但能源擴張更慢
- **出口管制政策**：被訪問者主動追問下才深入討論；黃仁勳反對全面管制
- **ASIC 競爭（Google TPU、AWS Trainium）**：黃仁勳主動淡化，稱「Anthropic 只是 ASIC 增長的獨特個例而非趨勢」

## 對產業 / 市場的論述

### 產業趨勢判斷
- AI 生態分五層：能源 → 晶片 → 軟體 → 算法 → 應用，每層都必須成功
- 通用可編程架構（GPU）優於專用 ASIC，因新算法（注意力機制、混合狀態空間模型）需要靈活硬體
- 加速運算的未來超越 AI 本身：分子動力學、資料處理、流體力學等廣闊市場
- 「你希望一個行業的瞬時需求大於總供應」——將供應吃緊解讀為健康訊號

### 對競爭對手的評論
- **Google TPU**：「沒有任何一個平台能向我展示出比我們更好的性能與 TCO 比」、「TPU 不來測且 Trainium 也不來測」MLPerf 基準
- **OpenAI 自造 Titan 加速器、使用 AMD**：承認「他們絕大部分算力還是跑在輝達上」
- **華為**：作為出口管制議題的核心，警示 DeepSeek 若被迫與華為硬體深度綁定將削弱美國技術堆疊全球優勢

### 對客戶 / 供應鏈的觀察
- **供應鏈信任關係**：「輝達和台積電沒有簽署法律合同但總有一些粗略的公平」
- **定價原則**：從不採用價高者得模式，「如果我報了一個價那就是那個價」、「需求飆升價格依然穩定」
- **CoreWeave 等新雲**：「如果我們不支援 CoreWeave 存在，這些新雲、這些 AI 雲就不會存在」

### 對總體經濟 / 政策的看法
- 全球 AI 研究人員中國佔近 50%
- 對出口管制政策的具體批評：
  - 「極端的出口管制政策十分幼稚」
  - 「主動放棄全球第二大市場不會讓美國長期在晶片層、在計算堆疊中贏得技術競賽」
  - 呼籲「分寸、成熟而不是非黑即白」的政策
- 警告若美國放棄，中國將基於開源標準向全球南方輸出，美國在 AI 生態標準競爭將陷入被動

## 具體承諾 / 預測（待追蹤）

- [ ] **Vera Rubin 架構推出** — 目標時程：2026 年內，驗證方式：Nvidia 官方發表、財報揭露
- [ ] **Vera Rubin Ultra 架構推出** — 目標時程：2027 年，驗證方式：同上
- [ ] **Feynman 架構推出** — 目標時程：2028 年，驗證方式：同上
- [ ] **每代 token 成本下降一個數量級** — 目標時程：每年，驗證方式：比對各代定價與實際推理成本（獨立 benchmark）
- [ ] **Blackwell 相較 Hopper 效能提升 30-50 倍** — 目標時程：已推出，驗證方式：MLPerf、獨立第三方 benchmark
- [ ] **TSMC N3 節點 AI 佔 86%（2027）** — 目標時程：2027，驗證方式：TSMC 財報、SemiAnalysis 等研究機構追蹤
- [ ] **與上游供應商採購承諾達上千億美元** — 目標時程：未來數年，驗證方式：Nvidia 10-K／10-Q CapEx 與採購義務揭露
- [ ] **Anthropic 使用 TPU 是「獨特個例而非趨勢」** — 驗證方式：後續觀察其他大型 AI 實驗室是否轉向 ASIC

## 回答風格觀察
- **中國議題**：被 Dwarkesh Patel 追問時出現明顯情緒反應，語氣從 keynote 式的自信轉為激動；多家媒體（ChinaTechNews 等）以「Jensen Huang loses his cool」為標題報導
- **迴避／淡化**：對 Google TPU 的威脅採取主動淡化策略（「獨特個例而非趨勢」、「TPU 不來測 MLPerf」），而非正面回應具體性能比較
- **承認失誤**：罕見地主動承認「我的失誤是我沒有深刻意識到沒有風投會投 50 到 100 億美元到一個 AI 實驗室」，顯示在 OpenAI/Anthropic 投資議題上願意自我檢討
- **強化可信度措辭**：多次使用「你可以像相信時鐘一樣相信輝達」、「I truly believe」等句式
- **善用類比**：將 Nvidia 與供應商關係類比為「粗略的公平」，將產業瞬時供需失衡描述為健康訊號

## 當時的公司 / 產業背景
- 2026 年 4 月：AI 基礎設施投資熱潮持續，但市場對 AI 資本支出的可持續性、ASIC 競爭、中國出口管制議題的辯論同步升溫
- Dwarkesh Patel 引用 Anthropic CEO Dario Amodei 近期言論作為對比
- 此次專訪發生在美國政府對 AI 晶片出口中國的政策討論關鍵期
- 本次訪談具體股價位置、季度財報前後時序待補

## 利益衝突提醒
本場發言中**最需要保留懷疑**的論點：

1. **「Anthropic 使用 TPU 只是獨特個例而非趨勢」**
   - 黃仁勳作為 GPU 陣營 CEO，對 ASIC 崛起趨勢的否認具直接競爭動機
   - Anthropic 已公開承諾大規模使用 Google TPU，是否真為「個例」需持續觀察
2. **「反對出口管制」的政策論述**
   - Nvidia 在中國市場的商業利益與黃仁勳的政策立場高度一致
   - 其「放棄市場反而害美國」的論點需區分：客觀戰略分析 vs. 商業利益包裝
3. **「OpenAI 絕大部分算力跑在 Nvidia 上」**
   - 此為有利於 Nvidia 敘事的片面陳述；未明確提供比例數字，需交叉驗證 OpenAI 實際 AMD 採購量與 Titan 部署進度
4. **「TPU / Trainium 不來測 MLPerf」**
   - 暗示對手不敢接受公開比較，但 Google 與 AWS 有其他內部性能資料；此論述具引導性
5. **「摩爾定律年度進步約 25%」的數字**
   - 用以凸顯自家架構進步（Hopper→Blackwell 30-50 倍）的相對優勢；但兩者非同一評估框架
6. **「能源是真正瓶頸」**
   - 將供應限制歸因於能源而非自家供應承諾，有助於降低市場對 Nvidia 未來供給緊俏負評的預期

## 後續追蹤
- 待 Vera Rubin 發表會後回填實際規格、效能、定價
- 待 Nvidia 2026 年 Q2／Q3／Q4 財報揭露實際 CapEx 與採購義務，驗證上千億美元採購承諾
- 持續追蹤 Anthropic、OpenAI 等大型客戶的 ASIC vs. GPU 採購比重變化
- 追蹤美國對中國 AI 晶片出口政策的後續演變，評估黃仁勳公開立場是否影響政策走向
- 關注中國市場（華為、DeepSeek、中芯國際）的技術進展，驗證黃仁勳「規模彌補性能」論點

## 備註
- 播出後數日內多家深度分析文章發表，顯示本次訪談在 AI／投資圈具廣泛影響力：
  - [Zvi Substack 長文分析](https://thezvi.substack.com/p/on-dwarkesh-patels-podcast-with-nvidia)
  - [LessWrong 社群討論](https://www.lesswrong.com/posts/RBBChvuPHP7LfWyME/on-dwarkesh-patel-s-podcast-with-nvidia-ceo-jensen-huang)
  - [Daniel Miessler 評論](https://danielmiessler.com/blog/jensen-vs-dwarkesh-china-chips)
  - [Dave Friedman Substack 摘錄](https://davefriedman.substack.com/p/jensen-huang-on-anthropic-openai)
- 鉅亨號中文版本標題「逼 DeepSeek 與華為深度繫結，這對美國太可怕了」屬編輯方下標，原始訪談中此論點為黃仁勳論述的一部分，但並非全篇核心；閱讀時應以原始播客為準
- 中文轉述中的部分數字（如「2500 億美元」）為 SemiAnalysis 的外部估計，非黃仁勳本人發言，需區分
