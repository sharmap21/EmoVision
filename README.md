# 🎭 EmoVision — AI-Powered Sentiment & Emotion Analysis

> **EmoVision** is an NLP project that detects emotions and sentiment in customer text using machine learning and natural language processing.  
> It processes raw reviews, tweets, and comments to uncover emotional tone, keyword drivers, and brand perception — turning unstructured text into actionable insights.

---

## 🧠 Project Overview

**EmoVision** analyzes the *emotions behind customer opinions*.  
It reads text, interprets sentiment (positive, negative, neutral), extracts emotional patterns, identifies common topics, and compares how people feel about different brands.

In simple terms:

> **EmoVision understands how people feel — and why — by analyzing their words.**

---

## 🧩 Key Features

- 🔤 **Text preprocessing** (cleaning, lemmatization, tokenization)  
- 📊 **Sentiment classification** (Positive / Neutral / Negative)  
- 🎭 **Emotion detection** through NLP  
- 🧵 **Keyword extraction & topic clustering**  
- 🫶 **Brand-wise sentiment comparison**  
- ☁️ **Word cloud generation** (positive & negative emotions)  
- 📉 **Sentiment distribution visualizations**  
- 🧠 **ML models** for classification and clustering  
- 📁 **Exported dashboards & insights**

---

## 🧰 Tech Stack

| Layer | Tools & Technologies |
|-------|----------------------|
| **Languages** | Python |
| **NLP** | NLTK, SpaCy, TextBlob |
| **Modeling** | Scikit-Learn, Logistic Regression, Naive Bayes |
| **Visualization** | Matplotlib, Seaborn, WordCloud, Plotly |
| **Dashboard Output** | PNG reports, CSV sentiment summaries |
| **Documentation** | Jupyter Notebooks |

---

## 🗂️ Project Structure

```
EmoVision/
│
├── notebooks/ # All NLP processing scripts
│ ├── 01_data_preprocessing.ipynb
│ ├── 02_exploratory_analysis.ipynb
│ ├── 03_sentiment_model_training.ipynb
│ ├── 04_brand_comparison_analysis.ipynb
│ └── 05_visualizations.ipynb
│
├── datasets/
│ ├── raw/ # Original text datasets
│ └── processed/ # Cleaned, labeled, ML-ready datasets
│
├── brand_analysis_results/ # Final outputs (CSV summaries & charts)
│ ├── brand_comparison.csv
│ ├── brand_sentiment_summary.csv
│ ├── topic_sentiment_results.csv
│ ├── wordcloud_positive.png
│ ├── wordcloud_negative.png
│ └── sentiment_distribution.png
│
├── outputs/ # Visual exports for documentation
│ └── figures/
│ ├── sentiment_distribution.png
│ ├── top_keywords.png
│ └── brand_comparison_chart.png
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🚀 How It Works

### **1️⃣ Data Preprocessing**
- Remove URLs, emojis, symbols  
- Tokenization  
- Stopword filtering  
- Lemmatization  
- Normalization  

### **2️⃣ Exploratory Data Analysis**
- Sentiment distribution  
- Frequent words  
- Emotion keywords  
- Class imbalance check  
- WordCloud visualizations  

### **3️⃣ Model Training**
Algorithms used:
- Logistic Regression  
- Naive Bayes  
- SVM (optional)  

Outputs:
- Accuracy score  
- Confusion matrix  
- Classification report  
- Predictions saved into CSV  

### **4️⃣ Brand Comparison Analysis**
- Split text by brand keywords  
- Compare overall sentiment  
- Topic-wise emotion mapping  
- Generate CSV and chart outputs  

### **5️⃣ Visualization & Reporting**
Creates:
- Word clouds  
- Sentiment charts  
- Brand comparison graphs  
- Topic sentiment heatmaps  

---

## 📊 Sample Visuals

[Click here for analysis](https://github.com/sharmap21/demo-git/blob/main/dashboard/Sentiment_Analysis_Dashboard.pdf)

---

## Follow these to run

```
git clone https://github.com/<your-username>/<your-repo-name>.git
cd EmoVision

python -m venv venv
source venv/bin/activate       # macOS / Linux
venv\Scripts\activate          # Windows

pip install -r requirements.txt

jupyter notebook

Then open the notebooks in order:

- 01_data_preprocessing.ipynb
- 02_exploratory_analysis.ipynb
- 03_sentiment_model_training.ipynb
- 04_brand_comparison_analysis.ipynb
- 05_visualizations.ipynb
```

---

## 💡 Key Insights

- Emotions around brands vary significantly across topics
- Negative sentiment often clusters around delivery delays or customer service
- Word clouds highlight how strongly certain keywords influence perception
- ML models can predict sentiment with high accuracy after preprocessing
- Topic sentiment helps brands understand what exactly customers love or dislike

---

## 🧠 What You Learn From This Project

- Text cleaning & NLP processing
- Sentiment classification using ML
- Understanding emotional tone in text
- Topic modeling & keyword extraction
- Visual storytelling with charts & word clouds
- Building end-to-end NLP workflow

---

