# Review Sentiment Analysis 

This project analyzes **1,000 customer reviews of British Airways** to understand passenger sentiment and uncover key themes in feedback.  
It demonstrates skills in **web scraping, text preprocessing, sentiment analysis, topic modeling, and visualization**.

---

## 📌 Project Overview
- Scraped **1,000+ reviews** from [airlinequality.com](https://www.airlinequality.com/airline-reviews/british-airways) using `requests` and **BeautifulSoup**.  
- Cleaned and preprocessed text with **regex, stopwords removal, and lemmatization**.  
- Conducted **sentiment analysis** with NLTK’s **VADER**:
  - Positive → 535  
  - Negative → 444  
  - Neutral → 21  
- Applied **Latent Dirichlet Allocation (LDA)** to uncover topics like *boarding experience, staff service, class/seat comfort, and food quality*.  
- Created **word clouds and frequency plots** to visualize common keywords and trends.  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** BeautifulSoup, Requests, Pandas, NLTK, Scikit-learn, Matplotlib, WordCloud  
- **Techniques:** Web Scraping, Text Cleaning, Sentiment Analysis (VADER), Topic Modeling (LDA), Visualization  

---

## 📊 Key Results
- **Sentiment distribution:**  
  - ~54% Positive, ~45% Negative, ~2% Neutral  
- **Top 5 Topics Identified via LDA:**  
  1. Boarding process and flight timing  
  2. Crew service, food, and business class experience  
  3. Airline operations, delays, customer service  
  4. Economy vs. business class comfort  
  5. Staff behavior, cabin crew, and in-flight service  

---

## 📸 Sample Visualizations
- **Word Cloud of Customer Reviews**  
- **Top 20 Most Common Words (Bar Plot)**  

*(See notebook for visual outputs)*

---

## 🔮 Future Improvements
- Build a **Streamlit dashboard** for interactive review analysis.  
- Experiment with **transformer models (BERT/DistilBERT)** for more advanced sentiment classification.  
- Extend scraping to **multiple airlines** for industry-wide insights.  

---

## 👩‍💻 Author
**Mahak Chauhan**  
📧 [cmahak35@gmail.com](mailto:cmahak35@gmail.com)  
🌐 [GitHub](https://github.com/Mahak732)  
