# ⏱️ The Almost Final Countdown

**The Almost Final Countdown** is a fun and interactive timing-challenge web application that tests how accurately you can estimate time.
Your goal is simple: **stop the timer as close as possible to the target time — without going over it**.

---

## Website Link
- https://final-countdown-jofn.onrender.com

---

## 🚀 Features

* 🧑 **Set Your Name**
  Enter your name at the top to personalize the experience.

* 🎯 **Multiple Difficulty Levels**

  * **Easy** – 1 second
  * **Not Easy** – 5 seconds
  * **Getting Tough** – 10 seconds
  * **Pros Only** – 15 seconds

* ▶️ **Start & Stop Timer**

  * Start a challenge by clicking **Start Challenge**
  * Stop the timer when you think the target time is almost reached

* 📊 **Score Calculation**

  * If you stop **before** the target time:

    ```
    Score = (Remaining Time / Target Time) × 100
    ```
  * Higher score = better time estimation 🎯

* ❌ **Lose Condition**

  * If the timer **expires** 
  * A popup appears showing:

    * Target time
    * Time left (0.00 seconds)
    * Result: **YOU LOST**

* 💬 **Result Popup**

  * Displays win/loss message and score
  * Includes a **Close** button to continue playing

---

## 🖥️ Screens Overview

* **Home Screen**

  * Name input
  * Four challenge cards with different time limits
  * Timer status shown as *inactive* initially

* **Result Modal**

  * Appears automatically after each challenge
  * Shows success or failure details clearly

---

## 🚀 Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/vinaypoddar2000/final_countdown.git
cd final_countdown
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open your browser and navigate to `http://localhost:3000`

---

## 🛠️ Tech Stack

* HTML
* CSS
* JavaScript
* React

---

## 🎮 How to Play

1. Enter your name at the top
2. Click **Start**
3. Estimate the time mentally
4. Click **Stop** just before the timer ends
5. Check your score or result in the popup

---

**Enjoy beating the clock! ⏳**
