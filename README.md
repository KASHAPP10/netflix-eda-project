# Netflix Content Strategy: EDA and NLP Case Study

This project presents a data-driven analysis of Netflix’s global content catalog using the publicly available Netflix Titles dataset from Kaggle. It aims to explore business-critical questions that impact content acquisition, regional strategy, and user engagement.

---

## 🎯 Business Objectives

- **Understand Netflix's Global Content Footprint:**  
  Identify which countries dominate Netflix’s offerings and how that aligns with international growth strategies.

- **Analyze Shifts in Content Focus Over Time:**  
  Quantify whether Netflix is moving toward more episodic content (TV Shows) over standalone content (Movies) — and what that means for platform engagement.

- **Reveal Patterns in Content Descriptions:**  
  Use Natural Language Processing (TF-IDF + Cosine Similarity) to identify clusters of similar content — a foundational step in building smarter recommendation systems.

- **Build Foundations for Actor/Director Networks:**  
  Explore co-occurrence relationships across cast members to lay the groundwork for collaboration networks or casting analytics.

---

## 🛠️ Technical Highlights

- 🧹 Cleaned and structured 8,000+ Netflix titles  
- 📅 Converted and extracted time trends from messy date formats  
- 🌍 Aggregated and visualized country-wise content distribution  
- 🧠 Applied **TF-IDF vectorization** + **cosine similarity** to detect related titles  
- 📊 Built visual reports using **pandas**, **matplotlib**, and **seaborn**

---

## 🔍 Sample Insights

- The **United States, India, and the UK** dominate Netflix’s catalog — but there's fast growth in non-English-speaking countries post-2017.
- Netflix has **shifted heavily toward TV Shows** since 2018, potentially signaling a retention-focused strategy through longer-form content.
- NLP-based analysis of descriptions revealed **clusters of genre-specific content** not captured in traditional categories.
- Missing data in fields like `director` and `country` follows **non-random patterns** — offering potential signals for budget/production strategy.

---

## 🧰 Tools Used

- Python (pandas, numpy)
- Visualization: matplotlib, seaborn
- NLP: Scikit-learn (TF-IDF, cosine similarity)
- Notebook environment: Jupyter / Kaggle Notebooks

---

## 📁 Dataset

Kaggle: [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 💡 For Stakeholders

This project simulates a real-world scenario in which a **content strategy team or data science unit** would investigate:
- Where to invest in content next
- Which regions are underserved
- How similar content performs across geographies
- How user-facing systems (like recommendation engines) could be enriched using unstructured data

---

## 👀 Live Preview (Screenshots)

<img src="screenshots/top_countries.png" width="600">
<img src="screenshots/movies_vs_shows_over_time.png" width="600">
<img src="screenshots/description_similarity_map.png" width="600">

---

## 📈 Future Improvements

- Integrate viewership or performance data (if available)  
- Deepen actor/director network graph using `networkx` or Neo4j  
- Turn this EDA into a live Streamlit dashboard for executives

---

## 🚀 Author

**Avinash Parimeru**  
Aspiring Data Scientist | Research & Business Strategy | [LinkedIn](https://www.linkedin.com)

---

