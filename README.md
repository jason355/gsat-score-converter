
# 🎓 學測級分跨年度換算工具 (GSAT Score Converter)

一個基於大考中心 (CEEC) 原始數據，利用累積百分位數進行換算的工具。特別優化了多考科組合與跨年度矩陣對照功能。

<div style="text-align: center;">
    <a href="https://jason355.github.io/gsat-score-converter/" target="_blank">
    <img src="https://img.shields.io/badge/馬上試試-2563eb?style=for-the-badge&color=blue" alt="GitHub Pages">
    </a>
</div>


## 功能 

- **換算**：不只是級分加減，而是對齊大考中心原始「累積百分比」，確保換算結果符合該年度考題難易度。
- **全年度矩陣對照**：一鍵查看你的成績在歷年（111-115年）分別對應的級分，方便落點分析。
- **2-4 科組合計算**：支援真實的組合累積數據（如：國+英+數A），而非單科簡單相加。
- **PDF 匯出**：自動排版為 A4 橫式報表，適合學生與家長列印討論志願。

## 🛠️ 技術細節 (Technical Stack)

- **Frontend**: Vanilla JavaScript (ES6+), HTML5, CSS3.
- **Data Structure**: JSON 格式儲存歷年大考中心原始人數百分比資料。
- **Responsive Design**: 使用 CSS Sticky Position 與 Media Queries 達成跨裝置一致體驗。
- **Algorithm**: 採用「最接近百分位數演算法」，並落實「從優原則」（若差距相同則顯示較高級分）。



## 🚀 如何使用 (How to Use)

1. **選擇來源年份**：選擇你參加考試的年份（例如 115 年）。
2. **輸入成績**：填入你的各科級分。
3. **選擇目標**：選擇特定的目標年份，或選擇「全年度對照矩陣」。
4. **查看結果**：系統會自動標示出換算後的級分與對應的百分比。
5. **匯出 PDF**：點擊綠色按鈕，即可獲得一份格式整齊的對照表。

## 📈 數據來源 (Data Source)

本工具之原始數據均取自 [大學入學考試中心 (CEEC)](https://www.ceec.edu.tw/xmdoc?xsmsid=0J018604485538810196) 公佈之各科及組合級分人數累計表。


---
*Disclaimer: 本工具僅供參考，實際分發結果請以當年度甄選委員會公佈為準。*