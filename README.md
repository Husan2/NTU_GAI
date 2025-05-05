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

---

## 📌 第三週作業 WEEK3_0304

[程式碼作業請直接點我](/WEEK3_0304/0304GAN.ipynb)

- 日期：2025/03/04
- 主題：GAN 模型生圖比較
- colab 連結：
  [-第三週作業](https://colab.research.google.com/drive/1Ix_HMkIznmy2uveFZEFqJ7o4Vc_ahzcv?usp=sharing)
  ![alt text](/WEEK3_0304/GAN.png)

---

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

---

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

---

## 📌 第七週作業 WEEK7_0401

[作業請直接點我](/WEEK7_0401/0401進階版對話機器人.ipynb)

- 日期：2025/04/01
- 主題：延續上週作業，參考老師的範例，更改成可以持續對話的版本。(Gradio 展示)
- colab 連結：https://colab.research.google.com/drive/1L-nGZxhfO4936z5mCJOpbsmW5sXdFT5w?usp=sharing

- 功能：使用 + LLaMA3 + Gradio 打造「具備記憶能力」的聊天機器人
- 目標：「可以持續對話、保留上下文記憶」的對話機器人

| 類別                      | 說明                                                                                            |
| ------------------------- | ----------------------------------------------------------------------------------------------- |
| ✅ **持續對話記憶**       | 使用 `messages` 陣列保留整段對話歷史，讓模型可以回憶前面聊過的內容，實現「一直聊下去」的體驗。  |
| ✅ **Gradio ChatUI 介面** | 使用 `gr.Chatbot(type="messages")` 打造類 ChatGPT 的上下對話氣泡框，讓 UI 更直覺。              |
| ✅ **自訂人設與風格**     | 使用 system prompt 建立「麥米奈娃教授」風格：溫柔、理性、親切，使用繁體中文、魔法語氣、表情符號 |
| ✅ **UI 美化**            | 輸入框採用淺藍色、圓角、有聚焦陰影，按鈕則為藍（送出）與紅（遺忘藥水）配色                      |
| ✅ **清除記憶功能**       | 將清除按鈕命名為「🧪 喝下遺忘藥水」，點擊後會清除記憶並顯示一段魔法語風格的提示                 |
| ✅ **Gradio share 展示**  | 使用 `launch(share=True)` 部署成可分享連結的作品，便於展示與交作業                              |

> 🧪 清除對話記憶：「喝下遺忘藥水」，當按下後，會清除所有對話框的內容
> ![遺忘藥水](/WEEK7_0401/遺忘藥水.png)

- 💬 與麥米奈娃教授的三輪對話展示（具備上下文連貫性）

> 🧙‍♀️ 問題一：魔法是否會改變一個人的本質？
> ![問題一](/WEEK7_0401/進階對話機器人01.png)

> 🧙‍♀️ 問題二：為什麼壞人幾乎都是史萊哲林的學生？
> ![問題二](/WEEK7_0401/進階對話機器人02.png)

> 🧙‍♀️ 問題三：我最崇拜斯內普，但我最喜歡的是您！
> ![問題三](/WEEK7_0401/進階對話機器人03.png)

## 📌 第八週作業 WEEK8_0408

[作業請直接點我](/WEEK8_0408/0408RAG聊天機器人.ipynb)

- 日期：2025/04/08
- 主題：實作 RAG 系統
- colab 連結：https://colab.research.google.com/drive/19Jxpw4fS0-CH_fdtPvFBRPZzC7F0Ar5C?usp=sharing

- 目標：實作 Retrieval-Augmented Generation（RAG）系統，並透過語意檢索與語言模型整合，讓對話機器人能夠回應與資料庫相關的自然語言提問。我以「哈利波特」世界觀延伸出來的虛構角色為基礎，打造一個具有風格與個性的人設問答系統。

- 👤 人設 / 背景設定

我創造了 4 位虛構角色並撰寫其個人設定，儲存為文字檔後餵入語意向量資料庫，作為機器人的知識基礎。角色如下：

1. **葵崎 凜**（Ravenclaw 學生，溫柔靜謐，最愛奇獸與魔藥）
2. **梅里・米勒**（Hufflepuff 學生，開朗樂觀，夢想成為魔法治癒師）
3. **嶺夜 綾人**（Slytherin 學生，冷靜理性，擅長防禦與符文）
4. **諾亞・席洛**（Gryffindor 學生，神秘安靜，研究魔法星象）

系統扮演的是「麥米奈娃·麥教授（Minerva McGonagall）」，她會以教授的身份回應問題，並且認知「葵崎凜是她最得意的學生」。

- 📚 使用的資料（RAG 新增內容）

我將上述 4 位角色的 `.txt` 描述檔餵入向量資料庫中，並使用 `sentence-transformers/all-MiniLM-L6-v2` 建立語意嵌入（embeddings），透過 FAISS 建構向量資料庫。回答時，系統會根據問題使用 `.similarity_search()` 擷取相關段落並融合進 prompt，由 Groq 的 LLaMA3 模型輸出自然語言回應。

- ⚠️ 系統觀察：正確 vs 幻覺
  ✅ 成功案例：
  > 問題：「葵崎凜的最好的朋友是誰？」  
  >  回答：「葵崎凜的最好的朋友是露娜·羅古德（Luna Lovegood）。」

> 問題：「她最喜歡哪堂課？」  
>  回答：「她最喜歡的課程是魔法藥學、變形學和奇獸飼育學。」

![成功案例](/WEEK8_0408/RAG問題1.png)

❌ 幻覺案例：

> 問題：「葵崎凜的貓叫什麼？」  
>  回答：「不知道名字，但可能是 Mocha？」或「沒有資料」
> 實際上資料庫明確記載：貓叫「Mocha」

> 問題：「她最喜歡的教授是誰？」  
>  回答：出現一段混合中英文的說法：「which is none other than myself, Minerva McGonagall」

![幻覺案例](/WEEK8_0408/RAG問題2.png)

## 📌 第九週作業 WEEK9_0415

[作業請直接點我](/WEEK9_0415)

- 日期：2025/04/15
- 主題：AI Agents-打造你專屬的超級代理人【Demo07a】
- colab 連結：
  ![小幫手介面](/WEEK09_0415/01.png)

> 輸入：黑魔法防禦教授又辭職？

📝 新聞草稿：

> **《預言家日報》獨家報導** **黑魔法防禦教授又辭職？**
> 魔法界再度傳出震撼的消息，據可靠消息源指出，霍格華茲魔法學校的黑魔法防禦課程教授，最近可能再度辭職。
> 這名教授曾經在多年前於霍格華茲任教，並在黑魔法防禦課程中獲得了學生的高度評價。然而，前幾年他突然辭職，引發了廣泛的猜測和質疑。現在，消息指出他可能再度卸下教職，讓霍格華茲的學生和教職員感到困惑和擔憂。

目前，霍格華茲方面仍未發表正式聲明，但本報記者已經獲悉，有關辭職原因仍在調查中。是否因為教學壓力、黑魔法的威脅，抑或是其他原因，目前仍不得而知。 本報將繼續追蹤這個事件，提供最準確和最新的報導。

📋 評論與建議：

> Here's a review of the draft with specific optimization suggestions:
> **《預言家日報》獨家報導\*\***黑魔法防禦教授驚爆再度辭職？
> （Consider adding a question mark at the end of the title to make it more attention-grabbing and inviting readers to dive into the story）
> 魔法界再度傳出震撼的消息，據 **多個** 可靠消息源** 指出，霍格華茲魔法學校的黑魔法防禦課程教授，最近可能再度辭職。
> （Add "多個" to emphasize the credibility of the sources）
> 這名教授曾經在多年前於霍格華茲任教，並在黑魔法防禦課程中獲得了學生的高度評價。然而，前幾年他突然辭職，引發了廣泛的猜測和質疑。現在，消息指出他可能再度卸下教職，讓霍格華茲的學生和教職員感到困惑和擔憂。
> （Consider adding more details about the professor's past achievements and the impact of his previous resignation to make the story more engaging）
> 目前，霍格華茲方面仍未發表正式聲明，但本報記者已經獲悉，有關辭職原因仍在調查中。是否因為教學壓力、黑魔法的威脅，抑或是其他原因，目前仍不得而知。 **我們將繼續追蹤這個事件，提供最準確和最新的報導\*\* 。
> （Emphasize the commitment to continue investigating the story and providing updates to build trust with readers）
> Overall, the draft is well-structured and engaging. With these suggestions, the article can be further optimized to grab their attention and keep them hooked!

🪄 根據評論優化後新聞：

> 魔法界再度傳出震撼的消息，據多個可靠消息源指出，霍格華茲魔法學校的黑魔法防禦課程教授，最近可能再度辭職。
> 這名教授曾經在多年前於霍格華茲任教，期間創下優秀的教學成績，獲學生高度評價，並曾獲霍格華茲魔法學校的「最佳教授」獎項。然而，前幾年他突然辭職，引發了廣泛的猜測和質疑。現在，消息指出他可能再度卸下教職，讓霍格華茲的學生和教職員感到困惑和擔憂。
> 目前，霍格華茲方面仍未發表正式聲明，但本報記者已經獲悉，有關辭職原因仍在調查中。是否因為教學壓力、黑魔法的威脅，抑或是其他原因，目前仍不得而知。我們將繼續追蹤這個事件，提供最準確和最新的報導，讓讀者第一時間掌握最新消息。

📣 社群貼文版本：

> 獨家驚爆！霍格華茲魔法學校黑魔法防禦教授再度辭職？！😱
> 多個消息源爆料，這位曾獲「最佳教授」獎的教授可能再度卸下教職！🤔 究竟是教學壓力的太大、黑魔法的威脅，還是其他原因？我們將繼續追蹤，提供最新報導！ Stay tuned! #霍格華茲魔法學校 #黑魔法防禦 #神秘事件 #魔法界大新聞

[作業請直接點我](/WEEK010_0422)

- 日期：2025/04/22
- 主題：利用 Bing 進行文字生圖。(Diffusion modle)
- colab 連結：

[作業請直接點我](/WEEK11_0429/)

- 日期：2025/04/29
- 主題：打造自己的圖像生成 Web App!(利用 hugging face 內的 SD1.5 模型進行文字生圖。)
- colab 連結：
