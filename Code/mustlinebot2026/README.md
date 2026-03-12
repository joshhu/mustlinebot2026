# mustlinebot2026

明新科技大學 資訊管理系 2026 LINE Bot 課程專案

## 課程資訊

- **學校**: 明新科技大學（MUST）
- **系所**: 資訊管理系
- **學期**: 2026 上半年
- **上課時間**: 每週五 09:10 ~ 12:00

### 上課日期

| 週次 | 日期 |
|------|------|
| 1 | 3/20 |
| 2 | 3/27 |
| 3 | 4/10 |
| 4 | 4/17 |
| 5 | 5/8 |
| 6 | 5/15 |

## 專案說明

本專案為 LINE Bot 開發教學用程式碼，使用 Flask 建立 Webhook Server，搭配 Google Gemini API 實現聊天機器人功能，並透過 Docker 容器化佈署至 Hugging Face Spaces。

## 程式檔案

| 檔案 | 說明 |
|------|------|
| `replybot.py` | 基本回覆機器人（Echo Bot） |
| `multiturn.py` | 多輪對話機器人 |
| `system_prompt.py` | 含系統提示詞的機器人 |
| `with_logs.py` | 加入日誌記錄功能 |
| `with_search.py` | 加入搜尋功能 |
| `gpt4.py` | OpenAI GPT-4 版本（示範用） |
| `gemini.py` | Google Gemini 版本（主要使用） |
| `example01.py` | 綜合範例 |

## 技術架構

- **語言**: Python 3.12
- **Web 框架**: Flask + Gunicorn
- **LINE SDK**: line-bot-sdk
- **AI 模型**: Google Gemini API
- **容器化**: Docker
- **佈署平台**: Hugging Face Spaces

## 快速開始

1. 複製本專案
2. 設定環境變數（LINE Channel Secret、Channel Access Token、Gemini API Key）
3. 使用 Docker 建置並執行：

```bash
docker build -t mustlinebot2026 .
docker run -p 7860:7860 mustlinebot2026
```
