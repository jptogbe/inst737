
 This is for class project in INST737.

# Data source

source: https://data.stackexchange.com
 
Brief explanation of database is here: https://meta.stackexchange.com/questions/2677/database-schema-documentation-for-the-public-data-dump-and-sede


# Example data files to work with

For project ideatons, please refer to the example files (.csv). The brief description of each file can be found as below:

* posts

Contains information of each post (a thread of a question & answer(s))

* Users

Contains information of each user in Stack Overflow

* Comments

Contains information of each comment attached to either a question or an answer

* Badges

Contains information of each badge awarded to a user for the one's contribution to the site

* Tags

Contains information of each tag associated with a post. A post may have multiple tags. 


*These datasets are taken from Stack Overflow only.*


---

Below are the list of papers that you might find helpful for brainstorming. 

## Reference papers

* ICWSM2017
* Min(e)d Your Tags: Analysis of Question Response Time in StackOverflow
https://pdfs.semanticscholar.org/312d/a6ff7dc3aa104493e3c8e7be8313020f16bd.pdf

* From the paper titled: `Discovering values~~~`

27 features used

> Questioner features (SA), 4 features total: questioner repu- tation, # of questioner’s questions and answers, questioner’s percentage of accepted answers on their previous questions.

> Activity and Q/A quality measures (SB ), 8 features total: # of favorites, # of page views, # positive and negative votes on question, # of answers, maximum answerer reputation, high- est answer score, reputation of answerer who wrote highest- scoring answer,

> Communityprocessfeatures(SC),8featurestotal:average answerer reputation, median answerer reputation, fraction of sum of answerer reputations contributed by max answerer
reputation, sum of answerer reputations, length of answer by highest-reputation answerer, # of comments on answer by highest-reputation answerer, length of highest-scoring an- swer, # of comments on highest-scoring answer.

> Temporal process features (SD), 7 features total: average time between answers, median time between answers, min- imum time between answers, time-rank of highest-scoring answer, wall-clock time elapsed between question creation and highest-scoring answer, time-rank of answer by highest- reputation answerer, wall-clock time elapsed between ques- tion creation and answer by highest-reputation answerer.

## Examplary NLP analyses
=======

### For text summarization&classification

-Extracting Sentence Segments for Text Summarization: A Machine Learning Approach
https://dl.acm.org/citation.cfm?id=345566

-BOOK: Learning to Classify Text Using Support Vector Machines: Methods, Theory, and Algorithms
https://dl.acm.org/citation.cfm?id=1105708

-Thumbs up?: sentiment classification using machine learning techniques
https://dl.acm.org/citation.cfm?id=1118704


## Other NLP analyses (not in papers, but in articles or other sources)

1. 2015 presidential debate [link](https://alexperrier.github.io/jekyll/update/2015/11/12/nlp-analysis-presidential-debates.html)

2. Topic modeling of Stack Overflow questions [link](https://www.r-bloggers.com/text-mining-of-stack-overflow-questions/)

## ML methods / Techniques

* Which algorithm to solve my problem? [link](https://blogs.sas.com/content/subconsciousmusings/2017/04/12/machine-learning-algorithm-use/)
