# Auto-Summarizer-of-Articles-on-the-Web
This project focuses on auto-summarizing the articles on internet in a few lines. The code in the project uses python as
a programming language. 
Significant Libraries used to implement:
1. BeautifulSoup: To scrape the web page and scrape all the meaningful texts
2. nltk: Natural Language toolkit. Used for carrying out tokenization of text.

---

**Usage**

The code is written according to the article "https://www.washingtonpost.com/news/the-switch/wp/2015/08/06/why-kids-are-meeting-more-strangers-online-than-ever-before/"
To use it for a different article have a look on it's page source and locate the actual token where the meningful text is present and replace the 'article' word in the
code with the name of the token. Then run:

python implement.py

After it runs, just input the url of the article from the console and you will get the summary of the article.
