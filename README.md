# NTNU_GAI

- 姓名：王俐璇
- 系級：電機系
- 課程名稱：生成式 AI:文字與圖像生成的原理與實務\_國立臺灣師範大學衛星課程
- 修課學期：113-2

## 📌 第一週作業 WEEK1_0218

[程式碼作業請直接點我](/WEEK1_0218/0218函數圖形.ipynb)

- 日期：2025/02/18
- 主題：函數圖形
- colab 連結：
  [第一週作業](https://colab.research.google.com/drive/1gNIgU3czeM_yyakykFpk6_UBSod2QFid?usp=sharing)

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

ChatGPT（GPT-4.5） 提供了逐步且易於理解的程式碼解釋，這對於新手非常友好。
它的回應中穿插了詳細的步驟說明，避免了將程式碼一口氣丟給使用者的情況；然而，這個模型在使用 ngrok 進行伺服器轉發時，卻未能事先提醒使用者需要註冊並取得 authtoken，造成了一定的困擾。另外，背景畫面沒有使用響應式設計（RWD），導致在不同設備上顯示效果不佳，且即便進行後續對話後也未能有效修正這一問題。

Claude（Claude-3.5 Haiku） 的回應中，主要的問題在於使用 inspect.getsource() 時無法正確取用原始碼，並且即使與模型進行交流，問題仍未解決，最終免費額度用完，導致測試無法完成，顯示出這個模型在處理一些較為技術性的問題時的限制。

Deepseek（Deepseek-V3） 提供了視覺上漂亮的介面，符合美學需求，但其程式碼冗長且包含不必要的部分，這使得代碼不夠簡潔清晰。此外，程式碼中還存在順序錯誤，這需要使用者進行人工調整，顯示了這個模型在邏輯性和代碼整潔度上的不足。
