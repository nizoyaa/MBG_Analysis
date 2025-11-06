# 🥗 MBG_Analysis — Topic Modeling & Trend Visualization

This repository contains the results of topic modeling and temporal trend analysis of online news articles related to the *Makan Bergizi Gratis (MBG)* program in Indonesia.  
The analysis aims to uncover the main discussion themes and how public attention towards MBG-related topics evolves over time.

---

## 📊 Project Overview
This project uses **Latent Dirichlet Allocation (LDA)** to identify dominant topics in MBG-related news data, followed by **trend visualization** to monitor topic fluctuations over time.

### Objectives:
- Identify the main topics within MBG-related online news.
- Automatically label each news item with a relevant topic.
- Visualize the temporal distribution and highlight media focus patterns.

---

## ⚙️ Workflow
1. **Preprocessing**
   - Text cleaning, case folding, stopword removal, and stemming.
2. **Topic Modeling (LDA)**
   - Extracts latent topics using `sklearn.decomposition.LatentDirichletAllocation`.
3. **Auto Labeling**
   - Assigns topic names automatically based on keyword interpretation.
4. **Trend Visualization**
   - Plots topic frequency over time (line chart and heatmap).

---

## 🧠 Topics Discovered
| Topic | Label | Description |
|--------|--------|-------------|
| Topic 0 | Program Gizi Sekolah / Makan Gratis | News on school feeding programs and government initiatives |
| Topic 1 | Kasus Keracunan Makanan | Coverage of food poisoning incidents and health responses |
| Topic 2 | Kandungan Makanan & Kesehatan | Discussion on food safety, nutrition, and bacterial contamination |
| Topic 3 | Program Pemerintah & Gizi Nasional | National policies, ministers’ statements, and implementation updates |
| Topic 4 | Anggaran & Ekonomi Program Pangan | Reports related to budget allocation and program funding |

---

## 📈 Trend Visualization
Visualization results show the dynamic evolution of topics:
- The topic **“Kasus & Korban”** peaked sharply in **early November 2025**, reflecting intense media coverage.
- Program-related discussions show consistent growth across months, indicating ongoing policy attention.

---

## 🧩 Repository Structure
MBG_Analysis/
│
├── MBG_TopicModeling.ipynb # Main notebook for preprocessing, LDA, and auto labeling
├── hasil_LDA_auto_label.csv # Final auto-labeled dataset
├── Distribusi_Topik_LDA_MBG.png # Bar chart of topic distribution
├── Trend_Visualization.png # Time-based topic trend chart
├── README.md # Project documentation
└── data/ # (Optional) Preprocessed or raw data files


---

## 🚀 Deployment
### Deployment Forms:
- Topic trend visualization (line/heatmap charts)
- Analysis notebook shared via GitHub
- Optional dashboard integration

### Outcome:
Provides **insights into the MBG news landscape in Indonesia**, supporting both **policy analysis** and **media trend monitoring**.

---

## 🧰 Tools & Libraries
- Python 3.10+
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- WordCloud

---

## 👩‍💻 Author
**Anisa Nur Eka Putri**  
Universitas Negeri Malang  
📬 [LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/nizoyaa)

---

## 📜 License
This project is shared for academic and portfolio purposes only.  
Please provide attribution if reused.

