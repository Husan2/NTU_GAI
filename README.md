# NTNU_GAI

- 姓名：王俐璇
- 系級：電機系
- 課程名稱：生成式 AI:文字與圖像生成的原理與實務\_國立臺灣師範大學衛星課程
- 修課學期：113-2

---

## 📌 第一週作業 WEEK1_0218

[程式碼作業請直接點我](/WEEK1_0218/0218函數圖形.ipynb)

- 日期：2025/02/18
- 主題：函數圖形
- colab 連結：
  [第一週作業](https://colab.research.google.com/drive/1gNIgU3czeM_yyakykFpk6_UBSod2QFid?usp=sharing)

---

## 📌 第二週作業 WEEK1_0225

[程式碼作業請直接點我](/WEEK2_0225/0225作業神經網路.ipynb)

- 日期：2025/02/25
- 主題：打造自己的 DNN(全連結)手寫辨識
- colab 連結：
  [-第二週作業](https://colab.research.google.com/drive/1LAK8PpSQ1qoH9e7NRJLalNjHwL30VUTH?usp=sharing)
- colab 連結：
  [-上課筆記](https://colab.research.google.com/drive/1c5zAok7IQkd0WCugFMnYlaNeTulDmh1F?usp=sharing)

  在老師範例的筆記中，寫下 3 後，還沒有完全確定這個手寫數字就是 3
  信心度為 29%認為這是 3
  ![alt text](/WEEK2_0225/29.png)
  經過訓練後，完全 100%確定就是 3 ~可喜可賀
  ![alt text](/WEEK2_0225/100.png)
  以下是我的準確率截圖
  ![alt text](/WEEK2_0225/accuracy.png)

## 📌 第三週作業 WEEK3_0304

[程式碼作業請直接點我](/WEEK3_0304/0304GAN.ipynb)

- 日期：2025/03/04
- 主題：GAN 模型生圖比較
- colab 連結：
  [-第三週作業](https://colab.research.google.com/drive/1Ix_HMkIznmy2uveFZEFqJ7o4Vc_ahzcv?usp=sharing)
  ![alt text](/WEEK3_0304/GAN.png)

## 📌 第四週作業 WEEK4_0311

[作業請直接點我](https://docs.google.com/document/d/1--HbRHwBmwLQVSUaiazV1FK_4EAWUVYZPw13PRkReyM/edit?usp=sharing)

- 日期：2025/03/11
- 主題：建立自己的 benchmarks
- colab 連結：
  1. [-ChatGPT 模型：GPT-4.5 版本](https://colab.research.google.com/drive/1Vt4_yNdW4ZZmdMJDZIFoFlhPkp8mfSUR?usp=sharing)
  2. [-!失敗!Claude 模型：Claude-3.5 Haiku 版本](https://colab.research.google.com/drive/1b1RuWcZX6VakEdJFO3vD0iml30YMqIcZ?usp=sharing)
  3. [-Deepseek](https://colab.research.google.com/drive/1TGh74JerU1EYJAYs7QyG4iKbhxKbv0I6?usp=sharing)
- 模型回答的看法：
  綜合觀察下來，我最喜歡 ChatGPT 的回應，Deepseek 的生成介面
  - ChatGPT（GPT-4.5） 提供了逐步且易於理解的程式碼解釋，這對於新手非常友好。
    它的回應中穿插了詳細的步驟說明，避免了將程式碼一口氣丟給使用者的情況；然而，這個模型在使用 ngrok 進行伺服器轉發時，卻未能事先提醒使用者需要註冊並取得 authtoken，造成了一定的困擾。另外，背景畫面沒有使用響應式設計（RWD），導致在不同設備上顯示效果不佳，且即便進行後續對話後也未能有效修正這一問題。
  - Claude（Claude-3.5 Haiku） 的回應中，主要的問題在於使用 inspect.getsource() 時無法正確取用原始碼，並且即使與模型進行交流，問題仍未解決，最終免費額度用完，導致測試無法完成，顯示出這個模型在處理一些較為技術性的問題時的限制。
  - Deepseek（Deepseek-V3） 提供了視覺上漂亮的介面，符合美學需求，但其程式碼冗長且包含不必要的部分，這使得代碼不夠簡潔清晰。此外，程式碼中還存在順序錯誤，這需要使用者進行人工調整，顯示了這個模型在邏輯性和代碼整潔度上的不足。

## 📌 第六週作業 WEEK6_0325

[作業請直接點我](/WEEK6_0325/0325ChatRobot.ipynb)

- 日期：2025/03/11
- 主題：用 API 打造自己的對話機器人
- colab 連結：https://colab.research.google.com/drive/11dRGEDE5Y5V_7msNoNxzqPA4wHJP_6-6?usp=sharing

- 本週作業的目標是透過 **Groq API** 打造一個具有明確人設的智慧對話機器人。
- 我選擇了《哈利波特》系列中深具智慧與威嚴的角色 ──**麥米奈娃·麥教授（Minerva McGonagall）**，並嘗試讓她展現出溫柔、親切但堅定的教學風格。

- 在人設設計上，我使用 `system` prompt 明確設定教授的身份、個性與語氣，並要求她使用繁體中文回應，讓整體互動體驗更貼近霍格華茲的氛圍。

- 🪄 對話一：魔法與個性的關聯
  ![對話一](/WEEK6_0325/對話機器人.png)
  我問教授：

> 教授，您覺得一個人會因為選擇的魔法而變成不同的人嗎？

她的回答令人印象深刻，不僅回應了問題，還加入了價值觀引導。她指出：**魔法的選擇反映的是人的價值觀與個性，但不會從根本改變一個人的本質**；真正定義一個人的是他如何使用這股力量。  
她也提醒我：選擇魔法的過程，其實也是一種成長與轉變。這讓我聯想到現實中我們對技術與知識的選擇，關鍵不在工具本身，而在於我們的使用方式。

- 📚 對話二：學習上的困難與鼓勵
  ![對話二](/WEEK6_0325/對話機器人02.png)
  我接著問教授：

> 我在變形術小考總是記不住那個魔法咒語的語調，有什麼練習方法嗎？

- 教授以非常細膩又具體的方式回應，分析了問題的可能原因，並給予多種練習策略：

  - 重複誦讀魔法咒語，強化語調熟悉度
  - 將咒語與動作結合，加深記憶連結
  - 在不同情境下練習，以提高應變能力

- 她最後以一句「**我們可以一起努力**」來鼓勵我，展現出既嚴謹又溫暖的教學態度，完全貼合原著角色形象。

## 📌 第七週作業 WEEK7_0401

[作業請直接點我]

- 日期：2025/04/01
- 主題：延續上週作業，參考老師的範例，更改成可以持續對話的版本。(Gradio 展示)
- colab 連結：

## 📌 第八週作業 WEEK8_0408

[作業請直接點我]

- 日期：2025/04/08
- 主題：實作 RAG 系統
- colab 連結：
