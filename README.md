#  Netflix Clustering and Exploratory Data Analysis (EDA)

This project performs an in-depth exploratory data analysis and unsupervised clustering on Netflix's content dataset to uncover hidden patterns, popular content themes, and business insights. By using machine learning techniques like TF-IDF and KMeans, we segment the content into meaningful clusters that can support personalized recommendations, content strategy, and platform optimization.

---

##  Files Included

| File Name                    | Description |
|-----------------------------|-------------|
| `Netflix_Clustering_EDA.ipynb` | Full Jupyter Notebook containing EDA, feature engineering, KMeans clustering, and visualizations |
| `README.md`                 | This file – project overview, structure, and instructions |
| Dataset                     | Not included due to size – link provided below |

---

##  Dataset Source

The dataset used for this project is publicly available on Kaggle:

🔗 [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

**Attributes include:**
- Title, Type (Movie or TV Show)
- Description
- Genre (listed_in)
- Country, Rating, Director
- Date Added, Release Year, Duration

---

##  Key Objectives

- Explore Netflix content using visual analytics
- Understand trends by genre, country, and type
- Clean and preprocess the data for modeling
- Vectorize text data using **TF-IDF**
- Apply **KMeans clustering** to segment content
- Visualize clusters using **PCA**, **Bar Charts**, and **Word Clouds**
- Derive insights that support personalization and business strategy

---

##  Techniques & Tools Used

- `pandas`, `numpy` – data manipulation
- `matplotlib`, `seaborn` – visualization
- `scikit-learn` – TF-IDF, clustering, metrics, PCA
- `wordcloud` – text visualization
- `MultiLabelBinarizer`, `OneHotEncoder`, `StandardScaler` – preprocessing

---

##  Sample Visualizations

- Movies vs TV Shows distribution
- Year-wise content trend
- Top 10 genres
- Country-wise title contributions over time
- Histogram of durations and seasons
- Clustering evaluation (Elbow, Silhouette, DB Index)
- Word Clouds per content cluster
- PCA plot of clusters in 2D

---

##  Business Insights

✅ Drama, International Movies, and Comedies dominate Netflix's catalog  
✅ Most TV shows have short durations (1–2 seasons)  
✅ Optimal content clusters discovered using TF-IDF + KMeans  
✅ Genres and themes visualized using word clouds  
✅ Opportunities to improve catalog diversity by expanding underrepresented genres and countries  

---

##  Business Use Cases

- Personalized content recommendations based on cluster behavior
- Strategic content acquisition & production by analyzing genre and duration trends
- Platform UI enhancements using cluster-based content curation
- Better tagging, filtering, and categorization of titles

---

##  Future Enhancements

- Include user watch history to personalize recommendations
- Try other clustering algorithms (e.g., DBSCAN, HDBSCAN)
- Use advanced NLP models like BERT for deeper text embeddings
- Deploy as a web dashboard using Streamlit or Flask

---

##  How to Run

1. Clone this repo or download the `.ipynb` file
2. Install required libraries (if not using Colab)

```bash
pip install pandas scikit-learn matplotlib seaborn wordcloud
