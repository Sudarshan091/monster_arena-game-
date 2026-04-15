# ⚔️ Python Battle Simulator (CLI Game)

A simple command-line turn-based battle game built using Python. The player fights against a Goblin enemy using attack and heal actions until one is defeated.

---

## 🎮 Features

* 👤 Player vs Enemy turn-based combat
* ⚔️ Attack system with random damage
* 🧪 Healing system with capped HP
* 💀 Game over / victory conditions
* 📊 Live health tracking (HP display)
* 🎲 Randomized enemy behavior

---

## 🧠 Concepts Used

* Dictionaries (to store player & enemy stats)
* Functions (modular design)
* Loops (`while`) for game flow
* Conditional logic (`if-elif-else`)
* Random module (`random.randint`)
* Input/output handling

---

## 📂 Project Structure

```id="9o8k2g"
monster_arena.py
README.md
```

---

## ▶️ How to Run

1. Make sure Python 3 is installed
2. Open terminal and navigate to the project folder

   ```
   cd your/project/folder
   ```
3. Run the script:

   ```
   python3 monster_arena.py
   ```

---

## 🕹️ Gameplay Instructions

* Enter your name to start the game
* Each turn, choose:

  * `1` → Attack (deal damage to enemy)
  * `2` → Heal (restore your HP)
* Enemy will randomly:

  * Attack you
  * Heal itself
* Game ends when:

  * Enemy HP ≤ 0 → 🎉 You Win
  * Player HP ≤ 0 → 💀 Game Over

---

## 🖥️ Sample Output

```id="e9sn1n"
What is your name? Sudarshan

Sudarshan: 100/100 HP
Goblin: 100/100 HP
--------------------

__PLAYER TURN__
[1] Attack
[2] Heal
Choose your action: 1

You strike Goblin for 15 damage!
```

---

## ⚠️ Limitations

* No multiple enemies or levels
* No inventory system
* No save/load functionality
* Enemy AI is purely random (not strategic)
* CLI-based (no graphics)

---

## 🔥 Future Improvements

* 🧠 Smarter enemy AI (decision-making logic)
* 🧝 Multiple enemy types (Orc, Dragon, etc.)
* 🎒 Inventory system (potions, weapons)
* 📈 Leveling system (XP, stats upgrade)
* 💾 Save & load game progress
* 🎨 Convert to GUI (Tkinter / Pygame)

---

## 📌 Author:Sudarshan



