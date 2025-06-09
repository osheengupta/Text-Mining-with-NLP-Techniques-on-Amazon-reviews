# Text Analytics on Amazon Reviews for Greenies Dog Treats

## Project Overview

This project applies natural language processing (NLP) and text analytics techniques to analyze customer reviews of Greenies dog treats sourced from Amazon. Using a dataset of approximately 2,500 reviews extracted from the larger Amazon Fine Food Reviews dataset, the project aims to uncover customer sentiment, identify common themes, and extract actionable insights to help improve product quality, customer satisfaction, and marketing strategies.

---

## Objectives

- Analyze customer reviews specifically for Greenies dog treats using NLP techniques.  
- Determine overall sentiment distribution (positive, neutral, negative) among the reviews.  
- Identify common language patterns associated with satisfaction or dissatisfaction.  
- Discover key topics and themes in both positive and negative reviews via topic modeling.  
- Generate insights to support product improvement, marketing, and customer engagement.  

---

## Dataset

- **Source:** Kaggle - Amazon Fine Food Reviews  
- **Subset:** Reviews mentioning Greenies dog treats (approx. 2,500 records)  
- **Time Frame:** March 2007 - October 2012  
- **Products:** 4 SKUs  
- **Key Columns:** Review text, score, product ID, helpfulness votes, timestamps  

---

## Methodology

1. **Text Preprocessing:**  
   - Lowercasing, removing HTML tags, expanding contractions, tokenization  
   - Removing punctuation, stopwords, numeric values  
   - Lemmatization  

2. **Sentiment Analysis:**  
   - Using VADER to assign sentiment scores and categorize reviews as positive, neutral, or negative  

3. **Word Frequency and N-gram Analysis:**  
   - Identifying frequent words and common bigrams/trigrams in positive and negative reviews to understand customer expression patterns  

4. **Topic Modeling:**  
   - Applying Latent Dirichlet Allocation (LDA) separately to positive and negative reviews to discover key themes  

---

## Key Findings

- **Sentiment Distribution:** 91% positive, 8% negative, 1% neutral  
- **Positive Themes:** Dental health benefits, easy purchasing on Amazon, pet enjoyment  
- **Negative Themes:** Packaging issues, product safety concerns (choking risks), chewability problems  
- **Common Words in Positive Reviews:** love, treat, clean  
- **Common Words in Negative Reviews:** order, chew, box  

---

## Recommendations

- **Product Development:**  
  - Maintain dental health features  
  - Address chewability and size concerns with product variants  
  - Improve ingredient transparency and digestibility  

- **Operations:**  
  - Strengthen packaging and fulfillment processes  
  - Implement freshness indicators  

- **Marketing:**  
  - Use positive customer language in campaigns  
  - Emphasize dental benefits in messaging  
  - Leverage authentic testimonials for trust-building  

---

## How to Run the Project

1. Load the dataset and filter for Greenies dog treats reviews.  
2. Perform text preprocessing using provided scripts/functions.  
3. Apply sentiment analysis with VADER.  
4. Generate word frequency and n-gram statistics.  
5. Conduct topic modeling using LDA.  
6. Visualize and interpret results through charts and tables.  

*(Refer to the Jupyter notebook `Project.ipynb` for detailed code and step-by-step analysis.)*

---

## Dependencies

- Python 3.x  
- pandas  
- nltk  
- vaderSentiment  
- gensim  
- matplotlib  
- seaborn  

---

## Contact

For questions or collaboration, please reach out to:  
**Osheen Gupta** – osheengupta1994@gmail.com
