# 🏏 IPL 2025 Batting Intent Analysis

This project presents a comprehensive **Batting Intent Analysis** of a high-stakes IPL 2025 match between **Royal Challengers Bengaluru (RCB)** and **Delhi Capitals (DC)**. Using detailed **ball-by-ball data** and powerful Python libraries like **Pandas**, **Plotly**, and **Seaborn**, we uncover batting patterns and performance trends that highlight how different players and teams approach various phases of the game.

---

## 📌 Project Highlights

- 🔍 **Strike Rate Analysis** across Powerplay, Middle Overs, and Death Overs  
- 📊 **Team-wise Batting Intent Comparison** by match phase  
- 🚀 **Boundary % vs Dot Ball %** visualization per batter  
- 📈 **Over-wise Run Progression** of Top 4 Run-Scorers  
- ⚖️ **Correlation of Wickets with Run Flow** to understand momentum  
- 🧠 **Radar Charts** of batter profiles based on strike rate, dot %, and boundary %

---

## 📂 Dataset

The dataset includes every delivery from the RCB vs DC IPL 2025 match, with details like:
- Over and ball number
- Batter and bowler names
- Runs scored
- Wickets
- Team details

📥 You can download the dataset from: `ipl_match_1473461_deliveries.csv` (place it in your working directory)

---

## 🛠️ Technologies Used

- **Python** 🐍  
- **Pandas** 📊  
- **Plotly Express & Graph Objects** 📈  
- **Seaborn & Matplotlib**  
- **Jupyter Notebook / VS Code** 💻

---

## 🔍 Key Insights

### 1. Strike Rate Across Game Phases
Batters like **T Stubbs** and **KL Rahul** showed strong intent in the death overs with strike rates >220, while **PD Salt** impressed in the powerplay with over 140.

### 2. Team-wise Batting Intent
DC outperformed RCB in the Death Overs (SR ~240). RCB dominated early but lost momentum in the middle and end phases.

### 3. Boundary % vs Dot Ball %
PD Salt had an ideal balance: high boundary % and low dot ball %. In contrast, TH David was aggressive but inconsistent with many dot balls.

### 4. Over-Wise Run Progression
Top batters like Salt and Stubbs showed explosive bursts in select overs. Stubbs was dominant between overs 14–16 while TH David owned the death.

### 5. Runs vs Wickets Per Over
Revealed the **risk-reward balance**—high scoring overs often saw wicket falls. Useful for understanding pressure points.

### 6. Radar Charts of Batting Profiles
Visualized batter characteristics:
- PD Salt: Balanced, aggressive
- Stubbs: Maximum power hitter
- KL Rahul: Steady with risk control
- TH David: Risky but high-strike impact

---

## ▶️ Run the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/harshshri07/IPL-2025-Batting-Intent-Analysis.git
   cd IPL-2025-Batting-Intent-Analysis
