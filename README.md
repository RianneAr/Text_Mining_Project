# Greek Mythology Project

## Project update 1
So far, we have finished the data acquisition and started the preprocessing. We have also found some sources and started to lay out the structure of the final report.
We created two dictionaries, one with names of Olympian gods and one with mortals, so that we can check whether the characters in the data are gods or mortals. For the preprocessing, we wrote code to tokenize, PoS tag, and lemmatize the data. We also wrote code to check whether there are any characters in the data that don't yet occur in the character dictionaries. Right now, we are going through these names, and adding them to the dictionaries if necessary. The preprocessing is currently done on only the Odyssee, so we plan on going through the same process for the other texts. We are able to keep up with the schedule, and the teamwork is going very smoothly.

## Project update 2
We finished the preprocessing and data exploration where we checked wether there were enough names/ adverbs/ adjectives in the dataset to do a meaningfull analysis. 
The model is slowly but surely coming along. We struggled with getting the sequence of steps in the right order. For example, at first we first filtered all the adjectives and adverbs out of the text and then did word2vec most_similar to godnames and mortalnames, but this gave very similar results. Later we discovered it was better to do word2vec on the whole text and then filter out the adjectives and adverbs. (**Question 1**) Is the latter method better? Some more work needs to be done on finetunign these findings. (**Question 2**) We are debating wether it is a good idea to do weigther counts, as some adjectives/ adverbs are much more common but have less meaning. 

As for the paper, we delved a little deeper into some previous research done and the way that Gods and mortals are characterized, so that once we run our chosen texts through the model, we will be able to easily analyze whether the information collected resonates with the character description from the research. 
We are making good and timely porgress, and the project is taking a much clearer shape. 


## Abstract
This research aims to determine in what way gods and mortals are described in Greek mythology, and how these descriptions differ from each other. In Greek mythology, gods are often portrayed with human traits; they make mistakes, have human-like relationships and feel the same emotions as mortals. We want to know whether this is also reflected in the words used to describe them, or whether there is a very clear distinction between the descriptors of gods and humans. This project will analyze the adjectives and adverbs that describe gods in Greek mythology texts, and compare this with the way that mortal characters are represented. Results show that both mortals and gods are described with mostly positive adjectives and adverbs, even though the words themselves do differ from each other. The individual differences between characters are larger than those between the group of gods and the group of mortals. Future research could further look into the individual differences between characters. 

## Research questions
In what way are Gods portrayed differently than mortals in popular Greek myths? 

## Dataset
In order to create a good overview, we will be studying multiple different myths about Greek gods and mortals from the following text library: https://www.theoi.com/Library.html. This resource contains English translations of many different Greek myths, ordered by era. We will choose one of these eras and use this as our raw data.\
To be able to compare gods and humans, we will first label the characters in the story as either of the two. To this end, we will create a list of humans from Greek mythology, and one of gods. Then, we will go through the texts and label each character as either a god or human. \
To answer the research question, we will use word embedding to compare words in the context of gods and in the context of mortals. We will filter out all words that are not adjectives or adverbs, and then analyze the remaining data.

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
Preprocessing - Rianne\
Data exploration - Rianne\
Model creation and training - Rianne & Savanna\
Analysis - Everyone\
Writing - Leah & Rianne\
Powerpoint - Savanna

## Documentation
The repository consists of the following files:
- Greek Mythology Project Code File.ipynb: The main code file that contains the data acquisition and exploration, and the implementations and interpretations of the models;
- TM Project Greek Mythology.pptx: The powerpoint presentation of our work;
- characterdicts.ipynb: Code that creates a dictionary for mortals and gods;
- goddict.json and mortaldict.json: the saved dictionaries created with characterdicst.ipynb;
- text_file.txt: The raw data.

## Bibliogrpahy
  Karakis. (2019). Neuroscience and Greek mythology. Journal of the History of the Neurosciences, 28(1), 1–22. https://doi.org/10.1080/0964704X.2018.1522049

  Lefkowitz. (2003). Greek gods, human lives : what we can learn from myths. Yale University Press.
  
  Theoi Texts Library. Theoi Classical Texts Library. (n.d.). Retrieved May 5, 2022, from https://www.theoi.com/Library.html 
  
  30 of the Most Famous Tales from Greek Mythology. (2019, December 19). [web log]. Retrieved May 5, 2022, from https://greektraveltellers.com/blog/30-of-the-most-famous-tales-from-greek-mythology. 

