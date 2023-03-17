# Character Profiling in Literature through Natural Language Processing
Artificial Intelligence, and especially natural language processing, promises to provide solutions in information extraction from text. Natural language processing can even enable character comprehension. While there have been existing research about character comprehension from various resources, this document reviews on the character profiling through literature. Taking a text classification approach, I propose a new design of literature character profiling system, which can guess speaker’s name by a random given sentence. As profiling will be executed by training the dataset of speaker and dialogue, I have collected datasets from raw text by building the parser and applying natural language processing techniques and predict the speaker with five different classifiers, and have a reasonable degree of success. Finally, I consider how I could modify my character profiling model to increase accuracy and propose potential future directions for the project.


<p align="center">
<img width="214" alt="Picture 2" src="https://user-images.githubusercontent.com/82886152/225987715-f5236383-bc06-4494-bb64-e14cdc5057d3.png">
</p>

## Dataset
Raw text of:
1. A Study in Scarlet by Arthur Conan Doyle
2. Jane Eyre by Charlotte Brontë

## Methodologies
- TF-IDF
- NLP techniques: tokenisation, POS tagging and dependency parsing
- Machine Learning Classifiers: Random Forest, Gaussian Naive Bayes, Multinomial NB, Bernoulli NB and Complement NB




Note: The details can be found from the pdf file uploaded above.
