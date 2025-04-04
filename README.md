# 🎲 Monte Carlo Simulation: Fair 6-Sided Die

This project simulates rolling a **fair 6-sided die** multiple times (10 to 50,000 throws) and analyzes the probability of each face appearing. The goal is to observe how the **Monte Carlo method** approximates theoretical probabilities as the number of rolls increases.

📌 **Built in:** First-year college (Statistics Subject)  
📌 **Platform:** Google Colab  

---

## 🔍 Project Overview
- Uses **Monte Carlo Simulation** to estimate probabilities of rolling each face of a **fair 6-sided die**.
- Compares **theoretical probability (1/6 = 16.67%)** with **experimental probability**.
- Analyzes how probabilities converge as the number of rolls increases.

---

## 📊 Features & Visualizations  
✔️ **Bar Charts**: Theoretical vs Monte Carlo probabilities for different sample sizes (10, 50, 100, etc.)  
✔️ **Line Graphs**: Show how probabilities **converge** as rolls increase (log-scale visualization)  
✔️ **Cumulative Probability Graph**: Tracks probability stability over multiple trials  

---

## 🔢 Methodology
1. **Simulate Rolls**: Generate random outcomes for rolling a 6-sided die.
2. **Calculate Probabilities**: Compute Monte Carlo probabilities for each face.
3. **Compare with Theory**: Plot theoretical vs experimental probabilities.
4. **Observe Convergence**: As the number of rolls increases, probabilities approach 1/6.

---

## 📁 File Structure
monte_carlo_simulation/ │── [monte_carlo_die_simulation.ipynb](https://colab.research.google.com/drive/1cUQ1VX6PO5ocuDMdQ0mykgcxZ6kxrirO?usp=sharing) # Jupyter Notebook (Google Colab) │── monte_carlo_results/ # Folder containing saved images │── README.md # Project documentation


---

## 📊 Results

- With **small samples (10-100 rolls)**, probabilities fluctuate significantly.  
- As **trials increase (5,000+ rolls)**, probabilities approach the expected 1/6.  
- **Graphs visually confirm** how random experiments align with probability theory.

---

## 🛠️ Technologies Used
- **Python**
- **NumPy** (for random number generation)
- **Matplotlib** & **Seaborn** (for data visualization)
- **Tabulate** (for structured result display)
- **Google Colab** (for running the simulation)

---

## 🚀 How to Run the Simulation
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload `monte_carlo_die_simulation.ipynb`.
3. Run all cells to generate results.

---

## 🎯 Key Learnings
✅ **Monte Carlo simulations** provide a practical approach to probability.  
✅ **Larger sample sizes** lead to more stable probability estimates.  
✅ **Visualizing probability convergence** helps understand randomness & law of large numbers.  

---

## 📸 Sample Visuals  
![image](https://github.com/user-attachments/assets/f7f9d65a-38a9-46d0-a08f-cd5bdcea3b1c)


---

## 👨‍🎓 Author  
[Your Name](https://github.com/maxarnab)  

---
