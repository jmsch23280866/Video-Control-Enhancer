# 影片播放速度與音量調節器

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[English](README.md)

這是一個方便的瀏覽器使用者腳本（userscript），讓您能夠使用滑鼠輕鬆調整網頁影片的播放速度和音量，並提供即時視覺回饋。

## 功能特色

- 使用 Ctrl + 滑鼠滾輪調整影片播放速度
- 使用 右鍵 + 滑鼠滾輪調整影片音量
- 螢幕中央顯示即時調整資訊
- 支援所有包含 HTML5 影片播放器的網站
- 介面簡潔直覺，不影響原始網頁體驗

## 使用方法

### 播放速度調整
- 按住 Ctrl 鍵
- 向上滾動滑鼠滾輪：加快播放速度
- 向下滾動滑鼠滾輪：降低播放速度
- 速度範圍：0.1x ~ 16.0x

### 音量調整
- 按住滑鼠右鍵
- 向上滾動滑鼠滾輪：提高音量
- 向下滾動滑鼠滾輪：降低音量
- 音量範圍：0% ~ 100%

## 安裝方式

1. 首先安裝使用者腳本管理器：
   - Chrome：[Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - Firefox：[Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)

2. 點擊以下連結安裝腳本：
   - [安裝腳本](安裝連結) <!-- 請替換成實際的安裝連結 -->

## 技術細節

- 純 JavaScript 實作
- 不依賴任何外部函式庫
- 使用 MutationObserver 監控 DOM 變化
- 支援動態載入的影片元素

## 相容性

- 支援所有主流瀏覽器（Chrome、Firefox、Edge、Safari）
- 支援所有使用標準 HTML5 `<video>` 元素的網站

## 授權條款

本專案採用 MIT 授權條款 - 詳見 [LICENSE](LICENSE) 檔案

## 貢獻指南

歡迎提交 Issue 或 Pull Request 來協助改善這個專案！

## 作者

特務E04 ([@jmsch23280866](https://github.com/jmsch23280866))

## AI 協助聲明

- 本專案在開發過程中獲得 Claude 3.5 Sonnet 及 ChatGPT AI 的協助，包括程式碼優化建議和文件撰寫。
- 本人相信透明地聲明 AI 的參與可以促進開源社群的發展。

## 更新日誌

### 1.0.0 (2025-01-03)
- 首次發布
- 實作基本的播放速度和音量控制功能
- 加入 HUD 顯示功能 
