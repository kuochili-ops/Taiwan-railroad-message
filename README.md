# 𓃥 白六台鐵火車頭 (Taiwan Railway GE E400 3D Simulation)

一個基於 **Three.js** 打造的 3D 鐵道與火車行駛模擬互動網頁應用程式。呈現台鐵 GE E400 火車頭行駛景象，並結合動態看板動態文字繪製技術，提供豐富的文字輪播與戶外視覺景觀展示。

---

## ✨ 專案特色與亮點

* **3D 鐵道與模型動態渲染**：
  * 高精度台鐵 GE E400 3D 機車頭模型（GLTF/GLB 格式）。
  * 平滑無縫的軌道、水泥枕木與道床流動模擬。
  * 精密設計的 3D 戶外大型廣告看板，配備符合力學結構的**背面斜撐鋼架**與金屬外框。
  * 沿途動態生成 Low-Poly 風格造景（小木屋/貨櫃）。

* **動態廣告看板與訊息輪播系統**：
  * **多行訊息無限輪播**：於設定面板輸入多行文字，每一行訊息將自動分配至依序出現的看板上。
  * **動態 Canvas 貼圖技術**：採用 HTML5 Canvas 於記憶體中動態即時繪製，文字更新不卡頓。
  * **Google Fonts 整合**：預載 Google 免費中文字型（**思源黑體**、**思源宋體**、**jf open 粉圓體**），文字風格隨心切換。
  * **外觀高度自訂**：可自由自訂文字顏色、看板背景底色、字型與字型大小。

* **使用者互動體驗**：
  * 支援手機與電腦端手勢操作（單指/滑鼠旋轉視角、雙指/滾輪縮放與平移）。
  * 可收合式控制面板，操作直覺不遮擋畫面。

---

## 🛠️ 使用技術 (Tech Stack)

* **前端核心**：HTML5, CSS3, JavaScript (ES6+)
* **3D 繪圖引擎**：[Three.js (r128)](https://threejs.org/)
* **控制與載入外掛**：
  * `OrbitControls.js`（鏡頭軌道控制）
  * `GLTFLoader.js`（3D 模型載入器）
* **網路字型**：Google Fonts API (`Noto Sans TC`, `Noto Serif TC`, `Zen Maru Gothic`)

---

## 📁 檔案結構

```text
.
├── index.html                           # 主頁面程式碼 (包含 3D 邏輯與 CSS 樣式)
├── taiwan_railway_ge_e400__interior.glb  # 台鐵 GE E400 機車頭 3D 模型
├── storagecontainer_lowpoly.glb         # 沿途景觀小木屋/貨櫃 3D 模型
└── README.md                            # 專案說明文件
