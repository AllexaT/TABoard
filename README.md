# TABoard - Smart Digital Clock with Weather Display
# TABoard - 智慧型動態時鐘與天氣顯示器

[English](#english) | [中文](#中文)

## English

Transform your idle tablet into an elegant digital timepiece! TABoard breathes new life into your unused tablet, turning it into a sophisticated clock display that enhances your living space. This Android application combines a stylish digital clock with real-time weather information, featuring dynamic video backgrounds that adapt to current weather conditions.

### Why TABoard?

- **Repurpose Your Tablet**: Give your unused tablet a meaningful second life
- **Enhance Your Space**: Turn any room into a modern living space with an aesthetic clock display
- **Beyond Just Time**: More than a simple clock - it's an ambient information center that elegantly displays weather and time
- **Visual Delight**: Dynamic backgrounds that smoothly transition based on time and weather, creating a living artwork in your space

### Features

- Clean and modern digital clock display
- Real-time weather information with temperature display
- Dynamic video backgrounds that reflect current weather conditions
- Day/night cycle awareness with appropriate visual changes
- Customizable clock size and appearance
- Manual location setting or GPS-based weather updates
- Minimalist floating menu for easy access to settings
- Network status monitoring with auto-retry capability

### Technical Highlights

- Written in Kotlin
- MVVM architecture
- Coroutines for asynchronous operations
- Custom video scaling implementation
- OpenWeatherMap API integration
- SharedPreferences for settings management
- LocalBroadcastManager for component communication
- Custom view implementations

### Screenshots

[Screenshots will be added here]

### Requirements

- Android 6.0 (API level 23) or higher
- Internet connection for weather updates
- Location permission (optional, for GPS-based weather)

### Installation

1. Clone this repository
2. Add your OpenWeatherMap API key to `local.properties`:
   ```
   WEATHER_API_KEY=your_api_key_here
   ```
3. Build and run using Android Studio

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Weather data provided by OpenWeatherMap
- Video backgrounds [source attribution]

### Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 中文

將閒置的平板電腦搖身一變成為優雅的數位時鐘！TABoard 為您的閒置平板注入新生命，將其轉化為一個提升居家空間品質的精緻時鐘顯示器。這款 Android 應用程式結合了時尚的數位時鐘與即時天氣資訊，配備根據當前天氣條件自動調整的動態影片背景。

### 為什麼選擇 TABoard？

- **平板再利用**：讓閒置的平板發揮全新的價值
- **提升空間質感**：用精緻的時鐘顯示器為任何房間增添現代感
- **不只是時鐘**：不僅僅是簡單的時鐘 - 更是一個優雅展示天氣與時間的環境資訊中心
- **視覺饗宴**：根據時間和天氣平滑轉換的動態背景，為您的空間創造一件生動的藝術品

### 功能特色

- 簡潔現代的數位時鐘顯示
- 即時天氣資訊與溫度顯示
- 反映當前天氣狀況的動態影片背景
- 因應日夜循環自動調整的視覺效果
- 可自訂的時鐘大小與外觀
- 手動位置設定或 GPS 定位的天氣更新
- 簡約的浮動選單，輕鬆存取設定
- 網路狀態監控與自動重試功能

### 技術特點

- 使用 Kotlin 開發
- MVVM 架構
- 使用 Coroutines 處理非同步操作
- 自訂影片縮放實作
- 整合 OpenWeatherMap API
- 使用 SharedPreferences 管理設定
- 使用 LocalBroadcastManager 進行元件通訊
- 自訂視圖實作

### 系統需求

- Android 6.0 (API level 23) 或更高版本
- 網路連線（用於天氣更新）
- 位置權限（選用，用於 GPS 定位天氣）

### 安裝說明

1. 複製此儲存庫
2. 在 `local.properties` 中加入您的 OpenWeatherMap API 金鑰：
   ```
   WEATHER_API_KEY=your_api_key_here
   ```
3. 使用 Android Studio 建置並執行

### 授權條款

本專案採用 MIT 授權條款 - 詳見 [LICENSE](LICENSE) 檔案。

### 致謝

- 天氣資料由 OpenWeatherMap 提供
- 影片背景 [來源說明]

### 參與貢獻

歡迎提交貢獻！請隨時提出 Pull Request。 