# ChatGPT-Prompt-Book

<img alt="Book!" style="width:30%;" src="https://github.com/androchentw/ChatGPT-Prompt-Book/blob/main/res/book.jpeg?raw=true">

初衷是彙整平常使用到的 prompt。

如同 《Hunter x Hunter 獵人》貪婪之島的 "Book"，以後會是人手一本咒語書的時代了。讓我們一起蒐集實用的 prompt，見賢思齊！

## 原理與建議

理解原理就像抓住粽子頭，可以幫助我們拓展更多應用，也可以用來檢視我們都用在哪些例子上。

### 1. 學習機制

ChatGPT 的學習訓練機制是 RLHF (Reinforcement Learning from Human Feedback, 基於人類回饋的強化學習) , 特別擅長文字接龍 (預測下一個字)。而 NLP (Natural Language Processing, 自然語言處理) 基本上可以歸類在做這 5 件事情/任務:

1. **Classification 分類**: 這篇文章在講環保還是科技, 這句話是正面還是負面
2. **Extraction 提取**: 取出關鍵字
3. **Matching 比對**: 這兩句話是否表達相同意思, 差別在哪裡
4. **Transformation 轉換**: translate, summarize 都屬於這類
5. **Generation 生成**: 綜合所有技能，無中生有，不斷文字接龍下去

所以我們就可以從這些基礎，再衍生各種應用。

### 2. 建議使用英文

基於現在使用英文會比中文有品質&有效率 (主要是因為原始訓練語料量的差別)，建議大家學習精簡的 “英文動詞與形容詞" 作為 prompt 基礎。也有助於我們邏輯思考

需要時再轉中文也可以。英文部分可以參考 

1. [GrammarlyGo](https://www.grammarly.com/grammarlygo)
2. [rephrase.info](https://www.rephrase.info/)

### 3. 角色扮演 營造情境

目前我認為最有效果的就是要提供給 ChatGPT 一個情境/Scenario/Context/上下文。這能使他更精準地扮演你要的角色，跟你互動。

### 4. 多不如精

現在有很多非常長的 prompt。而且我自己測試覺得精簡的描述就已經很足夠了。比起在大量 prompt 海中找不到，能簡單取才是關鍵。雖然 Prompt Engineering 本身有其意義存在，但其實 GPT4 比起 GPT3.5 更精準，也許現在調整得太多，最後還是回到「問答本質」

## 👨‍💻 Developer Utils 開發相關

```prompt
in #zhTW
in #enUS
 ```

### 💻 Dev, Code, Test, Security Fix

```prompt
#act-as-senior-software-engineer-expert 
```

| Icon | Title | Input | Prompt | 
| :--: | :---: | :---: | ------ | 
| 💬 | Explain | code | `Explain code: ` | 
| 🛠️ | Implement feature | requirement (story, task, BDD) | `Implement: ` | 
| 👀 | Code review | code | `Perform code review on:` | 
| 🧹 | Debug error message | error | `Fix error: ` | 
| 🧪 | Test sample output | code | `Provide sample output according to the code: ` | 
| 🔒 | Fix security | code, issue | `Fix securiti issue: ` | 

### 💻 Ops, Troubleshooting

```prompt
#act-as-senior-devops-engineer-expert 
```

| Icon | Title | Input | Prompt | 
| :--: | :---: | :---: | ------ | 
| 🔬 | RCA | issue | `Perform root cause analysis: ` | 
| 📝 | Incident report | issue | `Generate effective incident report: ` | 


## 💡 Knowldege 知識產出 相關

```prompt
#act-as-senior-expert 
```

### 📚 Reading

| Icon | Title | Input | Prompt | 
| :--: | :---: | :---: | ------ | 
| 🇹🇼 | Translate | article | `Translate to #zh-tw, preserve original tone and format: ` | 
| 📝 | Summarize 摘要 | article | `Summarize in bullet point in #zhTW and #enUS: ` | 
| 📝 | Condense 精簡 | article | `Refine and condense: ` | 
| 📝 | Rephrase 改寫 | article | `Rephrase fluently while keep the original style: ` | 
| 📝 | Elaborate 闡述 | article | `ellaborate with examples: ` | 

### ✍️ Writing

| Icon | Title | Input | Prompt | 
| :--: | :---: | :---: | ------ | 
| 🇹🇼 | Translate Blog | article | `Translate in bullet point to #zhTW, preserve original quote: ` | 
| 🇹🇼 | Propose i18n title | article heading | `Propose 5 translation to English & Japanese, and keep the original tone and make it intriguing blog post title:: ` | 
| ✍️ | Propose structure | article heading | `Propose concise heading in bullet point: ` | 
| ✍️ | Grammar | article | `Check grammar: ` | 



### 💬 Presentation

| Icon | Title | Input | Prompt | 
| :--: | :---: | :---: | ------ | 
| 💬 | Speech | article | `Compose a compelling speech: ` | 

### 📱 Social Media Post Generation

| Icon | Title | Input | Prompt | 
| :--: | :---: | :---: | ------ | 
| 📱 | Suggest SEO practices | title, article | `Suggest SEO practices: ` | 
| 📱 | Propose content | title, article | `Propose 3 engaging social media post within 500 words: ` | 


## Others

```prompt
#act-as-senior-expert 
```

### 💼 Job

| Icon | Title | Input | Prompt | 
| :--: | :---: | :---: | ------ | 
| 💼 | Resume | role, achievement | `Create a professional resume: ` | 
| 💼 | Job description | role | `Compose a profession job description: ` | 

## AIGC Copilot App/Plugin

統整實用的 AI 輔助 App

### General

| Name | Category | Function | Feature | 
| :--: | :------: | -------- | :-----: | 
| [ChatGPT](https://chat.openai.com) | Web | ChatGPT | 完整對話記錄 |
| [UseChatGPT.AI], [ChatGPT Sidebar], [Merlin] | Chrome Plugin | 網頁中的 ChatGPT | 選取運用; Prompt template  |
| [Glarity] | Chrome Plugin | 網頁及 YouTube 摘要 (ChatGPT) | 一鍵方便 |
| [Trancy]  | Chrome Plugin | 語言學習助手 YouTube 雙語字幕 | 生成字幕, 整合度高 |
| [ChatGPT Writer]  | Chrome Plugin | Email | 整合 gmail |
| [Sharly.AI](https://www.sharly.ai) | Web | Doc Summarize | 整份文件 |
| [FlowGPT](https://flowgpt.com) | Web | Prompt 社群 | 多種情境範本參考 |
| [Auto-GPT], [AgentGPT], [BabyAGI] | GitHub Repo | 自動任務串接 | 用來產生 Story 的 subtask |
| [stable-diffusion-webui-colab] | GitHub Repo | Stable Diffusion Google Colab | 免費產圖. cetus, pastel, rpg, lyriel, anime-lineart |
| [Moonshot](https://www.kocpc.com.tw/archives/483998) | LINE Chatbot | 寫實/概念/漫畫 | 免費產圖 |
 

<!-- Link -->
[Glarity]: https://chrome.google.com/webstore/detail/glarity-summary-for-googl/cmnlolelipjlhfkhpohphpedmkfbobjc
[Trancy]: https://chrome.google.com/webstore/detail/language-learning-with-vi/mjdbhokoopacimoekfgkcoogikbfgngb
[UseChatGPT.AI]: https://chrome.google.com/webstore/detail/usechatgptai-chatgpt-copi/mhnlakgilnojmhinhkckjpncpbhabphi
[ChatGPT Sidebar]: https://chrome.google.com/webstore/detail/chatgpt-sidebar-support-g/difoiogjjojoaoomphldepapgpbgkhkb
[Merlin]: https://chrome.google.com/webstore/detail/merlin-chatgpt-assistant/camppjleccjaphfdbohjdohecfnoikec
[ChatGPT Writer]: https://chrome.google.com/webstore/detail/chatgpt-writer-write-mail/pdnenlnelpdomajfejgapbdpmjkfpjkp
[Auto-GPT]: https://github.com/Torantulino/Auto-GPT
[AgentGPT]: https://agentgpt.reworkd.ai/
[BabyAGI]: https://github.com/yoheinakajima/babyagi
[stable-diffusion-webui-colab]: https://github.com/androchentw/stable-diffusion-webui-colab
