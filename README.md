# AI_Chatbot

This is a simple program that I developed for my master thesis in Business Intelligence and Data Analytics.

The concept is that using Langchain I developed a very simple AI chatbot that is fed by user data, html or pdf files and it can answer questions on that data.

The code is very simple so it is easily comprehensible. If something is not clear with a simple search in the langchain doucments it will be resolved.

The code has two options, the one is to upload the files directly and the other is to enter the url of the website you wish to be crawled and the files will be saved automatically. However, the web crawling method seems to not find all the subpages.

In order for the code to work you must have installed the required libraries, have an OpenAI key and also enter the paths were the data will be saved as instructed in the code.

The applicatiob was tested with my university website as data. I crawled my university's website starting from the main url and continue to all the other subpages. In total, 414 webpages were found as can be seen also in the excel file that it is attached.
The application seem to perfrom well answering almost all the questions correctly.

Since the concept of the application was to be simple, it contains only the very basic for an AI Chatbot. Of course, the code can be developed further by changing the text splitting method, the embediing transformer, the LLM model and many more.



