# Sport Scavenger Hunt

**Sport Scavenger Hunt** is an interactive, gesture-based educational game built with **Flutter**. The app challenges users to identify specific sports equipment against a ticking clock while providing historical trivia and "legend" reveals through advanced touch interactions.

## 🚀 Features

* **Timed Scavenger Hunt:** Integrated a `Timer.periodic` countdown system that challenges users to find a specific sport's ball within 60 seconds.
* **Multi-Gesture Interaction:** Leveraged the `GestureDetector` widget to create a rich user experience:
    * **Tap:** Core gameplay mechanic to select the correct item and trigger Victory/Failure dialogs.
    * **Horizontal Drag:** Triggers an educational modal detailing the history and origins of the specific sport (e.g., James Naismith for Basketball, Alexander Cartwright for Baseball).
    * **Double Tap:** An "Easter Egg" feature that reveals an iconic legendary player for that sport (e.g., Messi for Fútbol, LeBron James for Basketball).
* **Dynamic State Management:** Utilizes `StatefulWidget` and `setState` to handle real-time timer updates and randomized objective selection.

## 🛠️ Technical Stack

* **Framework:** Flutter
* **Language:** Dart
* **Key Widgets:** `GestureDetector`, `Timer`, `AlertDialog`, `MaterialButton`, `AssetImage`.

## 📖 How to Play

1. **Start:** Long-press the **PLAY** button to start the timer and receive your target.
2. **Play:** Tap the correct ball to win before time runs out.
3. **Explore:** * **Drag horizontally** on any ball to learn its history.
    * **Double-tap** to see a legend of the game.

---
*Developed as part of an advanced App Development course focused on full-stack mobile applications and AI/API integration.*
