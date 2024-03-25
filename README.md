# llama2-faiss-langchain-qa-RAG
該project利用個人網站來實現客製化的QA問答。其中使用了RAG、LLAMA 2模型、Faiss庫和LangChain等關鍵技術來解決問題。


當中使用到的技術包含：
* 使用RAG模型（Retriever Answer Generator）來進行問答系統的構建。
* 利用LLAMA 2模型進行對話生成，實現QA功能。
* 使用Faiss實現向量檢索功能，用於相似度匹配和聚類。
* 利用LangChain來構建和管理NLP流程，包括文檔加載、文本分割、向量嵌入等功能。
* 使用[個人網站](https://antiotseng.github.io/antio.github.io/)做為外部資料進行增強檢索。

範例輸出：
Q: Who is Antio Tseng?
A: Antio Tseng is a Data Analyst/Data Scientist based in Taipei, Taiwan. He has a Master's degree in Statistics from National Chengchi University (NCCU) and previously worked as an intern at iKala inc. His skills include Python, R, Git, SQL, HTML, CSS, Tableau, Looker Studio, Machine Learning, Deep Learning, NLP, Statistics Analysis, Data Mining, and Metric design.



Reference:
https://medium.com/@murtuza753/using-llama-2-0-faiss-and-langchain-for-question-answering-on-your-own-data-682241488476
