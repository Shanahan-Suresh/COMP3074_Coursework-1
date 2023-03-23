# COMP3074_Coursework-1
This is an information retrieval chatbot trained on a dataset of 1473 questions given in University of Nottingham's Human-AI class lab sessions.

### Table Of Contents:
1. Pre-processing activities
2. Information Retrieving
3. Generalist Features

## 1. Pre-processing Activities
The following activities took place for defining the corpus :
  -  Dropping unrelated columns within the dataset
  -  Tokenizing indidual words and/or phrases
  -  Part-of-speech (POS) tagging
  -  Lemmatization 
  -  Stop-word filtering


## 2. Information Retrieving
- TF-IDF and cosine similarity were used to determine the likeliest answer for any user-given query
- Threshold needed for generating a response was set at a minimum value of 0.15


## 3. Generalist Features
Added to enhanced user experience and apply a more conversationally driven design into the chatbot system.
- **Small Talk via intent matching**
  - Trained to respond to 5 areas of conversation
  - Seperate bag-of-words (BOG) and dataset used from the main information retrival functionality
  - Uses cosine similarity, set at a minimum threshold value of 0.2, which defaults to the information retrieval system if not met

- **Identity Management**
  - Used POS to detect a named identity and stores it for future reference
