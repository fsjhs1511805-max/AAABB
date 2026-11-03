# 🎯 Aim Mastery Hub - 一頁式瞄準學習歷程與 2D 電競對決平台

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![HTML5 / Canvas](https://img.shields.io/badge/HTML5-Canvas-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-06B6D4.svg)](https://tailwindcss.com/)
[![Web Audio API](https://img.shields.io/badge/Audio-Web%20Audio%20API-green.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)

> 一個專為 FPS / TPS 射擊遊戲新手打造的**一頁式遊戲化學習平台與 2D 擬真槍戰訓練場**。整合了系統化學習路線圖、eDPI 計算工具以及具備動態雷射彈道的 AI 對射實戰系統。

---

## 💡 開發緣由與動機 (Motivation & Background)

許多剛接觸第一人稱射擊 (FPS) 或第三人稱射擊 (TPS) 遊戲的玩家，常面臨以下痛點：
1. **「人體描邊」與瞄準瓶頸**：遇到敵人群聚或高速移動時容易慌亂失準。
2. **缺乏系統化教學**：不了解預瞄 (Pre-aiming)、跟槍 (Tracking) 與壓槍 (Recoil Control) 的運作原理。
3. **訓練軟體枯燥**：傳統打靶軟體缺乏實戰對射的緊張感與急停躲避彈道的要求。

為了讓射擊遊戲新手能夠**「從觀念建立到肌肉記憶養成」**，我們開發了 **Aim Mastery Hub**——將理論知識、靈敏度校正工具與動態 AI 對射模擬器整合至單一網頁中，打造零門檻、即開即練的沉浸式學習體驗。

---

## 🗺️ 玩家學習歷程 (Learning Journey Roadmap)

本平台設計了四階段的漸進式學習路線，引導玩家一步步掌握瞄準核心：

```
[Phase 1: 姿勢與 eDPI] ➔ [Phase 2: 甩槍肌肉記憶] ➔ [Phase 3: 動態跟槍] ➔ [Phase 4: 實戰 AI 對射]
```

* **Phase 1: 靈敏度與姿勢校正**
  * 透過內建 **eDPI 計算器**，幫助玩家找到適合「手臂流」或「手腕流」的最佳滑鼠靈敏度。
* **Phase 2: 靜態標靶與甩槍 (Flick Shooting)**
  * 培養準心從原點快速移至目標點的第一發爆頭 (First-Bullet) 直覺。
* **Phase 3: 動態追蹤與跟槍 (Tracking)**
  * 練習將準心穩定鎖定在橫向移動或平移閃避的敵方目標上。
* **Phase 4: 實戰 AI 壓槍對射 (Duel Arena)**
  * 進入 2D 對決戰場，面對具備動態走位與雷射彈道攻擊的 AI Bots，同步鍛鍊預瞄、急停與擴散壓槍。

---

## ✨ 核心特色與功能 (Key Features)

### 1. ⚔️ 2D 雷射對射戰場 (Interactive Duel Arena)
* **動態曳光彈道 (Tracer Bullets)**：實時繪製敵我雙方的紅色/藍色雷射彈道，可清晰觀察彈道軌跡與槍口擴散。
* **AI 智能敵機**：提供 5 個難度遞增的關卡，AI Bots 具備自動走位 (Strafing)、預瞄與不同射速/傷害設定。
* **畫面與打擊回饋**：包含槍口火花 (Muzzle Flash)、擊中火花、浮動傷害數字 (Damage Numbers) 與受傷螢幕震動 (Screen Shake)。

### 2. 📊 實時戰績評估與 S+ 評級系統
* 對決結束後自動統計並結算：
  * **命中率 (Accuracy %)**
  * **爆頭率 (Headshot %)**
  * **最大連擊數 (Max Combo)**
  * **傷害輸出 / 承受比例 (DPS & Damage Ratio)**
* 根據表現頒發 **S+ / S / A / B / C / D** 電競評級與改進建議。

### 3. ⚙️ 豐富的客製化設定
* **多種武器選擇**：戰略手槍 (Pistol)、突擊步槍 (Rifle)、重型狙擊槍 (Sniper)。
* **準心自訂**：支援圓點 (Dot) 與動態擴散十字 (Dynamic Crosshair)，並可隨意切換主題顏色。
* **Web Audio API**：免載入外部音效檔，由瀏覽器原生合成開火、擊中打擊聲與受傷警報聲。

---

## 🛠️ 技術架構 (Tech Stack)

* **前端框架/樣式**：HTML5, Tailwind CSS (CDN)
* **繪圖與渲染引擎**：HTML5 Canvas 2D API
* **音效合成**：Web Audio API
* **圖標庫**：FontAwesome 6.4

---

## 🚀 快速開始 (Quick Start)

本專案為無後端依賴的純前端一頁式 Web 應用，無需安裝任何包管理器或伺服器環境。

1. **複製專案庫 (Clone Repository)**
   ```bash
   git clone https://github.com/your-username/aim-mastery-hub.git
   ```
2. **執行專案**
   直接用瀏覽器開啟 `index.html` 即可開始遊玩與練習！

---

## 🎮 遊戲操作說明 (Controls)

| 操作 / 按鍵 | 功能說明 |
| :--- | :--- |
| **滑鼠移動** | 控制準心位置與方向 |
| **滑鼠左鍵** | 開火 / 射擊 |
| **Space (空白鍵)** | 快速開始 / 暫停對決 |
| **Esc** | 開啟/關閉設定選單 |

---

## 📄 授權條款 (License)

本專案採用 [MIT License](LICENSE) 條款授權。歡迎自由修改、分發與用於個人學習。
