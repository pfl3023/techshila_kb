# techshila_kb
A machine learning model that generates consulting case interview questions and analyses spoken response through NLP.  
We created dataset by extracting relevant pages from case interview pdf's (using python's PyPDF2 library) and then putting them in an excel file in a question-answer format.
Next we used natural language toolkit(nltk) to preprocess the data and get an array of keywords.
We used the BERT NLP model which is a transformer based model architecture  which reads the entire input text at once, capturing context from both directions. This bidirectional approach allows BERT to understand the context of a word based on its surrounding words. 
This model generates questions from the dataset we created and takes in answers from the interviewee using python's speech recognition and pyaudio library.
If the spoken answer contains a certain threshold of keywords,the interview proceeds,else,the model suggests a much more appropriate answer.
Finally,the interview ends when the majority of the keywords have been used in the interview process.
