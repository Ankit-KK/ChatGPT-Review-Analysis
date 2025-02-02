# ChatGPT Review Analysis

This project analyzes user reviews of ChatGPT, extracting key insights on user sentiment, common issues, and trends over time. Using **Natural Language Processing (NLP)** and **data visualization**, it identifies areas for improvement and evaluates user satisfaction through **Net Promoter Score (NPS)**.

## 📌 Features
- **Sentiment Analysis**: Categorizes reviews as Positive, Negative, or Neutral using TextBlob.
- **Frequent Phrases Extraction**: Identifies common phrases in positive and negative reviews.
- **User Issues Analysis**: Groups complaints into categories like "Incorrect Answers" and "App Performance."
- **Time-Based Trends**: Tracks sentiment changes over time.
- **Net Promoter Score (NPS)**: Measures user satisfaction and likelihood to recommend ChatGPT.

## 📊 Data & Methods
- **Dataset**: User reviews dataset (`chatgpt_reviews.csv`).
- **Libraries Used**:
  - `pandas`, `seaborn`, `matplotlib` (for data handling and visualization)
  - `TextBlob` (for sentiment analysis)
  - `CountVectorizer` (to extract frequent phrases)

## 🔍 Key Findings
- **Most users are satisfied**: The NPS score is **64.35**, indicating strong user loyalty.
- **Common praises**: Users describe ChatGPT as a “good app,” “best AI,” and “highly recommended.”
- **Top complaints**: Users report **incorrect answers**, **app performance issues**, and **UI difficulties**.
- **Review trends**: Positive reviews peaked in **May 2024**, with stable negative reviews over time.

## 📌 How to Run
1. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn textblob scikit-learn
   ```
2. Run the analysis script:
   ```python
   python chatgpt_review_analysis.py
   ```
3. View the generated plots and insights.

## 📈 Visualizations
- **Sentiment Distribution**: Bar chart of positive, neutral, and negative reviews.
- **Common Phrases**: Word frequency analysis for positive and negative feedback.
- **User Problems**: Horizontal bar chart of common user issues.
- **Trend Over Time**: Line chart showing sentiment changes.

## 📝 Conclusion
This project provides valuable insights into user satisfaction with ChatGPT, highlighting strengths and areas for improvement. The findings can help refine future AI models and enhance the user experience.

---

📢 **Contributions & Feedback Welcome!**  
If you have suggestions, feel free to open an issue or contribute to the repository.
