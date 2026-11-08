# 花蓮 3 天 2 夜自駕遊互動指南 (Hualien Travel Interactive Dashboard)

一個針對台灣花蓮「3 天 2 夜自駕旅行」量身打造的單頁互動式行程規劃網頁。提供路線動態模擬、詳細景點資訊、Google 地圖導航與行車順路性評估。

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Vanilla JS](https://img.shields.io/badge/JavaScript-Vanilla-yellow.svg)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-v3.x-38bdf8.svg)

---

## 🌟 核心特色

1. **向量 SVG 動態地圖**：
   - 採用原生 SVG 繪製花東海岸與台9線／台11線地理動線。
   - 零第三方地圖 API 金鑰限制，無 iframe sandbox 跨域載入阻擋問題，100% 穩定呈現。

2. **自駕路線順序模擬器**：
   - 具備播放、暫停、重置與倍速（1x, 2x, 4x）調整。
   - 紅色自駕車動態沿路線平滑平移，直觀驗證「南向北單行無折返」的省時優勢。

3. **景點詳細卡片 & 一鍵導航**：
   - 收錄停留時間、行車提示、防蚊與停車資訊。
   - 每站均附 Google Maps 即時導航捷徑與隨行打卡 Checkbox。

4. **零後端相依，支援 GitHub Pages**：
   - 全網頁僅由單一 `index.html` 構成，可直接拖拉至瀏覽器離線使用，或一鍵發布至 GitHub Pages。

---

## 📅 行程精華概述 (07:00 台北出發最佳化)

| 天數 | 規劃主題 | 主要路線 / 景點 |
| :--- | :--- | :--- |
| **Day 1** | **海岸樂園之旅** | 台北出發 ➔ 蘇花改 ➔ 遠雄海洋公園 ➔ 夜宿壽豐遠雄悅來大飯店 |
| **Day 2** | **縱谷文創順向遊** | 雲山水夢幻湖 ➔ 貨櫃星巴克 ➔ 吉安慶修院 ➔ 將軍府 1936 ➔ 又一村文創 ➔ 夜宿花蓮福容大飯店 |
| **Day 3** | **蔚藍海岸北返** | 七星潭月牙灣 ➔ 原野牧場海景午餐 ➔ 台泥 DAKA 園區 ➔ 蘇花改返抵台北 |

---

## 🚀 如何使用與部署

### 本地執行
直接在電腦上下載 `index.html`，按兩下用任何現代瀏覽器（Chrome, Edge, Safari, Firefox）開啟即可。

### 部署到 GitHub Pages
1. 在 GitHub 建立一個公開或私人的儲存庫（Repository，例如 `hualien-trip`）。
2. 將 `index.html` 與 `README.md` 上傳至 `main` 分支。
3. 進入儲存庫的 **Settings** ➔ **Pages**。
4. **Source** 選擇 `Deploy from a branch`，Branch 選擇 `main` / `/(root)`，按 **Save**。
5. 稍等 1~2 分鐘，即可獲得公開可訪問的專屬旅行網站！

---

## 🛠️ 技術棧
- **架構**：純前端單檔案 Single Page Web Application (`HTML5`)
- **樣式**：Tailwind CSS (CDN)
- **圖標**：Phosphor Icons
- **繪圖**：向量 SVG、原生 JavaScript 動態動畫（`requestAnimationFrame`）

---

## 📄 授權條款
本專案採用 [MIT License](LICENSE) 授權，歡迎自由修改並客製化您自己的公路旅行行程！
