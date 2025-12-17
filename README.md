# 🧠 Deep Reinforcement Learning – Atari & Arcade Agents

This repository showcases **high-performance Deep Reinforcement Learning agents** trained on classic Atari and arcade-style environments.  
Each project focuses on **stability, sample efficiency, and convergence to super-human performance**, with **GIFs demonstrating trained agent behavior**.

---

## 🎮 Trained Agent Performance (Live Rollouts)

<p align="center">
  <img src="website/boxing_500.gif" width="30%" />
  <img src="website/ponggif.gif" width="30%" />
  <img src="website/breakout_5000.gif" width="30%" />
</p>

<p align="center">
  <img src="website/flappy-bird.gif" width="30%" />
  <img src="gifs/qbert.gif" width="30%" />
  <img src="gifs/flappybird.gif" width="30%" />
</p>


---

## 📂 Projects Overview

### 🥊 **Atari Boxing — Double DQN + Dueling Architecture**
**File:** `DeepRL_boxing.ipynb`

- Optimized **Double DQN** with **Dueling Network Architecture (DDA)**
- Reduces **Q-value overestimation**
- Stabilizes training in **high-frequency action spaces**
- Demonstrates consistent defensive and offensive strategies

---

### 🧱 **Atari Breakout — DQN + Prioritized Experience Replay**
**File:** `DeepRL_breakout.ipynb`

- Deep Q-Network with **Prioritized Experience Replay (PER)**
- Faster convergence on **high-dimensional pixel state space**
- Learns long-term brick-clearing strategies
- Achieves **super-human control**

---

### 🏓 **Atari Pong — PPO + GAE**
**File:** `DeepRL_pong.ipynb`

- Highly parallelized **Proximal Policy Optimization (PPO)**
- Uses **Generalized Advantage Estimation (GAE)**
- Optimized for **low-latency competitive environments**
- Learns near-perfect ball control and positioning

---

### 👻 **Ms. Pac-Man — Deep Recurrent Q-Network**
**File:** `DeepRL_pacman.ipynb`

- **DRQN (LSTM-based)** to handle partial observability
- Tackles **delayed reward** challenges
- Uses **epsilon-greedy annealing**
- Truncated Backpropagation Through Time (**TBPTT**)

---

### 🟦 **Q*bert — Deep Q-Learning**
**File:** `DeepRL_qbert.ipynb`

- Pixel-based DQN learning complex spatial jumps
- Sparse reward optimization
- Learns color-completion strategies with minimal exploration
- Demonstrates stable long-term planning

---

### 🐦 **Flappy Bird — Evolutionary Strategies**
**Folder:** `flappy_bird_game/`

- AI-driven Flappy Bird using **Evolutionary Strategies (ES)**
- Neural network policies evolved across generations
- Distributed fitness evaluation
- No gradients, no backprop — pure evolution

---

## 🚀 Key Contributions

- Advanced **stabilization techniques** (Double DQN, Dueling, PER)
- Recurrent RL for **partial observability**
- Policy-gradient optimization with **parallel PPO**
- Evolutionary learning for non-differentiable environments
- Real performance visualization via rollout GIFs

---

## 📌 Requirements

```bash
Python 3.9+
PyTorch
Gym / Gymnasium
NumPy
OpenCV
