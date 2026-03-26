# 明新科技大學資管系 2026 年上半年 LINE Bot 課程

## 課程資訊

- **講師**：胡嘉璽（嘉崎人智股份有限公司技術長）
- **時間**：2026 年 3–4 月
- **地點**：明新科大資管系
- **聯絡**：[github/joshhu](https://github.com/joshhu)

## 課程注意事項

- 程式問題提問，請在 [Issues](https://github.com/joshhu/mustlinebot2026/issues) 上提問，並提供程式碼、錯誤訊息及問題描述。
- 課程所有資料放在此 GitHub 專案，每次上課前教材都會更新調整。
- 上課中有問題可以在 Slido 中提問，每節下課後都會回答 https://app.sli.do/event/phvxUHK5C9DznyewYDJvPC
- 密鑰名稱統一使用下列格式：
  - LINE Channel Secret：`YOUR_CHANNEL_SECRET`
  - LINE Channel Access Token：`YOUR_CHANNEL_ACCESS_TOKEN`
  - Google AI Studio API Key：`GOOGLE_API_KEY`

## 課前準備

1. Google 帳號（申請 Google AI Studio 的 API 金鑰）
2. LINE 帳號
3. GitHub 帳號（用於課後在 [Issues](https://github.com/joshhu/mustlinebot2026/issues) 提問）
4. 能執行 Powershell 的 Windows 電腦或 Terminal 的 Mac 電腦
5. 安裝 Conda 環境（用於管理環境變數與套件）

## 課程簡介

本課程教授如何使用 Python 搭配 Flask 框架、LINE Messaging API 及 Google Gemini API，從零開始建立一個具備多種 AI 功能的 LINE Bot，包含：

- 繁體中文聊天機器人（支援多輪對話、System Prompt、搜尋功能）
- 文字生成圖片（Text-to-Image）
- 圖片辨識描述（Image-to-Text）
- 圖片生成影片（Image-to-Video）
- RAG 檢索增強生成

## 課程大綱

| 單元 | 投影片              | 主題              | 內容概要                                                                                  |
| ---- | ------------------- | ----------------- | ----------------------------------------------------------------------------------------- |
| 0    | 00. 課程介紹        | 課程介紹          | 講師簡介、課程目標、教材下載及提問方式                                                    |
| 1    | 03. Line開發者帳號  | LINE 平台基礎     | Developer/Provider/Channel 帳號架構、Messaging API 設定、LINE Bot 運作原理與 Webhook      |
| 2    | 04. Ngrok說明       | 開發環境建置      | IP/網址/公私網原理、ngrok 通道技術、Flask 本機測試、環境變數設定（conda env config vars） |
| 3    | 05. 基礎觀念及知識  | Web 開發基礎      | Webhook 原理、JSON 資料格式、前後端語言概念、Flask Web 框架介紹                           |
| 4    | 06. LINEBOT程式講解 | LINE Bot 程式開發 | Google Gemini API 串接、生成式 AI 模型概念、多種訊息類型處理                              |

## 程式範例

所有範例程式放在 `Code/Colab/` 目錄下，以 Jupyter Notebook（`.ipynb`）格式提供：

| 編號 | 檔案                                    | 說明                   |
| ---- | --------------------------------------- | ---------------------- |
| 04   | `0404_Colab_Pyngrok_Flask.ipynb`        | ngrok + Flask 連線測試 |
| 05   | `0501_Colab_ReplyBot.ipynb`             | 基礎回覆機器人         |
| 06   | `0601_Colab_MultiMessageBot.ipynb`      | 多訊息類型處理         |
| 06   | `0602_Colab_Full_app.ipynb`             | 完整應用程式           |
| 07   | `0701_Colab_LINE_Bot_with_GEMINI.ipynb` | Gemini 基礎串接        |
| 07   | `0702_..._Stateful.ipynb`               | 多輪對話（有狀態）     |
| 07   | `0703_..._SystemPrompt.ipynb`           | System Prompt 設定     |
| 07   | `0704_..._Tooluse.ipynb`                | Tool Use 功能          |
| 07   | `0705_..._Logs.ipynb`                   | 對話紀錄功能           |
| 07   | `0706_..._Image2Text.ipynb`             | 圖片轉文字             |
| 07   | `0707_..._Text2Image.ipynb`             | 文字轉圖片             |
| 07   | `0708_..._Image2Video.ipynb`            | 圖片轉影片             |
| 07   | `0709_..._Rag.ipynb`                    | RAG 檢索增強生成       |

## 專案結構

```
├── Code/Colab/     # 課程範例程式（Jupyter Notebook）
├── Ref/            # 參考資料（LINE Bot 開發指南等）
├── Slides/         # 課程投影片
└── README.md
```

## 技術架構

- **語言**：Python
- **Web 框架**：Flask
- **LINE SDK**：line-bot-sdk
- **AI 模型**：Google Gemini API
- **通道工具**：ngrok / pyngrok
- **開發環境**：Conda + VS Code / Google Colab

## 上課日期

每週五 09:10 ~ 12:00

| 週次 | 日期       |
| ---- | ---------- |
| 1    | 2026/03/20 |
| 2    | 2026/03/27 |
| 3    | 2026/04/10 |
| 4    | 2026/04/17 |
| 5    | 2026/05/08 |
| 6    | 2026/05/15 |
