# 📊 Sentiment Analysis Dashboard

An **interactive NLP-powered dashboard** for sentiment analysis of text data, built using **Python**, **Streamlit**, and **VADER/TextBlob**.  
The app classifies text into **Positive**, **Neutral**, or **Negative** sentiments, visualizes results, and allows real-time user interaction.

---

## 🚀 Features
- **Dataset Sentiment Analysis** – Upload a CSV file of reviews, tweets, or comments and get instant sentiment classification.
- **Sentiment Visualization** – Pie charts, bar graphs, and word clouds for each sentiment category.
- **Real-Time Sentiment Detection** – Enter custom text and see sentiment results instantly.
- **Keyword Insights** – WordCloud for most common positive, neutral, and negative words.
- **Optional Advanced Model** – Hugging Face Transformers for more accurate sentiment detection.

---

## 🛠️ Tech Stack
- **Programming Language:** Python
- **Framework:** Streamlit
- **NLP Libraries:** VADER (NLTK), TextBlob, Hugging Face Transformers (optional)
- **Data Visualization:** Matplotlib, Seaborn, WordCloud
- **Data Handling:** Pandas

---

## 📂 Project Structure
sentiment-analysis-dashboard/
│
├── app.py # Main Streamlit app
├── requirements.txt # Required dependencies
├── data/
│ └── sample_reviews.csv # Sample dataset
├── images/
│ └── wordcloud_positive.png
│ └── wordcloud_negative.png
│ └── wordcloud_neutral.png
└── README.md # Project documentation

yaml
Copy
Edit

---

## 📦 Installation
1. **Clone the repository**
```bash
git clone https://github.com/<your-username>/sentiment-analysis-dashboard.git
cd sentiment-analysis-dashboard
Create a virtual environment (optional but recommended)

bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
▶️ Usage
Run the Streamlit app:

bash
Copy
Edit
streamlit run app.py
📊 Example Output
Pie Chart: Distribution of Positive, Neutral, and Negative sentiments.

Real-Time Input: "I love this product!" → Positive

WordClouds: Most frequent words in each sentiment group.

📌 Dataset
You can use:

IMDb Movie Reviews

Amazon Product Reviews

Twitter Tweets Dataset

Or create your own CSV with a text column.

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
