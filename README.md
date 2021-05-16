# Virtual assistants: state of the art and development of a prototype.
Bachelor's thesis

B.Eng. in Computer Engineering - Major in Computing (2016-2020)

## Code 
All the work done during my bachelor's thesis can be found in the following repositories:

- [semantic-similarity](https://www.github.com/pabvald/semantic-similarity): comparison of methods based on pre-trained Word2Vec, GloVe and FastText vectors to measure the semantic similarity between sentence pairs.

- [uva-faqs](https://www.github.com/pabvald/uva-faqs): extracting and processing of the frequently asked questions (FAQs) from the International Relations page and the Doctoral School page of the University of Valladolid in Spanish and English.
- [chatbot](https://www.github.com/pabvald/chatbot) (prototype 1): prototype of a virtual assistant for the International Relations service of the University of Valladolid built with **Flask**, **PostgreSQL**, **spaCy** and **Telegram Messenger**.
- [chatbot2](https://www.github.com/pabvald/chatbot2) (prototype 2): prototype of a virtual assistant for the International Relations service of the University of Valladolid built with **Flask**, **PostgreSQL**, **Dialogflow** and **Telegram Messenger**.



## Abstract 
Nowadays, there are already several virtual assistants such as Amazon Alexa, Microsoft Cortana or Google Assistant, whose use is becoming more and more widespread, both at home and in the workplace. Different sources estimate that the use of this sort of system will increase significantly in the coming years in different sectors, such as healthcare or banking, with the aim of automating various processes. However, virtual assistants still have limitations and are far from matching the conversation provided by a person. 


This project aims to determine what the current state of this technology is, studying and comparing the existing possibilities for building a chatbot. In order to do so, a small study on the main messaging channels, the main frameworks and the main Natural Language Processing (NLP) libraries available for the construction of this type of system has been carried out. Besides, the three most important algorithms to obtain word embeddings (Word2Vec, GloVe and FastText) have been studied; these algorithms play a fundamental role within NLP and getting a reasonable knowledge of them has been one of the purposes of this project.



In addition, with the aim of obtaining a better idea of the possibilities of the available technology, two prototypes of a chatbot have been built for the International Relations service of the University of Valladolid (UVa). While one of the prototypes has been built using the Google's Dialogflow framework, the other one has been built using the Python NLP library spaCy. Once both prototypes were built, a user evaluation of both was performed. The results of this evaluation have enabled to measure the usability of each of the prototypes and the possible improvements to be taken into account when building a system of this type. All in all, the two strategies used for the construction of a chatbot have been compared, identifying the advantages and drawbacks of each one.



## Report (in Spanish) 
See [memoria.pdf](memoria.pdf). 
