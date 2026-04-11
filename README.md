# 🐦 Flappy Bird AI using Deep Reinforcement Learning (DQN)

🚀 An intelligent AI agent that learns to play Flappy Bird using **Deep Q-Network (DQN)** and Reinforcement Learning techniques.

---

## 📌 Overview

This project implements a Reinforcement Learning agent that interacts with the Flappy Bird environment and learns optimal actions through rewards and penalties.

The agent improves its performance over time using **Deep Learning + Experience Replay**, eventually mastering the game.

---

## 🧠 Key Concepts Used

* Reinforcement Learning (RL)
* Deep Q-Network (DQN)
* Experience Replay
* Epsilon-Greedy Strategy (Exploration vs Exploitation)
* Neural Networks (PyTorch)

---

## 🛠️ Tech Stack

* **Language:** Python 🐍
* **Libraries:**

  * PyTorch
  * Gymnasium (flappy-bird-gymnasium)
  * NumPy
  * Matplotlib

---

## 🎮 Environment

* Game: Flappy Bird
* Framework: Gymnasium Environment

The agent observes the game state and decides whether to **flap or not**, aiming to survive as long as possible.

---

## ⚙️ How It Works

1. The agent observes the current state of the game
2. Chooses an action using epsilon-greedy policy
3. Receives reward/penalty based on the outcome
4. Stores experience in replay memory
5. Trains the neural network using sampled experiences
6. Improves performance over episodes

---

## 📊 Results

* The agent shows progressive learning over time
* Performance improves with more training episodes
* Successfully learns to avoid obstacles and survive longer

*(Add your score/graph here if available)*

---

## ▶️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/your-username/flappy-bird-rl.git

# Navigate to project folder
cd flappy-bird-rl

# Install dependencies
pip install -r requirements.txt

# Run the project
python main.py
```

---

## 📁 Project Structure

```
├── main.py
├── dqn.py
├── experience_replay.py
├── config.yaml
├── requirements.txt
└── README.md
```

---

## 📸 Demo

*(Add GIF or gameplay screenshot here)*

---

## 🚀 Future Improvements

* Add Double DQN / Dueling DQN
* Hyperparameter tuning for better performance
* Save & load trained models
* Deploy as a web-based game

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and improve it.

---

## 📬 Connect with Me

* LinkedIn: https://linkedin.com/in/your-profile
* GitHub: https://github.com/your-username

---

⭐ If you found this project useful, don’t forget to star the repo!

```
1. Installation :
  To install flappy-bird-gymnasium, simply run the following command:
  $ pip install flappy-bird-gymnasium
2. Command run in terminal to train model :
   python agent.py flappybirdv0 --train : use to train data
3. Command use in terminal to run model :
   python agent.py flappybirdv0
```
   
