# BERT_Keyword_Search
Using The BERT Large Language Model to search for keywords in running shoe reviews. The project involves 3 separate notebooks: collection, processing, and the main keywords algorithm. In the collection stage, I used the requests module and beautiful soup to scrape all of the shoe reviews on https://www.runningshoesguru.com/. The processing stage involved taking the html for each review and extracting features like the title, date, and review body. 

Finally The BERT_Keywords notebook utilises the BERT NLP framework to generate word embeddings, then uses these to search for similar words based on a search keyword.

This project taught me much about how to apply LLM's to unsupervised tasks, both in terms how powerful a framework like BERT is but also possible issues and limitations. My favourite achievement in this project was experimenting with how to embed the keywords, initially I planned to just feed then on their own to the model but I found that first inserting them into a standard sentence: 'look for '+keyword+' in the text' significantly improved the embedding from BERT.
