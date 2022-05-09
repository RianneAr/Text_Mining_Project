# Greek Mythology Project

## Project update 1
So far, we have finished the data acquisition and started the preprocessing. We have also found some sources and started to lay out the structure of the final report.
We created two dictionaries, one with names of Olympian gods and one with mortals, so that we can check whether the characters in the data are gods or mortals. For the preprocessing, we wrote code to tokenize, PoS tag, and lemmatize the data. We also wrote code to check whether there are any characters in the data that don't yet occur in the character dictionaries. Right now, we are going through these names, and adding them to the dictionaries if necessary. The preprocessing is currently done on only the Odyssee, so we plan on going through the same process for the other texts. We are able to keep up with the schedule, and the teamwork is going very smoothly.

## Abstract
(This is a first draft of our abstract, with the main idea of our project and our motivation for it. It is subject to change as it will be updated as the project unfolds.)\
In this project, we aim to determine in what way gods and mortals are described in Greek mythology, and how these descriptions differ from each other. In Greek mythology, gods are often portrayed with human traits; they make mistakes, have human-like relationships and feel the same emotions as mortals. We want to know whether this is also reflected in the words used to describe them, or whether there is a very clear distinction between the descriptors of gods and humans.\
This project will analyze the adjectives and adverbs that describe gods in Greek mythology texts, and compare this with the way that mortal characters are represented. 
We decided to work on Greek mythology because of our interest in Greek myths, and thought that analyzing these myths would be a great application of the material from class. 

## Research questions
In what way are Gods portrayed differently than mortals in popular Greek myths? 

## Dataset
In order to create a good overview, we will be studying multiple different myths about Greek gods and mortals from the following text library: https://www.theoi.com/Library.html. This resource contains English translations of many different Greek myths, ordered by era. We will choose one of these eras and use this as our raw data.\
To be able to compare gods and humans, we will first label the characters in the story as either of the two. To this end, we will create a list of humans from Greek mythology, and one of gods. Then, we will go through the texts and label each character as either a god or human. \
To answer the research question, we will use an n-gram model so that we can focus on the words close around the characters. We will filter out all words that are not adjectives or adverbs, and then analyze the remaining data.

## A tentative list of milestones for the project
April 21 Project update 0: \
repository README up.  \
research question, dataset, methods, milestones, proposed division of work. Please use the repository README template.\

May 9 Project update 1 (see below for guidelines).\
Data acquisition , finding sources, preprocessing , start model creation and training\

May 19 Project update 2 (see below for guidelines).\
Finish Model creation and training, perform data analysis, start writing paper, start making powerpoint \

May 29 (23:59 CEST) Project due for all groups.\
May 30-June 2 In-class presentations: 10+10 minutes (presentation + questions), schedule to be published in advance.

## Task division
Data acquisition - Savanna \
Finding sources - Leah\
Preprocessing - Rianne & Savanna\
Model creation and training - Everyone\
Analysis - Everyone\
Writing - Leah & Rianne\
Powerpoint - Savanna

## Documentation
Once our repo contains more files and data, we will explain its structure here.

## Bibliogrpahy
  Karakis. (2019). Neuroscience and Greek mythology. Journal of the History of the Neurosciences, 28(1), 1–22. https://doi.org/10.1080/0964704X.2018.1522049

  Lefkowitz. (2003). Greek gods, human lives : what we can learn from myths. Yale University Press.
  
  Theoi Texts Library. Theoi Classical Texts Library. (n.d.). Retrieved May 5, 2022, from https://www.theoi.com/Library.html 
  
  30 of the Most Famous Tales from Greek Mythology. (2019, December 19). [web log]. Retrieved May 5, 2022, from https://greektraveltellers.com/blog/30-of-the-most-famous-tales-from-greek-mythology. 

