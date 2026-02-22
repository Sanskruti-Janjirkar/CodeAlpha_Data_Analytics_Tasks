# Task 4: Sentiment Analysis on Best-Selling Books Dataset

## Objective
The objective of this task is to perform sentiment analysis on textual data and classify it as Positive, Negative, or Neutral.  
The project aims to understand sentiment patterns and their relationship with book ratings using NLP techniques.

---

## Dataset
- Dataset: Best Selling Books 2023
- Features used: Book Name, Rating, Genre, Price

---

## Methodology

1. Data Cleaning and Preprocessing  
   - Loaded dataset using Pandas  
   - Checked for missing values and cleaned text data  

2. Sentiment Analysis  
   - Used the VADER Sentiment Analyzer from NLTK  
   - Calculated sentiment scores for each book title  
   - Classified sentiment into Positive, Negative, and Neutral  

3. Data Visualization  
   - Sentiment distribution bar chart  
   - Rating vs Sentiment visualization  
   - Genre-wise sentiment analysis  
   - Dashboard combining multiple plots  

---

## Tools and Technologies Used
- Python  
- Pandas and NumPy  
- Matplotlib and Seaborn  
- NLTK (VADER Sentiment Analyzer)  
- Google Colab  

---

## Key Insights
- Most book titles showed positive or neutral sentiment.  
- Very few titles had negative sentiment.  
- There was no strong relationship between sentiment and book ratings.  
- Sentiment based on titles alone provides limited emotional context.  

---

## Data Limitations
Due to the unavailability of full review text in the dataset, **book titles were used as textual input for sentiment analysis**.  
This approach limits the accuracy of sentiment detection because titles are short and may not reflect readers’ actual opinions.  
Using full customer reviews would provide more reliable sentiment insights.

---

## Conclusion
This project demonstrates the application of NLP techniques for sentiment analysis using the VADER lexicon.  
Although book titles were used due to data constraints, the task successfully shows how sentiment analysis can be applied to real-world datasets and how sentiment trends can be visualized for decision-making.

---

## Author
Sanskruti Sanjay Janjirkar  
CodeAlpha Data Analytics Internship Task 4
