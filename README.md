# 📚 AI-Based Book Recommendation System

An intelligent book recommendation system that combines **Collaborative Filtering** and **Content-Based Filtering** to personalize book discovery. Developed as part of an academic project at **California State University, Long Beach**.

---

## 🚀 Features

- **Hybrid Recommendation Engine**: Merges **User-Based Collaborative Filtering** and **Content-Based Filtering** for precise recommendations.
- **Analyzed 100,000+ books** from **Goodreads**, leveraging **KNN & Cosine Similarity**.
- **Addressed Cold Start & Data Sparsity**: Implemented hybrid models to mitigate recommendation limitations.
- **Explored Sentiment Analysis**: Enhanced recommendation quality using NLP techniques.

---

## 📂 Dataset

The dataset used for this project can be accessed here: [Goodreads Book Dataset](https://csulb-my.sharepoint.com/:u:/r/personal/akshaya_tonde01_student_csulb_edu/Documents/Deep%20learning%20Sem%203/Deep%20Learning/Surreal%20Symphonies%20(A%20dataset%20of%20Diverse%20Artistic%20Visions)-20241206T070138Z-001.zip?csf=1&web=1&e=x2tm8C)

---

## 🛠 Technologies Used

- **Collaborative Filtering (User-Based & Item-Based)**
- **Content-Based Filtering** (TF-IDF, Cosine Similarity)
- **K-Nearest Neighbors (KNN) Algorithm**
- **Sentiment Analysis for Reviews**
- **Python Libraries**: `pandas`, `numpy`, `scikit-learn`, `NLTK`, `Flask` (for future deployment)

---

## 📌 Implementation

### 1️⃣ Collaborative Filtering
- Used **User-Based Filtering** to recommend books based on similar reader preferences.
- Tackled **cold start issues** by integrating item-based filtering.

### 2️⃣ Content-Based Filtering
- Leveraged **TF-IDF and Cosine Similarity** to match books based on their descriptions, genres, and author similarities.

### 3️⃣ Sentiment Analysis (Experimental)
- Analyzed book reviews to **understand reader sentiments**, enhancing recommendations beyond numerical ratings.

---

## 🛠 Installation & Setup

Clone the repository:
```bash
git clone https://github.com/your-username/ai-book-recommendation.git
cd ai-book-recommendation
```

Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 🎯 Running the Model

To generate recommendations, run:
```bash
python recommend.py --user_id 12345
```

To test content-based filtering:
```bash
python recommend.py --book "The Catcher in the Rye"
```

---

## 📈 Evaluation

Evaluate the model using:
```bash
python evaluate.py
```

This script calculates **Precision@K, Recall@K, and RMSE** for recommendation quality assessment.

---

## 🌟 Future Scope

- **Real-time AI-powered recommendations** for dynamic user interaction.
- **Cross-domain suggestions** (Movies, Music, and Books integration).
- **Scalable deployment** using **Flask/FastAPI & Cloud Services**.

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 📩 Contact

For any inquiries or collaborations, reach out at **your-email@example.com**.

---

⭐ **If you found this project useful, don't forget to star this repo!** ⭐
