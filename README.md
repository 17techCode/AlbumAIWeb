# AlbumAI Website

**Transform what you see to what you say.**

這是 AlbumAI 的官方網站，展示我們革命性的 AI 驅動照片轉文字應用程式。

## 🌐 網站概述

AlbumAI 網站是一個現代化的響應式網站，採用 Apple 設計語言，展示我們的核心產品功能和價值主張。

### 核心理念
- **Photos to Words** - 將照片瞬間轉化為有意義的文字內容
- **Search Your Memories** - 讓每張照片都能被搜尋和發現
- **AI-Powered Innovation** - 運用先進 AI 技術提升用戶體驗

## 📁 文件結構

```
AlbumAIWeb/
├── index.html              # 主頁 - 產品介紹和功能展示
├── PrivacyPolicy.html      # 隱私政策 - 符合 iOS 應用內版本
├── TermsOfService.html     # 服務條款 - 符合 iOS 應用內版本
├── img/                    # 圖片和影片資源
│   ├── logo.png           # 網站 Logo
│   ├── icon.png           # 網站圖標
│   ├── slideshow1-4.png   # 應用截圖輪播
│   ├── Experience.mp4     # 功能展示影片
│   └── upgradePremium.mp4 # Premium 升級影片
├── .DS_Store              # macOS 系統文件
└── README.md              # 本文件
```

## ✨ 主要功能

### 🏠 首頁 (index.html)
- **雙語支援**: 英文 / 正體中文切換
- **響應式設計**: 完美適配桌面和手機
- **應用截圖輪播**: 展示 AlbumAI 的核心功能
- **功能介紹**: 六大核心功能詳細說明
- **影片展示**: 自動播放的功能演示影片
- **Premium 推廣**: 高級版功能和優勢展示

### 📋 法律文件
- **隱私政策**: 詳細的數據保護和隱私條款
- **服務條款**: 完整的使用條款和限制說明
- **合規性**: 符合 GDPR、CCPA 等國際法規要求

## 🎨 設計特色

### 視覺設計
- **Apple 風格**: 採用 Apple 設計語言和色彩系統
- **現代化介面**: 清晰的層次結構和視覺效果
- **一致性**: 所有頁面保持統一的設計風格

### 技術特點
- **純 HTML/CSS/JavaScript**: 無需額外框架，載入速度快
- **SEO 優化**: 完整的 meta 標籤和語義化結構
- **無障礙設計**: 支援鍵盤導航和螢幕閱讀器
- **跨瀏覽器相容**: 支援所有主流瀏覽器

## 🌍 多語言支援

網站支援以下語言：
- **English** (預設)
- **正體中文**

語言切換功能：
- 右上角語言切換按鈕
- 本地儲存記住用戶偏好
- 動態更新頁面標題和 meta 描述

## 📱 響應式設計

### 桌面版 (1200px+)
- 完整的導航選單
- 雙欄佈局展示內容
- 大尺寸影片和圖片展示

### 平板版 (768px - 1199px)
- 適中的內容佈局
- 保持功能完整性

### 手機版 (< 768px)
- 單欄佈局
- 隱藏導航選單
- 優化的觸控體驗

## 🎬 影片功能

### 自動播放設定
所有影片都配置為：
- `autoplay` - 自動播放
- `muted` - 靜音播放（符合瀏覽器政策）
- `loop` - 無限循環
- `playsinline` - iOS 內聯播放

### 影片內容
- **Experience.mp4**: 展示 AlbumAI 的核心功能和使用流程
- **upgradePremium.mp4**: 介紹 Premium 版本的優勢和功能

## 🔗 重要連結

### 網站資訊
- **網域**: albumai.net
- **聯繫信箱**: 
  - 一般詢問: hello@albumai.net
  - 技術支援: support@albumai.net
  - 法律事務: service@albumai.net

### iOS 應用資訊
- **Bundle Identifier**: AlbumAI.ai
- **平台**: iOS 16.0+
- **App Store**: [即將上線]

## 🛠 技術規格

### 開發環境
- **HTML5**: 語義化標記
- **CSS3**: 現代化樣式和動畫
- **JavaScript ES6+**: 互動功能和語言切換
- **無框架**: 純原生技術實現

### 效能優化
- **圖片優化**: 適當的圖片格式和大小
- **CSS 最佳化**: 合併樣式，減少重複
- **JavaScript 最佳化**: 最小化 DOM 操作
- **載入策略**: 關鍵資源優先載入

## 📊 SEO 和分析

### SEO 優化
- 完整的 meta 標籤
- Open Graph 社群分享標籤
- 語義化 HTML 結構
- 適當的標題層級

### 分析追蹤
- 準備整合 Google Analytics
- 用戶行為追蹤點設置
- 轉換率優化準備

## 🔄 更新日誌

### v1.0.0 (2025.01)
- ✅ 初始網站建立
- ✅ 雙語支援實現
- ✅ 響應式設計完成
- ✅ 法律文件整合
- ✅ 影片自動播放設定
- ✅ iOS 應用資訊同步

## 📝 維護指南

### 內容更新
1. **應用截圖**: 定期更新 `img/slideshow1-4.png`
2. **功能影片**: 根據應用更新替換影片內容
3. **法律文件**: 與 iOS 應用保持同步

### 技術維護
1. **瀏覽器相容性測試**: 定期測試主流瀏覽器
2. **效能監控**: 監控載入速度和用戶體驗
3. **安全性檢查**: 定期檢查安全性問題

## 🚀 部署說明

### 靜態網站部署
網站可部署到任何靜態網站託管服務：
- **Netlify** (推薦)
- **Vercel**
- **GitHub Pages**
- **AWS S3 + CloudFront**

### 部署檢查清單
- [ ] 確認所有圖片和影片檔案存在
- [ ] 測試雙語切換功能
- [ ] 驗證響應式設計
- [ ] 檢查所有連結有效性
- [ ] 確認 SEO meta 標籤正確

## 📞 支援和聯繫

如有任何問題或建議，請聯繫：
- **技術問題**: support@albumai.net
- **商業合作**: hello@albumai.net
- **法律事務**: service@albumai.net

---

**© 2025 AlbumAI. All rights reserved.**  
*Transform what you see to what you say.* 