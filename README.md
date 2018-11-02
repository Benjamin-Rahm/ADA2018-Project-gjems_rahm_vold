# 
Fake News of America
Uncoverning the liars in the political scene in America


# Abstract
_A 150 word description of the project idea, goals, dataset used. What story you would like to tell and why? What's the motivation behind your project?_

# Research questions
- Is there any difference in the lying patterns of the republicans, democrats and independants?
- Is there any difference in the lying patterns at the different political levels (presidents, senators, ...)?
- Are there states where politicians tend to lie more? Is there a noticeable difference between urban and rural states?
- Which subjects are most often ~~subjected~~ to lies?

_A list of research questions you would like to address during the project._

# Dataset
["Liar, Liar Pants on Fire": A New Benchmark Dataset for Fake News Detection](https://www.cs.ucsb.edu/~william/papers/acl2017.pdf) by William Yang Wang, Department of Computer Science, University of California, Santa Barbara

Includes 12,836 short statements labeled for truthfulness, subject, context/venue, speaker, state, and party.
The dataset consists of three tsv-files: train.tsv, valid.tsv, and testing.tsv, used for training, validation, and testing (respectively) of the machine learning models. We expect to use all the tsv-files, and to load the data (3 MB) into a Pandas DataFrame for further processing and analysis.

_List the dataset(s) you want to use, and some ideas on how do you expect to get, manage, process and enrich it/them. Show us you've read the docs and some examples, and you've a clear idea on what to expect. Discuss data size and format if relevant._

# A list of internal milestones up until project milestone 2
- Load the data into a dataframe and initial analysis to get familiarized with the data.
- Extract the information relevant to answer the research questions.
- Find additional data to complement the liar dataset, e.g. state population counts.
- Try different vizualization methods for presenting our data, and select the most efficient one.

_Add here a sketch of your planning for the next project milestone._

# Questions for TAs
None so far.

_Add here some questions you have for us, in general or project-specific._
