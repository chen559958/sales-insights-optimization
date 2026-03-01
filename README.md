# 瓦斯店營業數據分析與優化 (Sales Insights Optimization)

這個專案使用 Python 針對瓦斯店的原始營業數據進行深度分析，旨在找出銷售趨勢、優化營運流程，並針對客戶行為提供具體的商業建議。

## 📊 專案重點
- **數據處理**：使用 Pandas 進行資料清洗，處理缺失值與格式轉換。
- **核心分析**：探討淡旺季銷售差異、客戶回購週期。
- **視覺化呈現**：使用 Matplotlib / Seaborn 產出關鍵績效指標 (KPI) 圖表。

## 📂 檔案結構
- `data`: 存放資料清洗及整理後的客戶檔案。
- `scripts`: Python 分析腳本。
- `nvisualizations`: 完整圖表。
- `report`: 優化建議報告。

## 📈 關鍵分析圖表
<img width="2966" height="1764" alt="Annual Total Sales" src="https://github.com/user-attachments/assets/8b574269-d851-4a42-b67f-a7c6141b980f" />

<img width="4468" height="1761" alt="Monthly Sales Trends" src="https://github.com/user-attachments/assets/d485021b-0d0d-4732-95c9-e9bd370a0040" />


1. **銷售趨勢分析**：顯示月營收變化，確認淡旺季週期。
2. **客群分類**：新舊客戶的購買量與留存率。
3. **配送效率分析**：針對瓦斯配送時間與熱點區域進行評估。

## 💡 數據洞察與優化建議

### 1. 數據發現 (Insights)
- **季節性影響**：[例如：冬季需求量比夏季高出 30%]。
- **客戶行為**：[例如：約有 40% 的客戶在固定周期內未回購，存在流失風險]。

### 2. 營運建議 (Recommendations)
- **庫存管理**：根據預測模型，在旺季前兩週提前部署瓦斯量並安排人力配置。
- **精準行銷**：針對回購率較高之客戶，配置相關優惠策略，（如：提供續購優惠）。
- **配送優化**：確認區域分布位置，就同區域之客戶可同步進行配送。
#### 📑 分析報告
完整的分析結果與優化建議，請點擊下方連結查看：
<a href="report/Sales Analysis and Recommendations.pdf">
  <img src="https://img.shields.io/badge/查看分析報告-Click%20Here-blue?style=for-the-badge&logo=github" alt="Report">
</a>

## 🛠 使用工具
- **語言**：Python 3.x
- **套件**：Pandas, NumPy, Matplotlib, Seaborn

## 🏁 結語
本專案透過 Python 實作自動化數據清洗與分析，成功將瓦斯店繁雜的原始報表轉化為具備商業價值的視覺化洞察。透過這套分析邏輯，店家能更精準地掌握營運現狀並降低庫存風險。
