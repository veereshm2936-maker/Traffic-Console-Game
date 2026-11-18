### 🚦 **Traffic Game - Overview**

This **console-based game** simulates a puzzle where **two teams (RED and BLUE)** are **stuck in a traffic jam**, and the goal is to **help your team get to the other side** by following specific rules.

---


### 🎯 **Game Objective**

> Move all your team members to the **opposite side** of the board, ahead of the other team, by taking valid moves.

---

### 👥 **Players / Teams**

* You have:

  * **Team RED**
  * **Team BLUE**
* Each team has up to **10 players**
* There's **one empty space** in the middle to move into

---

### 🧠 **Game Rules**

1. Each player can either:

   * **WALK** 1 step into the empty space (in front only)
   * **JUMP** over **one opponent player** into the empty space (2 steps ahead)
2. You **cannot go backwards**
3. You **cannot jump over your own team**
4. The first team to get all their players to the opponent’s side **wins**
5. You can also **cheat** (auto-solve) or **restart**

---

### 🎮 **How It Works**

* It’s **turn-based**:

  * RED plays, then BLUE plays
* You choose which player to move by its position (shown in console)
* After each move, the game updates the board and shows current positions
* Game ends when one team successfully reaches the other side

---
```markdown
## 💻 How to Run It Locally

### ✅ Requirements

- Java JDK **11 or newer**  
- Terminal (Command Prompt / Bash / VS Code / IntelliJ)

---

### 🧾 Steps to Run

#### 1️⃣ Clone the Repository
```bash
git clone https://github.com/vijay4229/Traffic-Jam-Game.git
cd Traffic-Jam-Game
```

---

#### 2️⃣ Folder Structure
Make sure the files are structured like this:
```plaintext
Traffic-Jam-Game/
└── traffic/
    ├── TrafficGame.java
    └── TeamMember.java
```

---

#### 3️⃣ Compile the Game
From the root directory, run:
```bash
javac -d . traffic/TrafficGame.java traffic/TeamMember.java
```
---

#### 4️⃣ Run the Game
```bash
java traffic.TrafficGame
```

---

### 🕹️ Start Playing!
Once started, follow the on-screen prompts to:
- 🚶 Move players  
- 📜 View rules  
- 🔁 Restart the game  
- 🤖 Solve (Cheat Mode)  
- ❌ Quit anytime  
```
