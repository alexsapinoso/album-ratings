# Successful Album or Forgotten: Predicting Album Ratings Using Sentiment Analysis

You can download the dataset here: [Pitchfork Reviews: Music Critiques Over the Years]([https://link-to-your-file](https://www.kaggle.com/datasets/timstafford/pitchfork-reviews/data).

## Project Overview

This project aims to predict album ratings using sentiment analysis on Pitchfork album reviews. By leveraging text mining techniques and machine learning models, we explore the factors that influence whether an album's review is positive or negative.

## Authors

- Alex Sapinoso
- Alison Wilbur
- Sofia Villalpando

## Dataset

The dataset used in this project is "Pitchfork Reviews: Music Critiques Over the Years" from Kaggle. It contains over 25,000 album reviews with various features including artist name, album name, album score, release year, genre, and review text.

## Methods Used

1. **Data Retrieval and Preparation**: Utilized a Kaggle dataset, performed data cleaning, tokenized text, and removed stop words.
2. **Exploratory Data Analysis (EDA)**: Analyzed the distribution of album scores and ratings across genres.
3. **Text Mining and NLP**: Created word clouds and bigrams to identify common terms and phrases.
4. **Sentiment Analysis**: Used the Bing lexicon to extract sentiments from text data and identify frequent positive and negative terms.
5. **Topic Modeling**: Applied Latent Dirichlet Allocation (LDA) to identify natural groups or topics within the reviews.
6. **Cluster Analysis**: Implemented k-means clustering and determined optimal clusters using the Gap Statistic method.
7. **Predictive Modeling**: Built a random forest model to predict high-rated albums, achieving a baseline accuracy of 63.8%.
8. **Visualization**: Created various plots to visualize distributions, sentiments, and bigram networks.

## Results

- **Distribution Analysis**: The median album score is 7.3, with most reviews scoring between 6 and 8.
- **Genre Analysis**: Median scores across genres are similar, indicating no particular genre bias.
- **Sentiment Analysis**: Most reviews have an overall positive sentiment.
- **Topic Modeling and Cluster Analysis**: Reviews can be clustered into groups based on sentiments and topics.
- **Predictive Modeling**: The random forest model achieved a baseline accuracy of 63.8%.

## Conclusion

Our analysis revealed interesting trends in album reviews and demonstrated the potential of sentiment analysis in predicting album ratings. Future work could include trigram analysis and exploring more predictive models to enhance the results.
