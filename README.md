# Book Sentiment Analysis

## Analyzing the content of a book, to check whether the content is positive, neutral or negative

### Descriptions

This program takes a book (text file) and does analysis on it, through multiple files. It checks the sentiment of every
chapter, allowing the reader to understand the overall context of the book before reading. Another file uses regex to
break down the book into separate parts and perform analysis on individual chapters.

#### Dependencies

This analysis application uses 2 packages. It uses the ```regex``` package to generate a regex, and then use it on the
book text to extract certain parts of the text for analysis.
This application also uses the ```nltk``` application to perform the sentiment analysis on the targeted text. 