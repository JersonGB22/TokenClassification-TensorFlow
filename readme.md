# <h1 align="center">**Token Classification**</h1>

<p align="center">
<img src="images/image_readme.jpeg"> 
</p>

This repository implements Token Classification models, a Natural Language Processing (NLP) task that assigns labels to individual tokens in a sentence. These models are built using TensorFlow and the Hugging Face Transformers library. The architectures are based on [LSTM](https://www.tensorflow.org/api_docs/python/tf/keras/layers/LSTM) networks and the pretrained [BERT](https://huggingface.co/docs/transformers/model_doc/bert) model.

Key applications of token classification include Named Entity Recognition (NER) and Part-of-Speech (PoS) tagging. In real-world scenarios, these tasks are crucial for various applications such as information extraction, text analysis, and language understanding.

## **Use Cases So Far:**

- **Named Entity Recognition:** This model identifies and classifies named entities in a text, such as names of persons, dates, locations, organizations, etc. It has been trained using the [NER dataset from Kaggle](https://www.kaggle.com/datasets/namanj27/ner-dataset), which provides 17 different labels for this task.

- **Part-of-Speech Tagging:** This model recognizes and tags parts of speech, such as nouns, pronouns, adjectives, or verbs, in a given text. It has been trained using a dataset containing 42 labels specifically for this task, also sourced from Kaggle.

## **Some Results of the Predictions**

- **Named Entity Recognition**

<p align="left">
<img src="images/ner/ner_prediction_1.png" style="width: 649px;"> 
</p>

---
<p align="left">
<img src="images/ner/ner_prediction_2.png" style="width: 878px;"> 
</p>

- **Part-of-Speech Tagging**

<p align="left">
<img src="images/pos/pos_prediction_1.png" style="width: 705px;"> 
</p>

---
<p align="left">
<img src="images/pos/pos_prediction_2.png" style="width: 535px;"> 
</p>

#### *Further results from the predictions can be found in their respective notebooks.*

## **Technological Stack**
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)](https://docs.python.org/3/) 
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white&labelColor=101010)](https://www.tensorflow.org/api_docs)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=white&labelColor=101010)](https://huggingface.co/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white&labelColor=101010)](https://scikit-learn.org/stable/)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white&labelColor=101010)](https://plotly.com/)

## **Contact**
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=101010)](mailto:jerson.gimenesbeltran@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101010)](https://www.linkedin.com/in/jerson-gimenes-beltran/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/JersonGB22/)