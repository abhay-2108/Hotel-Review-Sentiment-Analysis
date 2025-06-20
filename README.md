
# Hotel Review Sentiment Analysis

This project performs sentiment analysis on hotel customer reviews using both rule-based and transformer-based techniques. It helps analyze customer feedback to understand overall satisfaction, identify pain points, and extract valuable service-related insights without requiring custom model training.


## Features

* **Pretrained Model-Based Analysis**
  Uses NLTK's VADER for rule-based sentiment classification and Hugging Face's DistilBERT for transformer-powered sentiment understanding.

* **Dual Sentiment Scoring**
  Each review is analyzed using both VADER (compound score) and DistilBERT (label and confidence score) for comparison.

* **Sentiment Categorization**
  Reviews are categorized as **Positive**, **Negative**, or **Neutral**.

* **Text Preprocessing**
  Basic cleaning, normalization, and preparation of text for analysis.

* **Visualizations**
  Word clouds, sentiment distribution, and common review terms for interpretability.

* **No Model Training Required**
  Fully inference-based system—ideal for real-time or batch feedback analysis.


## Objective

* To classify hotel reviews as Positive, Negative, or Neutral using NLP tools.
* To combine lexicon-based and transformer-based sentiment analyzers for a more accurate understanding.
* To help hotel management identify service strengths and areas for improvement based on customer feedback.

## Tools & Technologies Used

* **Programming Language**: Python 3.10+
* **IDEs**: Jupyter Notebook, VS Code
* **Libraries**:

  * `nltk` (VADER, tokenization)
  * `transformers` (DistilBERT sentiment pipeline)
  * `pandas`, `numpy` (data handling)
  * `matplotlib`, `seaborn`, `wordcloud` (visualizations)


## Approach

1. **Data Collection**

   * Loaded a CSV file containing hotel reviews for analysis.

2. **Text Preprocessing**

   * Basic cleanup including lowercasing and removal of unwanted characters.

3. **Exploratory Data Analysis (EDA)**

   * Visualized review patterns, word frequencies, and sentiment distributions.

4. **Sentiment Analysis - VADER**

   * Applied NLTK’s VADER to assign compound sentiment scores and categorize reviews.

5. **Sentiment Analysis - Transformer (DistilBERT)**

   * Used Hugging Face's sentiment pipeline for context-aware sentiment labels and confidence scores.


## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/abhay-2108/Hotel-Review-Sentiment-Analysis.git
   ```

