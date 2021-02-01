
# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2: Ames Housing Data

### Problem Statement
Do varying classification models misidentify similar subsets of data when predicting whether a post will belong to r/Plants or r/Cats subreddits? Or do the subsets of misidentified posts vary by model?

---
### Background Research

When selecting models to use for classifying language data, different models perform differently. When beginners start to use and score models, it may be a missconception that the errors in each model overlap. That is to say that when selecting models with smaller scores, each error in that model is also found in the error of the worse performing model. I used this project to explore that assumption, and identify which posts were the most difficult for a machine learning model to identify and classify correctly.

This project focuses on two subreddits, r/Plants and r/Cats. Both subreddits are primarily comprised of photo posts, with minimal text in the submission itself. 10,000 posts were pulled using Pushshift's API for reddit in order to 


---
### Datasets Used


---

### Data Dictionary



---

### Analysis Summary

The title text from 10,000 reddit posts were tokenized using RegexpTokenizer in order to remove punctiuation before lemmatizing the text data to reduce variability due to the word's inflection in the original sentence. The data was then split into training and test datasets before handing off to one of ten models. Each model was a permutaition of either CountVectorizer or TIDIFVectorizer to transform the data and one of five classification models to classify the 

---

### Conclusions & Considerations


---

### Sources Cited:

