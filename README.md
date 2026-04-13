# NLPExtractiveSummarizationMidterms
Bilingual extractive text summarization system (Indonesian &amp; English) using TF-IDF and Word2Vec

## ▶️ How to Run

### 1. Open in Google Colab
Click the badge below or go to [colab.research.google.com](https://colab.research.google.com),
choose **File → Open notebook → GitHub**, and paste this repository URL.

### 2. Set Up Kaggle API
- Download your `kaggle.json` from Kaggle → Profile → Settings → API
- Upload it when prompted in the notebook's setup cell

### 3. Run All Cells in Order
> Runtime → Run all
- Total expected runtime: **~10–15 minutes** (stemming and Word2Vec training are the slowest steps)
- All libraries are installed within the notebook — no local setup required

---

## 🔧 Libraries Used
| Library | Purpose |
|---|---|
| NLTK | Tokenization, stopword removal |
| spaCy (`en_core_web_sm`) | English lemmatization |
| PySastrawi | Indonesian stemming & stopwords |
| Gensim | Word2Vec training |
| Scikit-learn | TF-IDF vectorization, PCA |
| Matplotlib + WordCloud | Visualizations |
| rouge-score | ROUGE evaluation |
| langdetect | Language detection |

---
