# Cyberbullying-Detection-using-Data-Augmentation-and-BERT

Developing machine learning model that can detect cyberbullying content from text. Two  common  issues  that  arise  in  cyberbullying detection and natural language processing are the following:

1. **Text Representation:** For text to be used as input for machine learning they need to be converted to a numeric format. There are multiple techniques for accomplishing this such as Bag-of-words, term frequency–inverse document frequency, vector embeddings etc. Researchers have used various techniques to accomplish this with varing degrees of accuracy.

2. **Class Imbalanace:** Usually the non-bullying content in cyberbullying datasets far outnumbers the actual bullying content. Dealing with class imbalances in text is not as straightforward as other data types.

In this project the text is represented using idirectional Encoder Representations from Transformers (BERT), a language model that creates  feature  embeddings  from 
pieces of text. The imbalance is dealt with using Easy Data Augmentation(EDA). EDA uses four techniques on text data to artificially increase the amount of data. They are as follows: 
- **Synonym  Replacement:**  It  randomly  chooses  some  words  in  the  sentence  and  replaces  them  with 
their synonym. 
- **Random Insertion:** It picks a random word in the sentence and inserts a randomly chosen synonym 
of it into a random position in the sentence. 
- **Random Deletion:** It randomly removes a word in the sentence based on a probability value. 
- **Random Swap:** It randomly swaps the position of two words in a sentence.  
