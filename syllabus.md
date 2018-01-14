## COMM 313: Computational Text Analysis for Communication Research
**Spring 2018: T/Th 1:30-3pm**  
**Room: 225 ASC**  

**Professor**: Dr. Matt O'Donnell  
**Email**: mbod@asc.upenn.edu  
**Office Hours**: Tuesday 11.30am-12.30pm, Thursday 11.30am-12.30pm & by appointment
**Office**: 404 ASC  

## Course Description, Goals and Objectives

In this hands-on course students will learn how to manage large textual datasets (e.g. Twitter, YouTube, news stories) to investigate research questions. They will work through a series of steps to collect,
organize, analyze and present textual data by using automated tools toward a final project of relevant interest.  The course will cover linguistic theory and techniques that can be applied to textual data (particularly from the fields of corpus linguistics and natural language processing).

No prior programming experience is required. Through this course students will gain skills writing Python programs to handle large amounts of textual data and become familiar with one of the key techniques used by data scientists, which is currently one of the most in-demand jobs.

* This course will provide an introduction to Python programming for collecting, preparing and analyzing text data from various sources including
social media (e.g. Twitter), weblogs, online news media and various publicly available archives (e.g. presidential speech achive, congressional sessions).

* Each week one session will be in lecture and seminar form and provide background for the theory and techniques and the second will be a lab session
in which students will work through programming exercises using Jupyter notebooks [A web-based programming environment well suited for data science and class-based assignments].

* By completing this course students will:
	* gain an understanding of relevant linguistic concepts for the analysis of text
	* understand the field of corpus linguistics and how its concepts and tools can be applied to text analysis questions of relevance to Communication
	* be exposed to a range of techniques from natural language processing and understand how they can be used to improve content analyses
	* gain a basic level of programming proficiency in the Python programming language and have completed a number of programming exercises to build, clean and analysis corpora of text

## Textbooks and resources

* The main readings on corpus linguistics will come from:
	* Baker, P. (2006) _Using Corpora in Discourse Analysis_. London: Continuum

* and on Python programming and NLP concepts from:
	* Bird, S., Klein, E. & Loper, E. _Natural Language Processing with Python - Analyzing Text with the Natural Language Toolkit._ Updated version for Python 3. Available free online at http://www.nltk.org/book/


## Assessment

1. **Complete the assigned readings and participation in class discussion (10%)**
	* Readings for each week will be posted on Canvas when electronic versions are available or taken from one of the recommended textbooks.
2. **Attend weekly lab sessions and complete the assigned exercises (40%)**
    * Thursday class sessions will be programming labs. Students are required to bring a laptop that can connect to the ASC network. Please contact the me if this is difficult and we can see if a machine can be made available for use in lab.
	* We will be using Jupyter notebooks to learn Python, which are a web-based interactive programming environment. Assignments will be completed in this and submitted to the instructor. Details of using this system for assignments will be covered in the first lab session.
	* Weekly assignments will be due at 5pm on the Tuesday following lab session (see schedule for details). These assignments are intended to help students practice the programming concepts and structures introduced in lab and build confidence. They should not be difficult or take excessive time but they do build from week to week so it is _very_ important to keep up.
3. **Complete a project that uses the techniques and theory covered in class to carry out a text analysis of a specific research question agreed upon with the instructor (50%)**
    * The goal of this project is to create an engaging blog post similar those produced by data journalists after [State of the Union](https://www.washingtonpost.com/news/monkey-cage/wp/2015/01/21/the-state-of-the-union-address-in-a-single-figure/?utm_term=.1a2854849261) addresses or on a topic like ['How men and women talk about love'](https://www.nytimes.com/interactive/2017/11/07/upshot/modern-love-what-we-write-when-we-write-about-love.html) in the NYTimes recently.
    
    * The steps in the project are: 
         1. Decide upon a tractable research question that involves analysis of textual data, e.g.: 
            * _Did Hillary Clinton's language as candidate change between 2008 and 2016?_
            * _What makes and when is Donald Trump happy (as evidenced on Twitter)?_
            * _What characterises the online media's discussion of poverty/immigration/etc.?_
            * _From smoking to vaping - Examining online testimonials of e-cigarette users_ 
            * _Comparing portrayal of women in rap and country music__
         2. Identify, retrieve and prepare a relevant corpus, e.g. 
            * Clinton 2008 and 2016 campaign speeches 
            * Trumps tweets since 2014
            * Online news coverage of poverty/immigration/..
            * User stories from online vaping forum, etc.)
            * Representative samples of song lyrics
         3. Carry out linguistic analysis of corpus, e.g.
            * Construct comparative frequency lists of 2008 and 2016 speeches by Clinton, identify keywords, collocations and examined and interpret concordance listings
            * Apply approrpriate sentiment analysis techniques to Trump tweet corpus, cluster tweets by sentiment and time, examine distinctive words and phrases
            * Collocation analysis of topic related words (e.g. _poverty, poor, low-income_ or _immigration, immigrants, illegals, illegal aliens_)
            * Create n-gram frequency lists and compare collocations and patterns relating to _smoking_ and _vaping_
            * Examine and compare collocates of words for women between two genres
         4. Visualize data
            * Find appropriate ways to communicate the most important and relevant results from step 3. This might be use a frequency list, concordance listings, a scatter plot of words and phrases, etc. 
         5. Interpret findings
            * How does your text analysis answer your research question?
            * Why and how does it matter?
         6. Write up in a blog post 


            These steps will be scheduled throughout the course allowing for the instructor to help you find a manageable problem, acquire the necessary data and be able to carry out the appropriate computational analysis.
            
     * More details of the kinds of projects that would be appropriate and manageable will be discussed during the first few weeks of class.



## Note about learning programming

A central goal of this class is to help students begin to develop programming skills that they can use to approach questions of interest using the growing amounts of textual data available in the era of 'big data'. But like learning any new skill, such as a new language, it takes time and can be frustrating at first. This course does not require students to have any programming background. Realistically it is not possible to become a fully proficient programmer in just one semester. However, the lab sessions and assignments are focused on helping you begin this process and to become comfortable with reading, understanding and modifying Python code examples that you can find on the web etc.

It is **very important** to attend the lab sessions and to work through the assignments. But if you get stuck do *ask for help sooner rather than later*. Come by my office hours or make an appointment and we can try and come up with ways to help. Every Thursday before the lab sessions from 1.00-1.30pm I will aim to be available to help with programming problems.


## Course Schedule

* **N.B.** - This is a tentative schedule that is subject to change

### Week 1 - Overview
* Thur 01/11/18 - **Course overview**

### Week 2 - Introduction
* Tue 01/16/18 - **Introduction to Corpus Linguistics and NLP** 
	* What are corpus linguistics and natural language processing?
	* Counting words and finding patterns in language

* Thur 01/18/18 - **Lab session 1**: Setting up Python. Jupyter notebooks. First scripts for text analysis

### Week 3 - What is a corpus?
* Tue 01/23/18 - **Types of corpora**
    - **Readings**: _Baker Chs. 1&2_; _NLTK Book Ch. 1 (sections 1, 2 & 4 )_ http://www.nltk.org/book/ch01.html  
    - **Assignment 1 DUE 5pm**

* Thur 01/25/18 - **Lab session 2**: Reading files. Listing directories. Manipulating strings. Loops and Conditions.

### Week 4 - Frequency lists and Concordance Analysis
* Tue 01/30/18 - **How and what to count**
	* Word and N-Gram lists
	* Dispersion
	* Using concordances (Keyword-in-context = KWIC) to find patterns and meaning
    - __Readings__: _Baker Chs. 3&4_; _NLTK Book Ch. 2 (esp. sections 1,2&4 )_ http://www.nltk.org/book/ch02.html
	- **Assignment 2 DUE 5pm**

* Thur 02/01/18 - **Lab session 3**: Creating frequency distributions and KWIC displays. Visualization techniques. Filtering lists.

### Week 5 - Finding, building and using corpora
* Tue 02/06/18 - **Corpus compilation**
    * Extracting text from structured data
	  * Using APIs to compile a corpus (e.g. Twitter)
	  * Web scraping and crawling
    * **Readings**: _Baker Chs. 3&4_; _NLTK Book Ch. 3_ http://www.nltk.org/book/ch03.html
	* **Assignment 3 DUE 5pm**
* Thur 02/08/18 - **Lab session 4**: Extracting text from web pages. Downloading data. Functions.

### Week 6 - Collocation
* Tue 02/13/18 - **Words _have_ friends**
  * Discovering meaning through context
	* Comparing words through collocation
	* Collocation profiles
    * **Readings**: _Baker Ch. 5_; _NLTK Book Ch. 4 (sections 1&2)_ http://www.nltk.org/book/ch03.html
	* **Assignment 4 DUE 5pm**
* Thur 02/15/18 - **Lab session 5**: Data structures. Visualization. Functions.

### Week 7 - Keyness
* Tue 02/20/18 - **Discovering distinctive vocabulary**
  	* 'Aboutness' in text
  	* Kinds of comparison
  	* Statistical significance and association
    * **Readings**: _Baker Ch. 6_; _NLTK Book Ch. 4 (sections 3&4)_ http://www.nltk.org/book/ch04.html
    * **Assignment 5 DUE 5pm**
* Thur 02/22/18 - **Lab session 6**

### Week 8 - Introduction to NLP
* Tue 02/27/18 - **Core concepts and techniques**
    * NLP pipeline
  	* Key tasks: POS tagging, parsing, anaphora resolution, role identification
  	* Example Applications
    * **Readings**: _NLTK Book Ch. 1 (section 5)_ (http://www.nltk.org/book/ch01.html) and _Ch. 5_ (http://www.nltk.org/book/ch05.html)
    * **Assignment 6 DUE 5pm**
* Thur 03/01/18 - **Lab session 7**: Using NLTK; NLP Pipeline

### Week 9 - Spring Break
* Tue 03/06/18 - NO CLASS
* Thur 03/08/18 - NO CLASS

### Week 10 - NLP: Affect and Sentiment analysis #1
* Tue 03/13/18 - **Measuring emotion in text**
* Thur 03/15/18 - **Lab session 8**: Using affect lexicons
  	* **Assignment 7 DUE 5pm**

### Week 11 - NLP: Affect and Sentiment analysis #2
* Tue 03/20/18 - **Sentiment classification**
  	* Supervised machine learning
  	* Building a training corpus
  	* Measuring accuracy
    * **Readings**: _NLTK Book Ch. 6_ (http://www.nltk.org/book/ch06.html)
  	* **Assignment 8 DUE 5pm**

* Thur 03/22/18 - **Lab session 9**: Building a sentiment classifier

### Week 12 - NLP: Named Entity Recognition (NER): Who, what, when and where?
* Tue 03/27/18 - **Identifying actors and actions in text**
  	* **Readings**: _NLTK Book Ch. 7_ (http://www.nltk.org/book/ch07.html)
  	* **Assignment 9 DUE 5pm**
* Thur 03/29/18 - **Lab session 10**: NER and parsed corpora

### Week 13 - NLP: Topic models #1
* Tue 04/03/18 - **Discovering clusters of words in text collections** 
	* **Assignment 10 DUE 5pm**
* Thur 04/05/18 - **Lab session 11**: Topic models and visualization

### Week 14 - NLP: Topic models #2
* Tue 04/10/18 - **Tracing topics over time** 
	* **Assignment 11 DUE 5pm**
* Thur 04/12/18 - **Lab session 12**: Working on projects

### Week 15 - Class projects
* Tue 04/19/18 - **Lab session 13**: Working on projects
* Thur 04/21/18 - **Lab session 14**: Working on projects

### Week 16 - Class projects
* Tue 04/24/18 - **Project presentations**
