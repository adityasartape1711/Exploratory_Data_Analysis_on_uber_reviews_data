
# **Uber Reviews Dataset Exploratory Data Analysis**

## **Overview**
This project involves the exploratory data analysis (EDA) of a dataset containing user reviews of the Uber app. The goal is to uncover insights, clean and preprocess the data, and identify trends and patterns that can inform business decisions or improve customer experience.

---

## **Project Description**
The dataset, `uber_reviews_without_reviewid.csv`, contains reviews provided by users on the Uber app. The EDA process includes data cleaning, handling missing values, visualization of user feedback, sentiment analysis, and generating key insights. The project is designed to help understand customer sentiments, identify areas for app improvement, and enhance overall user satisfaction.

---

## **Key Features**
- Data cleaning and preprocessing to handle missing values.
- Analysis of review content to extract frequent terms and insights.
- Visualization of key trends like sentiment distribution and review scores.
- Sentiment classification into positive, negative, and neutral categories.
- Generation of an automated report summarizing the dataset.
- Export of cleaned data for further analysis or modeling.

---

## **Technologies Used**
- **Python Libraries:**
  - `pandas` for data manipulation.
  - `matplotlib` and `seaborn` for data visualization.
  - `nltk` for sentiment analysis and natural language processing.
  - `pandas-profiling` and `sweetviz` for automated EDA reports.
  - `wordcloud` for visualizing frequent terms.
- **Tools:**
  - Jupyter Notebook or any Python IDE for coding.
  - GitHub for version control and project sharing.

---

## **Project Structure**
```
Uber-Reviews-EDA/
│
├── cleaned_uber_reviews.csv            # Cleaned dataset after preprocessing
├── sentiment_distribution.png          # Visualization of sentiment distribution
├── word_cloud.png                      # Word cloud of review content
│   ├── data_cleaning.py                # Script for data cleaning and handling missing values
│   ├── data_visualization.py           # Script for generating visualizations
│   ├── sentiment_analysis.py           # Script for classifying sentiments
│   └── generate_report.py              # Script for generating automated reports
├── README.md                           # Project documentation

---

## **How to Run the Project**
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/Uber-Reviews-EDA.git
   cd Uber-Reviews-EDA
   ```

2. **Run the EDA Scripts:**
   - Execute individual scripts inside the `scripts/` directory.
   - For example:
     ```bash
     python scripts/data_cleaning.py
     python scripts/sentiment_analysis.py
     ```

3. **Generate Reports:**
   - Use `generate_report.py` to create an automated EDA report:
     ```bash
     python scripts/generate_report.py
     ```

4. **View Results:**
   - Open the generated files such as `uber_reviews_eda_report.html` or visualizations like `sentiment_distribution.png`.

---

## **Results**
Key insights obtained from the dataset:
- **Average Review Score:** 4.2
- **Most Frequent Words:** "great," "service," "app," "ride," "time."
- **Sentiment Distribution:** 
  - Positive: 60%
  - Neutral: 25%
  - Negative: 15%
- Lengthy reviews tend to provide higher scores.

Visualizations such as the sentiment distribution and word cloud effectively highlight these findings.

---

## **Future Improvements**
- Implement advanced machine learning models to predict user sentiment.
- Perform topic modeling on reviews for deeper insights into customer feedback.
- Integrate this analysis into a web dashboard for real-time review tracking.
- Extend analysis to other datasets from similar applications for comparison.
