# 金寶貝健康問卷模組（M04）專案規劃

## 1. 專案個別組員的任務

| 職位 / 角色 | 姓名 | 主要負責任務 | 
| :--- | --- | :--- |
| **系統分析與專案管理(SA/PM)** | 林家誼 | 1. 訪談健康問卷需求與設計跳轉邏輯<br>2. 管控專案進度與團隊溝通 | 
| **前端開發工程師(Frontend)** | 賴湘詅 | 1. 開發問卷動態表單與介面動畫<br>2. 實作問卷結果分析圖表元件 | 
| **後端與測試工程師(Backend/QA)** | 蔡可心 | 1. 設計問卷資料庫與建置計分引擎 API<br>2. 執行系統整合測試與資安驗證 | 

---

## 2. 專案甘特圖 (Gantt Chart)

專案執行期間為 **10/01 至 12/21（共 12 週）**：

| 階段 / 週次 | 任務內容 | 負責角色 | 預計時間 |
| :--- | :--- | :---: | :---: |
| **Phase 1 (W1-W2)** | 需求分析、問卷邏輯規畫與 DB Schema 設計 | SA/PM | 10/01 - 10/14 |
| **Phase 2 (W3-W6)** | 前端問卷 UI 開發與後端計分引擎 API 寫作 | FE, BE | 10/15 - 11/11 |
| **Phase 3 (W7-W8)** | 前前後端 API 串接與資料加密安全性實作 | FE, BE | 11/12 - 11/25 |
| **Phase 4 (W9-W10)** | 全系統功能測試、壓測與 UAT 驗收 | BE/QA | 11/26 - 12/09 |
| **Phase 5 (W11-W12)** | 生產環境部署上線與專案結案文件 | 全員 | 12/10 - 12/21 |

```mermaid
gantt
    title 金寶貝健康問卷模組（M04）專案甘特圖
    dateFormat  YYYY-MM-DD
    axisFormat  %m/%d
    section 階段一：需求與規劃
    需求分析與邏輯規畫        :a1, 2026-10-01, 2026-10-14
    section 階段二：核心開發
    前端問卷 UI 與圖表開發    :a2, 2026-10-15, 2026-11-11
    後端問卷引擎與 API 開發    :a3, 2026-10-15, 2026-11-11
    section 階段三：系統整合
    前後端 API 串接與資安實作  :a4, 2026-11-12, 2026-11-25
    section 階段四：測試與驗收
    系統整合測試與 UAT 驗收    :a5, 2026-11-26, 2026-12-09
    section 階段五：部署與上線
    生產環境部署與結案交付    :a6, 2026-12-10, 2026-12-21


    style A fill:#ffe6e6,stroke:#ff0000,stroke-width:2px
    style B fill:#ffe6e6,stroke:#ff0000,stroke-width:2px
    style D fill:#ffe6e6,stroke:#ff0000,stroke-width:2px
    style F fill:#ffe6e6,stroke:#ff0000,stroke-width:2px
    style G fill:#ffe6e6,stroke:#ff0000,stroke-width:2px
