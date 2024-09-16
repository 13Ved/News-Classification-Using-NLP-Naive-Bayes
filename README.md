# News-Classification-Using-NLP-Naive-Bayes
This project aimed to classify news articles into four categories: World, Sports, Business, and Science/Technology. To achieve this, a Naive Bayes classifier was employed, leveraging Natural Language Processing (NLP) techniques for data preprocessing and model enhancement. The project also incorporats Exploratory Data Analysis (EDA) to gain insights into the underlying patterns and characteristics of the data. This includes: <br>

**1. Word Frequency Analysis:** Identifying the most frequently used words within each category to understand the linguistic nuances and key themes associated with each topic. <br>
**2. Word Cloud Visualization:** Creating word clouds to visually represent the distribution of words within each category, providing a more intuitive understanding of the dominant terms. <br>
**3. Word Count Analysis:** Quantifying the occurrence of words within each category to identify statistically significant differences in word usage. <br>

By combining these EDA techniques with the Naive Bayes classifier, the project sought to develop a robust and accurate model capable of classifying news articles into their respective categories based on their textual content.

# Dataset
The AG News dataset is a popular benchmark for text classification tasks, consisting of news articles categorized into four distinct domains: World, Sports, Business, and Science/Technology. This dataset provides a valuable resource for researchers to evaluate the performance of various text classification algorithms and models. With its balanced distribution of articles across categories, large dataset size, and real-world relevance, AG News is widely used in applications such as sentiment analysis, topic modeling, and information retrieval. However, it's important to consider potential challenges like class imbalance and data quality when working with this dataset. <br>
**Link:** https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset

# Objective

**1. Develop a robust text classification model:** <br>

Build a highly accurate model capable of effectively classifying news articles into the four predefined categories (World, Sports, Business, Science/Technology).
Ensure the model generalizes well to unseen data, demonstrating its effectiveness in real-world scenarios. <br>

**2. Conduct exploratory data analysis (EDA):** <br>

Gain a deeper understanding of the dataset by visualizing the distribution of categories, word frequencies, and other relevant features.
Identify any potential biases or imbalances in the data that may affect model performance.
Use EDA insights to inform feature engineering and model selection decisions. <br>

**3. Optimize model performance:** <br>

Experiment with different NLP techniques and machine learning algorithms to identify the most suitable approach for this task.
Fine-tune model parameters and hyperparameters to enhance accuracy and efficiency.
Explore techniques such as feature engineering, dimensionality reduction, and ensemble methods to improve model performance. <br>

**4. Evaluate model effectiveness:** <br>
Employ appropriate evaluation metrics (e.g., accuracy, precision, recall, F1-score) to assess the model's performance comprehensively.
Conduct a thorough analysis of the model's strengths, weaknesses, and potential biases.
Identify areas for improvement and explore future research directions.

# Model Development
The model used in this project is the Naive Bayes classifier. It's a probabilistic classifier based on Bayes' theorem, which assumes that the features (words) are conditionally independent given the class (category). This means that the probability of a word appearing in a document is independent of the presence of other words in the document, given the document's category. <br>

The Naive Bayes classifier calculates the probability of a document belonging to each category by multiplying the probabilities of each word appearing in that category. The document is then assigned to the category with the highest calculated probability. <br>

While the assumption of conditional independence is often violated in real-world text data, the Naive Bayes classifier still performs surprisingly well due to its simplicity and robustness. It's a popular choice for text classification tasks due to its efficiency and interpretability.

# Conclusion
The Naive Bayes classifier, in conjunction with effective NLP techniques and EDA, demonstrated remarkable performance in classifying news articles into the four categories: World, Sports, Business, and Science/Technology. The model achieved an impressive overall accuracy of 90%, indicating its ability to accurately predict the category of news articles with a high degree of confidence. <br>

It's important to note that the exceptionally high accuracy achieved in this project may be partially attributed to the synthetic nature of the dataset. Synthetic datasets often exhibit more regular patterns and less noise compared to real-world data, which can contribute to higher model performance. However, the model's strong performance on this dataset suggests its potential for effective classification in real-world scenarios, provided that the data quality and distribution are comparable. <br>

Future research could explore the application of this model to larger and more diverse news article datasets, incorporating factors such as temporal trends, author information, and contextual cues to further enhance classification accuracy and robustness. Additionally, investigating the impact of different NLP techniques, feature engineering approaches, and machine learning algorithms could provide valuable insights into the limitations and potential improvements of this model. <br>
