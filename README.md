# 🎮 Rock-Paper-Scissors (C++ Console Game)

A clean, modular console-based implementation of the classic **Rock-Paper-Scissors** game written in **C++**. 

This project was built to practice foundational C++ programming concepts, focusing on structuring code using Clean Code practices, custom data types, procedural state control, and interactive Windows Console features (audio & dynamic screen coloring).

---

## ✨ Features

* **Modular Architecture:** Fully decoupled business logic, round execution, data structures, and terminal UI rendering.
* **Struct-Based State Management:** Utilizes `stRoundInfo` and `stGameResults` structures to eliminate loose variables and pass complete data contexts.
* **Array-Based Lookups:** Replaces legacy conditional logic with high-performance array indexing for choices and game states.
* **Dynamic Audio & Visual Feedback:** Integrated Windows API (`windows.h`) for color-coded status backgrounds (Green for Win, Red for Loss, Yellow for Draw) paired with custom `Beep()` sound cues.
* **Game Replayability:** Built-in loop system allowing continuous play sessions with automated screen clearing (`cls`) and color resets.
* **Detailed Game Summary:** Full visual post-game analytics report showing total rounds, player score, computer score, draw count, and the ultimate match winner.

---

## 🛠️ Technical Concepts Applied

* **Enums & Structs:** `enGameChoice`, `enWinner`, `stRoundInfo`, `stGameResults`.
* **Randomization:** Seeded pseudo-random generator via `srand((unsigned)time(NULL))` and `rand()`.
* **Windows API Integration:** Dynamic terminal color manipulation (`system("color XX")`) and system frequency audio (`Beep()`).
* **Input Validation:** Guard clauses protecting round bounds (1 to 10) and option selections.
* **Procedural Programming:** Functional decomposition ensuring single-responsibility functions.

---

## 👨‍💻 Author

**Badr Samy**  
*Undergraduate Student & Aspiring .NET Backend Engineer*
