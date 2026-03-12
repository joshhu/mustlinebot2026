# 明新科技大學資管系 2026 年上半年 LINE Bot 課程

## 課程注意事項

* 程式問題提問，請在 [Issues](https://github.com/joshhu/mustlinebot2026/issues) 上提問，並且提供程式碼、錯誤訊息，以及問題描述。
* 密鑰名稱為求符合命名標準，統一使用下列格式：
    - LINE 的 channel secret：`YOUR_CHANNEL_SECRET`
    - LINE 的 channel access token：`YOUR_CHANNEL_ACCESS_TOKEN`
    - Google AI Studio 的 API key：`GOOGLE_API_KEY`

## 課前準備
1. Google 帳號，申請 Google AI Studio 帳號的 API 金鑰
2. Huggingface 的帳號
3. LINE 的帳號
4. 下課後問題，在本課程的 [Github Issues](https://github.com/joshhu/mustlinebot2026/issues) 提問（需註冊 Github 帳號）
5. 能執行 Powershell 的 Windows 電腦或者 Terminal 的 Mac 電腦

## 課程簡介
在 Huggingface Space 上建立 LINE Bot，具備下列功能：
1. 用繁體中文的聊天機器人
2. Text-to-image 機器人
3. Image-to-text 機器人

## 課程目標
- 課前準備
- 開發環境安裝及測試
- 基礎觀念及知識
- 帳號申請及金鑰
- Huggingface Space 的建立及使用
- 程式碼撰寫及說明
- Google Gemini API 說明及整合

## 上課日期
每週五 09:10 ~ 12:00

| 週次 | 日期 |
|------|------|
| 1 | 2026/03/20 |
| 2 | 2026/03/27 |
| 3 | 2026/04/10 |
| 4 | 2026/04/17 |
| 5 | 2026/05/08 |
| 6 | 2026/05/15 |

## 教材內容
- `Code/`：課程範例程式
- `Refs/`：課程參考資料
- `Slides/`：課程投影片

## 技術架構
- **語言**: Python 3.12
- **Web 框架**: Flask + Gunicorn
- **LINE SDK**: line-bot-sdk
- **AI 模型**: Google Gemini API
- **容器化**: Docker
- **佈署平台**: Hugging Face Spaces
