### Email Spam Detection with Machine Learning

This project focuses on the development of a machine learning model capable of accurately identifying spam emails. Utilizing a dataset of email messages that have been labeled as either ham or spam, the model learns to distinguish between these two categories. This project aims to enhance email filtering techniques and provide a reliable tool for maintaining the integrity of inboxes by minimizing unwanted messages.

![email](https://github.com/ShubhamKumbhar28/OIBSIP/assets/133940544/90c02d4e-69d5-49ca-8be1-f7627677a86e)

### Dataset

The dataset used in this project consists of email messages with the following attributes:

- Email Text (v2) : The body text of the email.
- Label (v1) : Whether the email is ham or spam 

link : https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

### Machine Learning Model
This project employs GaussianNB ,BernoulliNB ,MultinomialNB
for spam detection. The text data is preprocessed and transformed into a suitable format (e.g., TF-IDF vectors) for model training.

### Requirements

List the libraries and their versions required to run the project

- Python >= 3.7
- NumPy
- Pandas
- scikit-learn
- matplotlib / seaborn (for data visualization)
- NLTK (for text preprocessing)
