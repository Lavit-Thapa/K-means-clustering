# 🏏 K-Means Clustering on Cricket Player Data

This repository presents a machine learning project that applies the **K-Means Clustering** algorithm to cricket player performance data for unsupervised segmentation. The objective is to group players into distinct clusters based on similar performance metrics, enabling strategic insights for team selection, scouting, and game planning.

## 📊 Project Overview

- **Algorithm**: K-Means Clustering (Unsupervised ML)  
- **Use Case**: Cricket Player Segmentation  
- **Goal**: Identify hidden patterns and segment players into performance-based clusters.

## 🧠 Key Learnings

- Importance of **unsupervised learning** in real-world sports analytics  
- Use of **distance metrics** (Euclidean Distance) to define similarity  
- **WCSS** and the **Elbow Method** for selecting the optimal number of clusters (`K`)  
- Applications in **target strategy**, **team composition**, and **talent identification**

## 📁 Dataset

**File**: `cricket clean.csv`  
The dataset includes cleaned performance statistics for cricket players. Sample columns include:

Player 👤  → The name of the player.

Mat 🏏  → Total number of matches played by the player.

Inns 🎯  → Total number of innings the player has batted in.

NO (Not Outs) 🚫  → Number of times the player remained not out at the end of an innings.

Runs 🏃‍♂️  → Total runs scored by the player in their career.

HS (Highest Score) 🔝  → The player’s highest individual score in a single innings.

0 (Ducks) 🦆 → Number of times the player got out without scoring any runs.

Exp (Experience) ⏳  → The experience level of the player, which can be based on matches played, years active, or any predefined value representing seniority.

## 🛠️ Technologies Used

- Python  
- Jupyter Notebook  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## 📈 Project Steps

1. Load and clean the dataset  
2. Perform exploratory data analysis (EDA)  
3. Apply the K-Means Clustering algorithm  
4. Determine optimal number of clusters using the **Elbow Method**  
5. Visualize the resulting clusters  
6. Interpret cluster characteristics

**📌 Output**
  - Clustered groups of players based on performance metrics

  - Visual insights via scatter plots and elbow graphs

  - Performance-based segmentation ready for further sports analytics

**🤝 Contribution**
Pull requests are welcome. For major changes, please open an issue first to discuss proposed updates or enhancements.

**📬 Contact For inquiries or collaboration opportunities**

: Lavit Thapa – LinkedIn - https://www.linkedin.com/in/lavit-thapa/
