Project Title
-----------------

Text Analysis of Charles Dickens’ Oliver Twist using Natural Language Tool Kit and Sentiment Analysis using TextBlob

Table of Contents
-----------------
-   [Project Background](#project-background)
-   [Install & Setup](#install-&-setup)
-   [Prerequisites](#usage)
-   [Obtaining of Dataset](Obtaining-of-Dataset)
-   [Project Goal](#project-goal)
-   [Resourcest](#resources)



Project Background
----------
This project will focus on conducting a text analysis of the famous novel, ‘Oliver Twist’ written by renowned writer, Charles Dickens. With the aid of Natural Language Toolkit (NLTK) and TextBlob, the text will be analyzed to know the word that was mentioned frequently in the novel, the number of times the main character was mentioned. Also, a brief sentiment analysis will be carried out on the novel.


Prerequisites
---------------

For the purpose of this project, python needs to be downloaded. This project will be using NLTK for text analysis, so NLTK has to be downloaded. The dataset - Oliver Twist written by Charles Dickens- used for this project was sourced from Project Guntenberg.

Install & Setup
--------------

To analyse the text, follow this step on:

< !pip install nltk >

< !pip install wordcloud >
  
 < !pip install texblob >
 
Also, download all the NLTK packages to import some of them into the code and install TextBlob for Sentiment Analysis on the text. 

Obtaining of Dataset
--------------

The dataset - Oliver Twist by Charles Dickens- used for this project was sourced the online digitl library, Project Guntenberg.The webpage of the textfile is http://www.gutenberg.org/cache/epub/730/pg730.txt 
It was loaded into the program and the text was opened to be read so that the text contents will be analysed. The text was converted to UTF-8 (8-bit Unicode Transformation Format).

Project Goal
--------------

The goal of this project is to find out the most frequent that was mentioned in the text. Also, this project focuses on revealing the sentiment of the text. 

Code Implememtation
--------------

After loading the text from the web, the text was cleaned for effective analysis so that stopwords, numbers and punctuation marks are removed from the text. Tokenization, splitting of whitespace, normalization (converting text to lowercase), stemming, and lemmatization operations were done on the text. To get the most frequent word mentioned in the text, frequency distribution was performed. The ten most frequent words mentioned in the test and their frequencies were represented on a grap using the Matplot Library and Word Cloud. 
To perform sentiment analysis on the text, Textblob was installed to know the subjectivity and polarity results of the text. Also, SentimentIntensityAnalyzer was imported using Vader to know the sentiment of the text. 

Resources
--------------
Several online resources were used to carried out the text and sentiment analysis of text. The webpages are listed below:

  http://www.nltk.org/
  https://textblob.readthedocs.io/en/dev/
  https://www.datacamp.com/
  https://www.youtube.com/
  
