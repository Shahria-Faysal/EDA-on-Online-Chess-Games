# Chess Games EDA Notebook

This project is a complete **Exploratory Data Analysis (EDA)** of a large dataset containing online chess games. The notebook walks through understanding player ratings, openings, game outcomes, number of moves, and overall patterns within real chess match data.

---

## 🔍 What This Notebook Covers

The notebook performs a structured EDA workflow, including:

### **1. Dataset Inspection**

* Loading `games.csv`
* Checking data types
* Viewing basic structure
* Identifying missing or inconsistent values

### **2. Player Rating Analysis**

* Distribution of white vs black player ratings
* Rating comparisons between winners and losers
* Identifying rating gaps

### **3. Game Outcome Patterns**

* Who wins more often: White, Black, or Draws
* Game length (number of turns) vs winner
* Relationship between rating and game result

### **4. Chess Opening Analysis**

* Most common openings
* ECO code distribution
* Openings correlated with win rates

### **5. Visualizations**

Uses **matplotlib** and **seaborn** to generate:

* Histograms
* Heatmaps
* Countplots
* Boxplots
* Distribution plots

These visualizations help reveal patterns in player strength, opening choices, and game results.

---

## 📂 Project Structure

```
Chess.ipynb       # Main EDA notebook
Games.csv         # Dataset used for analysis (not included in repo unless you add it)
```

---

## 🛠 Requirements

Install the necessary Python libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

And Jupyter:

```bash
pip install notebook
```

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/Shahria-Faysal/EDA-on-Online-Chess-Games.git
```

2. Open the notebook:

```bash
jupyter notebook Chess.ipynb
```

3. Make sure `games.csv` is placed in the same directory as the notebook.

---

## 📘 Purpose of This Project

This notebook is perfect for:

* Learning EDA through a real-world dataset
* Understanding patterns in online chess games
* Analyzing openings, winners, and player ratings
* Building intuition before doing ML modeling on chess games

---

## 📌 Future Improvements

* Add interactive visualizations (Plotly)
* Perform opening-based performance modeling
* Cluster players by style or rating
* Predict game outcomes using ML

---

## 📄 License

MIT License (or any license you prefer)

---

## ⭐ Support

If this project helps you, consider giving it a star on GitHub!
