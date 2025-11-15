# SimonGame
A Qt-based implementation of the classic Simon Game for CS3505. Includes repeatable sequences, color frenzy mode, UI components, and full MVC architecture.

✨ Features
 - Four-button Simon Game with increasing difficulty
 - Sequence playback and user input validation
 - “Color Frenzy" mode (colors change every Nth round)
 - Clean MVC-based design
 - Fully implemented using Qt Widgets

📁 Project Structure
```bash
/src
    main.cpp
    simonmodel.cpp / .h
    simonview.cpp / .h
    ...
/resources
    icons, colors, sounds
```

🚀 How to Build
Install Qt 6 (or the version you used).
Open the .pro or CMakeLists.txt file in Qt Creator.
Build & Run.

🧪 Tests
Includes basic tests for:
Sequence generation
Button comparison
State transitions

### 🎨 Final UI Preview
Here’s how the Simon Game looks when running:
<img width="1919" height="1009" alt="Screenshot 2025-11-14 233024" src="https://github.com/user-attachments/assets/f57e340a-965f-4ea6-8549-382c4a4e679d" />
