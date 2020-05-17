# Quora Question Pairs
**Introduction** <br />
Quora is a question-and-answer style knowledge share platform. Where  questions are asked, answered, and edited by registered internet users from around the world. Over 100 million people visit Quora every month, therefore many users may ask similar questions which will result in multiple copies of the same questions and answers produced and stored. The research question is which questions on Quora will have the same meaning? And therefore the same or very similar answers? This analysis will be done using the Python programming language. The main objective is to give the reader and writer a better experience by finding the most suitable and related answers to their questions quickly and efficiently. 

This analysis will include but not limited to the following techniques and steps to deliver the desired results: <br />
•	Initial analysis: Dealing with missing values, checking the distribution of the word count in each question and checking the imbalanced data <br />
•	Data preprocessing: text cleaning, tokenization <br />
• word embedding <br />
• Feature Extraction <br />
•	Classification modeling <br />
•	Evaluating the model  <br />

**Dataset** <br />
The dataset consists of 404,290 question pairs.
Data Fields: <br />
Id: a simple row ID <br />
qid{1, 2}: The unique ID of each question in the pair <br />
question{1, 2}: The actual textual contents of the questions. <br />
is_duplicate: The label that we are trying to predict - whether the two questions are duplicates of each other or not. Similar pairs are labeled as 1 and non-duplicate as 0  <br />

Dataset source:
https://www.quora.com/q/quoradata/First-Quora-Dataset-Release-Question-Pairs


