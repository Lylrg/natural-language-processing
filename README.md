# NLP Translation Detection Project

![Static Badge](https://img.shields.io/badge/Hugging%20Face%20-555555?logo=Hugging%20Face&logoColor=yellow)
![Static Badge](https://img.shields.io/badge/BERT-555555?logo=Hugging%20Face&logoColor=yellow)
![Static Badge](https://img.shields.io/badge/python-555555?logo=Python&logoColor=green)
![Static Badge](https://img.shields.io/badge/Visual%20Studio%20Code-555555)
![Static Badge](https://img.shields.io/badge/NLP-555555)


## Project Description
Welcome to our NLP Translation Detection Project! In this thrilling (and sometimes baffling) adventure, we embarked on the quest to differentiate between spanish sentences translated by machines and those translated by professional translators. Think of it as our way of saying, "We know your secret, Google Translate!"

We made our own choices and text treatments, trying different features and embeddings to crack the code. Spoiler alert: The Hugging Face transformer BERT model in Spanish was our knight in shining armor.

## Methodology
1. **Data Preprocessing**: Cleaned the text data by removing unnecessary characters, and performed tokenization.
3. **Feature Engineering**: Tried different features such as word count, punctuation frequency count, POS tagging, 
4. **Embeddings**: Tested various embeddings ; TF-IDF, word2vectors, and BERT model.
5. **Model Training**: Trained several machine learning models, including:
   - Logistic Regression
   - Support Vector Machine (SVM)
   - Random Forest
   - Naive Bayes classifier
6. **Model Evaluation**: Selected the SVM model
7. **Prediction**: Used the best model to make predictions on the test set.


## Insights on this Project

As a scientist with feature engineering embedded in my DNA 🥼, I found this aspect of machine learning the most intriguing. I love trying and testing different approaches to see if there's an improvement (or, as is often the case, not) 🤓.

During this project, I experimented with several feature extraction techniques, such as counting male and female pronouns. This was because automatic translations can sometimes introduce errors, like using a male pronoun regardless of the actual gender.

After trying different ways to process text, I realized that in this particular case, less is more—we decided not to lemmatize the text. 

When it came to embeddings, the Hugging Face transformer BERT model in Spanish proved to be a game-changer in this adventure.


