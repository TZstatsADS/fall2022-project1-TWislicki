# Applied Data Science @ Columbia
## Fall 2022
## Project 1: A "data story" on the history of philosophy

<img src="figs/archive-nytimes-bridging-the-analytic-continental-divide.jpg" width="500">

image source: https://archive.nytimes.com/opinionator.blogs.nytimes.com/2012/02/19/bridging-the-analytic-continental-divide/

### [Project Description](doc/)
This is the first and only *individual* (as opposed to *team*) project this semester. 

Term: **Fall 2022**

+ Projec title: Exploratory Data Analysis (EDA) on the History of Philosophy: **Veryfing the Assumptions of Continental vs Analytic Debate Using Data**
+ This project is conducted by **Tomasz Wislicki**

+ Project summary: The following is an exploratory investigation of the general trends in the history of philosophy, based on numerical, sentimnet and emotion classification analysis of the following dataset: https://www.kaggle.com/datasets/kouroshalizadeh/history-of-philosophy Following the general, introductory analysis of the whole dataset, I proceed to narrow the scope down to a comparative analysis of the two, arguably, the most influential schools of thought in the 20th century philosophy, namely Continental and Analytic philosophy. 

The jupyter notebook file in the doc/ folder called Project1.ipynb contains all the python code for preprocessing as well as nlp and visual analysis--all commented and explained there via jupyter markdown. **The notebook** is organized as follows:

```
1. Loading and preprocessing data**
2. Exploratory Data Analysis (EDA): Full Dataset**
    2.1 Dataframe Frequency Grouping
    2.2 Frequency and Distibution of Sentence Entries in the Dataset Across Authors and Schools of Thought
        2.2.1 Frequency of Entries Across Authors and Schools of Thought
        2.2.2 Distribution of Entries Across Authors and Schools of Thought
    2.3 Publications Across Time Grouped by Authors and Schools of Thought
    2.4 Sentence Length Across Authors and Schools of Thought
    2.5 Sentence Length and Sentiment Distibution Across Schools of Thought
3. Exploratory Data Analysis (EDA): Analytic vs Continental Schools of Thought
    3.1 Analytic vs Continental Schools of Thought: Bacground and Expectations
    3.2 Preprocessing + Dataframe Frequency Grouping
    3.3 Sentence Length and Sentiment Distibution Between the Two Objects of Comparison
    3.4 Sentence Length Frequency Distribution Between the Two Schools 
    3.5 Compound Sentiment Score Across Time Between the Two Schools 
    3.6 Wordcloud Analysis of the Two Schools of Thought
    3.7 In-Depth Analysis: Emotion classification
        3.7.1 Applying NRCLex Emotion classification Models
        3.7.2 Preprocessing New Data
        3.7.3 Plotting Primary and Secondary Emotion Frequency Across the Two Schhols
4. Conclusion
5. Limitation and Further Work

```


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). **This folder** is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
