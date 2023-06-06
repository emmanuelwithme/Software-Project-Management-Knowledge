# 6/6 期末考筆試範圍

本次期末考筆試的範圍包含以下四個主題簡報檔內容：

1. CH1-破冰課程簡介與第1章專案管理導論
2. CH2,3-專案管理流程
3. SW Processes-230314
4. 0411-敏捷思維與實踐-軟體專案管理

考試共計包含12題簡答題，所有題目都可以在這四份簡報檔中找到。請同學們仔細學習和準備這些主題的內容，以確保在考試中獲得好成績。

祝大家順利通過考試！

# 軟體專案管理期末考重點

## PDCA循環
PDCA循環又稱為「戴明循環」，包含規劃(`Plan`)、執行(`Do`)、檢討(`Check`)、改善(`Act`)四個活動。持續改善是PDCA重點精神。

## 專案「啟始階段」
專案流程中最重要的階段應是「啟始階段」，約有80%的專案都是在此種下失敗的種子。

專案啟始主要工作:
1. 蒐集與確認專案目標、需求與範疇。
2. 尋求利害關係人的支持。
3. 發展專案核准證明(專案章程)。
4. 啟動會議(Kick-off Meeting)。

## 專案規畫
1. 發展專案管理計畫書/專案工作計畫書(整合管理)。
2. 專案基準(專案管理計畫書、軟體需求規格書)。

## 專案監控階段
目的: 在預算與範疇內準時完成。

重點:
1. 專案進度。
2. 專案資源。
3. 專案預算。

## 專案結案階段
暫停、終止與結束。

1. 專案交付。
2. 建立知識庫。
3. 績效考核。

## Software Process
A structured set of activities.

## Plan-driven processes 相對於 Agile processes
Plan-driven processes: 全部都先計劃好。
Agile: 漸增式的計劃，planning is incremental and it is easier to change the process to reflect changing customer requirements.
大部分專案都包含Plan-driven, Agile方法。

## Process activities
1. Specifying.
2. Designing.
3. Implementing.
4. Testing.

### 1. Software specification
- 需求獲取和分析。
- 要求規範。
- 需求驗證。

### 2. Software Design
- Architectural: overall structure of the system, the principal components.
- Database.
- Interface.
- Component.

### 3. Software implementation
- Program.
- Debug.

### 4. Software testing
Verification and validation:
- Verification: 是否按照規格。
- Validation: 是否符合顧客需求。

Testing stages:
- Component test.
- System test.
- Customer test.

## Software process models
- Waterfall: Plan-driven model.
- Incremental: Plan-driven or Agile.
- Integration and configuration: 現有元件組裝而成。

## 各種生命週期模型的困難
瀑布模型: 按照順序進行，每個階段完成後才能進入下一個階段。這樣會造成難以變更需求。

增量式開發的兩個問題: 管理者無法清楚地了解開發的進度和成果、程式重構困難。

可重複使用的軟體類型:
1. 獨立應用系統（有時稱為COTS）: 如會計系統或資料庫管理系統。
2. 封裝的物件：（如.NET或J2EE）。
3. 網路服務: API。

## 降低重工成本
1. 反覆確認需求。
2. 可以容忍變更。

Coping with changing requirements:
1. System prototyping.
2. Incremental delivery.

## 敏捷宣言
- Mindset: 軟體開發唯一不變的是「變」。
- 4 Value:
  1. 個人與互動 重於 流程與工具。
  2. 可用的軟體 重於 詳盡的文件。
  3. 與客戶合作 重於 合約協商。
  4. 回應變化 重於 遵循計劃。

## 12項敏捷原則
1. 交付有價值的軟體。
2. 歡迎需求變化。
3. 經常交付可用軟體。
4. 業務和開發合作。
5. 建立激勵可信的團隊。
6. 直接溝通。
7. 可工作軟體是進度。
8. 持續開發和交付。
9. 追求卓越和簡潔設計。
10. 簡單性至關重要。
11. 自組織團隊有效。
12. 定期反思和優化。

## XP(eXtreme Programming) 10個實踐
1. 增量計劃: 根據時間和優先級確定需求，分解為任務。
2. 小型交付: 首先開發提供商業價值的最小功能集。
3. 簡單設計: 滿足當前需求而不過度設計。
4. 先測試開發: 先寫測試再實現功能。
5. 重構: 持續改進代碼結構。
6. 雙人編程: 開發者成對工作，互相檢查和支持。
7. 共同擁有: 開發者共同負責所有代碼，可以自由修改。
8. 持續整合: 任務完成後立即整合，確保所有單元測試通過。
9. 可持續節奏: 避免過度加班，保持生產力和代碼品質。
10. 現場客戶: 客戶代表全職支援團隊，提供需求和反饋。

## Scrum專案管理方式:

1. **Product backlog**:
   - 待開發功能清單、優先重要性排序、User Story(As a (role) I want (feature) So that (benefit))
   - Product Owner創建與維護
   - 每次Sprint不斷被修正與更新

2. **Sprint Planning & Sprint Backlog**:
   - 決定這次Sprint要從Product backlog中挑出哪些項目放進此次Sprint Backlog
   - 並列出針對每㇐個Sprint backlog User Story更詳細的tasks(要做的GUI, Back-end service, DB structure, Unit test, Function test......)
   - 依照每個task難度估計需要投入的工時
   - 最後製作燃盡圖(Burn-down chart)來管理進度，Burn-down chart的橫軸是時間(Days)，縱軸是task數量或是完成此次sprint的tasks剩餘總工時

3. **Scrum工作領取/指派**
4. **每日站立會議**:
   - 15分鐘以內結束，只有Scrum Master, Team Members參加，Product Owner不用參加
   - 要討論3個問題: 昨天你做了甚麼? 、今天你要做甚麼? 、有甚麼困難需要幫助?
   - 這是Team Members彼此之間狀態同步，不是對Scrum Master的進度報告

5. **Sprint Review (展示和驗收)**:
   - 全部人都要參加
   - Demo這次Sprint的成果
   - 如果不盡理想，可以把要修改的功能、修改的需求放到Product Backlog (Refine Product Backlog )

---

以上就是軟體專案管理的期末考重點。請注意，這僅為摘要，建議參考相關教材和課堂筆記以獲得更詳細的內容和理解。
