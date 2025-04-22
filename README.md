# 🍓 Fruit Finder - Android Matching Game

A fun and interactive 5x5 grid-based matching game for Android, where users must find and tap on all instances of a randomly chosen fruit!

## 📱 Game Overview

In this game, players are challenged to locate all occurrences of a specific fruit (focus image) randomly chosen from a set of six different fruits. The focus fruit and its occurrences are randomly placed on a 5x5 grid, alongside other fruit distractors.

### 🎮 Gameplay Flow

1. **Game Initialization**:
   - Six fruit icons are preloaded in the game.
   - One fruit is randomly selected as the **focus image**.
   - A random count **N (1 to 8)** of the focus fruit is placed randomly on the board.
   - The remaining **25 - N** grid spaces are filled with random non-focus fruits.
   - All 25 fruits are randomly shuffled and placed on the 5x5 board.

2. **User Objective**:
   - The top of the screen displays:  
     `"Find All [Fruit Name] (N)"`  
     e.g., `Find All Apples (7)`
   - Each time the user taps on a correct fruit, the counter decreases.
   - When all correct fruits are found, a **congratulations dialog** appears.

3. **Reset Functionality**:
   - A **Reset** button at the bottom restarts the game.
   - The board reinitializes with a new random setup.

### 🖼️ UI Flow

- **(a) App Starting**: Initial board with the full fruit set.
- **(b) Finding the First Item**: A fruit has been found, counter decreases.
- **(c) Two Remaining Items**: Progress continues with real-time updates.
- **(d) Found All**: Success dialog appears after all target fruits are tapped.

## ⚙️ Tech Stack

- **Platform**: Android
- **Language**: Java
- **Layout**: GridView or RecyclerView with ImageView items
- **Randomization**: Utilizes `Random` for selecting focus fruit, count, and placements.

## 🚀 Features

- Dynamic and replayable gameplay
- Easy-to-understand interface
- Random board generation every time
- Reset functionality
- Victory dialog on success

## 📦 Future Improvements

- Add timer or scoring system
- Add sound effects and animations
- Introduce levels with increasing difficulty
- Accessibility features for children

## 🧑‍💻 Author

Created by **Srushti Samant** as a fun Android development project to explore grid-based UIs, randomization, and touch interactions.

---

Feel free to fork and enhance! 🌟
