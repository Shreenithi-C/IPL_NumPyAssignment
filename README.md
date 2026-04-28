# IPL Dataset — NumPy Assignment

## Overview
This project analyzes IPL ball-by-ball data (`deliveries.csv`) using **NumPy only**.  
It avoids Pandas/DataFrames to strengthen skills in vectorized computation, boolean masking, and aggregation.

Dataset: [IPL Complete Dataset (2008–2020)](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)

---

## Tasks Implemented
1. Total Runs per Match  
2. Top 5 Batters  
3. Strike Rate of Batters  
4. Economy Rate of Bowlers  
5. Runs per Over  
6. Boundary Analysis (4s & 6s, team with most boundaries)  
7. Death Overs Analysis (overs 16–20)  
8. Highest Scoring Match  
9. Runs per Team per Match  
10. Match Winner Approximation  
11. Match Scorecard Generation  

---

## Guidelines Followed
- **NumPy only** (no Pandas or DataFrames)  
- **Vectorized solutions** (avoiding loops)  
- **Boolean masking** for filtering  
- **np.unique + np.bincount** for grouping  
- **Clean modular notebook cells** (one task per cell)  
- **Handled missing/inconsistent data** gracefully  

---

## Project Learning Outcomes
- Perform grouping operations without Pandas  
- Use NumPy for real-world structured data analysis  
- Apply vectorization techniques for efficiency  
- Generate readable outputs (scorecards, summaries)  

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ipl-numpy-assignment.git

2. Open the notebook in VS Code or Jupyter:
  ```bash
  code IPL_NumPy_Assignment.ipynb
  
3. Run cells sequentially (Cell 1 loads data, Cells 2–12 implement tasks).
