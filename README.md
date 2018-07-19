# GoodReads project


This repository is for the project we made for Bertelsmann Data Science Scholarship Program: Phase 1. 

There are 3 of us in the team: 
- Ana Makarevich (<a href="https://www.linkedin.com/in/ana-makarevich/">LinkedIn</a>)
- Nesreen Sada (<a href="https://www.linkedin.com/in/nisreinsada/">LinkedIn</a>)
- Peter Lipp (<a href="https://www.linkedin.com/in/peter-lipp-0338498/">LinkedIn</a>)

It all started with a <a href="https://www.goodreads.com/group/show/603467-bertelsmann-data-science-book-readers">thread in the Udacity Forum (only accessible if you're a member!)</a>. Our fellow classmates were discussing their favourite books. This discussion soon resulted 
in an separate group on GoodReads. Looking at the group we got intrigued:  

<b>Are we special? Do we differ from other groups on GoodReads? </b>

We especially wanted to know, if the books favoured in our group differ from books featured in other book clubs?
Our key hypothesis for this project was: are Udacians inclined to read and recommend non-fiction literature more often than other groups.


The project consisted of several stages:

<h2>Stage 1: Data extraction and feature selection</h2>

At this stage we collected the data from GoodReads for 4 book clubs: 
- <a href="https://www.goodreads.com/group/bookshelf/603467-bertelsmann-data-science-book-readers">Bertelsmann Data Science book readers (that's ours!)</a>
- <a href ="https://www.goodreads.com/group/show/153138-gone-with-a-book">Gone with a Book</a>
- <a href ="https://www.goodreads.com/group/show/153782-pop-sugar-s-annual-ultimate-reading-challenge">Pop Sugar's Annual Ultimate Reading Challenge</a>
- <a href="https://www.goodreads.com/group/show/36119-reading-with-style">Reading with Style</a>

We cleaned the data and selected features using GoodReads API. The details were described by Nesreen and can be found <a href="https://github.com/AnaMakarevich/goodreads_project/blob/master/Goodreads%20Data%20Extraction%20.ipynb">here</a>

<h2>Stage 2: Database design and environment setup</h2> 

We wanted to have one single environment for the whole team and so since Ana had access to AWS with free-tier options, we decided to use that opportunity to learn about AWS as well. 
We've set up a EC2 instance to run Jupyter Hub with separate login and folder for each team member, but with single shared environment. 
Then we've also set up an RDS instance to run MySQL and store our data. The full desciption of the database design can be found <a href="https://github.com/AnaMakarevich/goodreads_project/blob/master/Goodreads%20database.ipynb">here</a>. 

<h2>Stage 3: Exploratory analysis and visualisation</h2> 

This stage included makind basic exploratory analysis and making visualisations. The core notebook for analysis can be found <a href="https://github.com/AnaMakarevich/goodreads_project/blob/master/Data%20analysis.ipynb">here</a>. Additional descriptive analysis dedicated to the year the book was first published can be found <a href="https://github.com/AnaMakarevich/goodreads_project/blob/master/Books%20by%20year%20viz.ipynb">here</a>.
And the summary visualisation that we used for our final slide can be found <a href="https://github.com/AnaMakarevich/goodreads_project/blob/master/Basic%20Analysis%20and%20Data%20Visualisation.ipynb">here</a>. 



