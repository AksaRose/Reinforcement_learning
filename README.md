# 🃏 Reinforcement Learning – Blackjack Agent

This project demonstrates the fundamentals of **Reinforcement Learning (RL)** by training an agent to play **Blackjack**, using **Gymnasium** (formerly OpenAI Gym).

The goal is to teach an agent to make optimal decisions — whether to “hit” or “stick” — to maximize its expected reward in a simulated Blackjack environment.

---

## 📘 Project Overview

Blackjack is a simple card game where the player competes against the dealer.  
This project implements a **Monte Carlo Exploring Starts (MC-ES)** algorithm to estimate value functions and derive an optimal strategy for the **Blackjack-v1** environment.

The environment models the full game dynamics, including card draws, busts, wins, and losses. The agent learns entirely through simulation and feedback — no prior knowledge of Blackjack rules is required.

---

##Working (SS)


<img width="673" height="596" alt="Screenshot 2025-10-15 at 8 42 35 AM" src="https://github.com/user-attachments/assets/ed3d07b9-eaf0-4f5e-ba6f-bf5d02eea670" />

<img width="1222" height="593" alt="Screenshot 2025-10-15 at 8 42 51 AM" src="https://github.com/user-attachments/assets/740acebc-f54e-4402-916b-85c683db33ac" />


## 🎯 Learning Objectives

- Understand **state-value** and **action-value** functions (Q(s, a))  
- Implement **Monte Carlo Control** using **Exploring Starts**  
- Train an RL agent via **episodic sampling**  
- Visualize learning progress with 3D plots and policy heatmaps  
- Evaluate convergence and performance

---

## 🧩 Tech Stack

| Component | Description |
|------------|-------------|
| **Language** | Python 3.10 + |
| **Core Library** | [Gymnasium](https://gymnasium.farama.org/) |
| **Computation & Plotting** | NumPy, Matplotlib |
| **Notebook Environment** | Jupyter Notebook |
| **RL Algorithm** | Monte Carlo Exploring Starts (MC-ES) |
| **Environment** | `Blackjack-v1` |

---

## 🖥️ Running Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/AksaRose/Reinforcement_learning.git
cd Reinforcement_learning
```

### 2️⃣ Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate
```
Windows:

```bash
python -m venv venv
venv\Scripts\activate
```
### 3️⃣ Install Dependencies

```bash
pip install gymnasium numpy matplotlib jupyter
```
### 4️⃣ Launch the Notebook

```bash
jupyter notebook Blackjack.ipynb
```
