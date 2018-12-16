# Uncovering the Liars in the Political Scene of America

## Abstract
In the current era of social media and instant connectivity, the impact of fake news is greater than ever. Not only does it pose a threat to the integrity of journalism, it also creates disturbances and uncertainties in the political world. What's alarming is when people believe what they read, and act upon it. For these reasons, we want to put the spotlight on fake news. More specifically, we will examine the distribution of fake news in the political life of America. In order to achieve this, we will use the liar dataset for fake news detection, created by William Yang Wang. The goal is to find patterns in the generation of fakes news, considering different parties, subjects, and some specific politicians.

The data story can be found [here](https://gjemsvoldrahm.github.io).

## Research Questions
Based on the data analysis we carried out for Milestone 2 and the feedback from our assigned TA, we changed the direction of this project in order to focus more on the statements themselves and what we could get out of them. As a consequence, our aims are now the following:

- Use NLTK (Natural Language Toolkit) and RAKE (Rapid Automatic Keyword Extraction) to analyze the corpus to find key phrases, discover buzzwords, and so on.

- Explore and visualize the data by making a word cloud (using WordCloud).

- Explore the relationships between the speakers with the help of NetworkX to create a directed graph.

- See if there are topics that only republicans, or only democrats, lie about, and which topics that are subjected to lies by both parties.

- Explore the relationships between the 20 politicians with the highest number of lies.

## Dataset
["Liar, Liar Pants on Fire": A New Benchmark Dataset for Fake News Detection](https://www.cs.ucsb.edu/~william/papers/acl2017.pdf) by William Yang Wang, Department of Computer Science, University of California, Santa Barbara

The dataset includes 12,836 short statements labeled for truthfulness, topic, context/venue, speaker, state, and party. It consists of three tsv-files: train.tsv, valid.tsv, and testing.tsv, used for training, validation, and testing (respectively) of the machine learning models. We have chosen to use all the tsv-files, and have loaded the data (3 MB) into a Pandas DataFrame for further processing and analysis.

## A List of Internal Milestones for Project Milestone 2
- __Week 1__: 
  - Load the data into a dataframe and initial analysis to get familiarized with the data.
- __Week 2__:
  - Extract the information relevant to answer the research questions.
  - Find additional data to complement the liar dataset, e.g. state population counts.
- __Week 3__:
  - Try different vizualization methods for presenting our data, and select the most efficient one.

## A List of Internal Milestones for Project Milestone 3
- __Week 1__: 
  - Analyze the corpus with NLTK and RAKE
  - Create the word cloud
  - Make the directed graph with NetworkX
- __Week 2__: 
  - Create a graph in HoloViews showing the relationships between the 20 politicians with the highest number of lies
  - Explore the distribution of topics subjected to fake news between republicans and democrats, and visualize with a Venn diagram
- __Week 3__:
  - Write a data story with Jekyll

## Contributions of the Team Members
- __Benjamin Rahm__: preliminary data analysis, maps with Folium, technical work with Jekyll 
- __Mimmi Gjems__: networks and graphs with NetworkX and HoloViews, word cloud, sentiment analysis
- __Martin Vold__: natural langauage processing with NLTK and RAKE, Venn diagram 

We will all work together on the poster for the final presentation in January. We will decide later who will speak during the presentation. 
