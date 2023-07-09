# Building-Sentiment-Lexicon-for-under-resources-language
Lexicon Dataset Builder using Python

This code first imports the necessary libraries, including the csv module for reading and writing CSV files, the pandas module for data manipulation, and the transformers module for natural language processing.
Next, the code loads the RoBERTa model and tokenizer, which are pre-trained models for sentiment analysis. The code then defines a function called SentimentAnalysis() that takes a text as input and returns the predicted polarity of the text.
The code then opens the CSV file testdata.csv and reads each text in the file. The SentimentAnalysis() function is called on each text and the predicted polarity is appended to the end of the text.
Finally, the results are saved to a CSV file called results.csv.
