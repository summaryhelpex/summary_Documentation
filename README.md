1.	Name of the product.

-	Summary Help

2.	A product description

Our team's goal is to make a Chrome extension program that helps students, or any user who wants instant summarization of a paragraph or translation.
 When we surf the internet, there are a lot of paragraph written in English. While reading we sometimes miss the keyword, and that reading process needs high workload. But if we use web service that helps us to translate, it is time spending to do it every time by copying and paste the paragraph. So, we are focusing on the easy way to help user when doing that job. And our answer is Chrome extension program that helps you these jobs.
User drags the paragraph which he wants to ask for the translation or to extract keywords. After that, program sends the paragraph to server, and refine the data. The server extracts the data by using Recurrent neural networks (RNN) or LSTM. We are planning to use seq-2-seq model, but it can be changed by the performance it shows. And for the translation, we’ll use Google translating api. If these tasks are done, server resend the data to the user and show it as pop-up or replace the paragraph that are shown.



[Architecture Diagram]

We also added feature that allows user to ask other user with translated paragraphs. If the user thinks the translation is awkward, you can just click the "Ask the user" button to send a translation request to another user. Then these data will sent to the user who preset the available language. The user who received request, sends back to the user a less awkward or appropriate translation. These functions can be on/off by users’ selection
 For example, a student who attending computer science, usually look for a reference in Stackoverflow. But most of the articles are written in English, It’s time spending work to read all the paragraph and translating it. 
If he installs our extension, he can figure out the keyword of the article and easily understand the page, and less effort looking for the information what he is looking for. After all, he can concentrate only on development. Not translating.


3.	GUI diagrams
[① Main GUI]
[② Settings]
[③ Summarize Result & Send]
 
[④ Send to Other User]
 
[⑤ Receive Reply from Other User]

4.	Use cases

4-1.	If user wants a summary of the article
 	 When user wants to summarize their articles, our program can quickly summarize articles and save users’ time.

4-2.	When summarizing articles from other language
If you want to summarize articles in other language, this program can summarize into the language which appropriates to you.

4-3.	If the accuracy of the summary is doubtful
If you think that the summary information is not accurate, you can send a question to other user to confirm that translation is correct or receive a response.


5.	A Process description
5-1	 Tools
-	Python 3
-	Java Script
-	Html
-	Css
-	Google chrome extension api
-	Seq2seq
-	Django

5-2	 Division of Works
-	정채문
1)	 Machine Learning Development
2)	 Sever Development
-	주석천
1)	 Machine Learning Development
2)	 ML test & Debugging
-	장유진
1)	Sever construction
2)	 System Link
-	최영재
1)	Chrome-extension frontend & backend
2)	Extension-Test & Debugging
3)	Server Development(Sub)
-	정영진
1)	Chrome-extension frontend & backend
2)	 Extension-Test & Debugging
3)	Machine-Learning Development Sub)


