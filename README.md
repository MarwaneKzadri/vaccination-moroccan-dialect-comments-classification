# vaccination-moroccan-dialect-comments-classification

The lexicon-based (unsupervised) approach uses a sentiment dictionary to score a document by summing the sentiment values of its words. The lexicon includes positive and negative words, created either manually or automatically.

In this project, we implemented a lexicon-based approach to classify opinions on COVID-19 vaccination in Moroccan dialect. This method was chosen to avoid the need for a large labeled training set, which was limited in our case.

Lexicon-based classification assigns sentiment labels by counting the number of positive and negative words in each comment. Each word is associated with a polarity (e.g., 1 for positive, 0 for negative). The dictionaries used can be built manually or automatically, starting from a small set of seed words.

This approach is not only efficient in low-resource settings, but also interpretable and easy to adapt.

---

### 📂 Dataset

The dataset used in this project is available on Kaggle. It contains user comments related to COVID-19 vaccination in Moroccan dialect (Darija), collected from social media platforms such as Twitter, Facebook, and Hespress.

📎 [Link to the dataset](https://www.kaggle.com/competitions/sentiment-analysis-on-moroccan-arabic-dialect/data)

---

### 🏆 Competition Context

This dataset was originally used in a Kaggle competition focused on classifying user opinions about COVID-19 vaccination in Moroccan dialect.  
The code in this repository is the **winner** of that competition, achieving the **best score** in both the **public** and **private** test phases on Kaggle.
