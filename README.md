# Memory & Puzzle Educational Game 🎮

A multi-level educational game developed using the Unity Engine, featuring puzzle challenges, memory card matching, authentication system, player feedback system, and mobile-ready gameplay for Android and iOS platforms.

---

# 📌 Project Overview

This project was developed as an interactive educational and entertainment game using Unity and C#.

The game includes:

- Memory card matching game
- Puzzle assembly levels
- Authentication system (Login / Register)
- Scene management
- UI feedback system
- Mobile support
- Multiple game levels
- Win panels and restart system
- Character selection system

The project focuses on improving:

- Problem solving
- Memory skills
- User interaction
- Game logic implementation
- Mobile game development

---

# 🛠️ Technologies Used

- Unity Engine
- C#
- TextMeshPro
- PlayerPrefs
- Firebase (initial integration)
- Unity UI System
- Scene Management
- Android Build Support
- iOS Build Support

---

# ✨ Features

## 🔐 Authentication System

- User Registration
- User Login
- Prevent entering game without login
- Local data storage using PlayerPrefs

---

## 🧩 Puzzle System

- Drag & drop puzzle pieces
- Snap detection
- Correct placement validation
- Win detection

---

## 🃏 Memory Game

- Card flipping system
- Match detection
- Move counter
- Game restart system

---

## 📢 Feedback System

- “Good Move!” feedback
- “YOU WIN” feedback
- Animated text messages
- Win panel system

---

## 🎮 UI System

- Main menu
- Instructions panel
- Restart buttons
- Scene transitions
- Mobile-friendly UI

---

## 📱 Mobile Ready

- Android support
- iOS support
- Touch input compatible
- Responsive UI

---

# 📂 Project Structure

```bash
Assets/
│
├── Scripts/
│   ├── AuthManager.cs
│   ├── MainMenu.cs
│   ├── GameManager.cs
│   ├── GameController.cs
│   ├── PuzzlePiece.cs
│   ├── CardFlipper.cs
│   └── CharacterSwitcher.cs
│
├── Scenes/
│   ├── MainMenu.unity
│   ├── Level1.unity
│   ├── Level2.unity
│   ├── Puzzle.unity
│   ├── Memory.unity
│   └── Instructions.unity
│
├── Prefabs/
├── Sprites/
├── Audio/
└── UI/
```

---

# 🧠 Game Logic

## Puzzle Logic

Each puzzle piece stores its correct position.

When released near the correct location:

- Piece snaps into place
- Feedback appears
- Piece becomes locked

---

## Memory Game Logic

- Player flips 2 cards
- Cards are compared

If matched:

- Cards stay visible
- Feedback appears

If not:

- Cards flip back automatically

---

# 🔑 Authentication Workflow

1. User enters email & password
2. Validation checks:
   - Empty fields
   - Email format
   - Password length
3. Data stored locally
4. User must login before playing

---

# 🎨 UI Design

The UI was designed to:

- Be beginner-friendly
- Support mobile devices
- Use responsive layouts
- Provide visual feedback

---

# 🚀 How to Run

## Requirements

- Unity Hub
- Unity 2022+ recommended
- Android Build Support (optional)
- iOS Build Support (optional)

---

## Steps

1. Clone repository
2. Open project in Unity
3. Open MainMenu scene
4. Press Play

---

# 📱 Build for Android

1. File → Build Settings
2. Select Android
3. Switch Platform
4. Build APK

---

# 🍎 Build for iOS

1. File → Build Settings
2. Select iOS
3. Switch Platform
4. Build project
5. Open with Xcode

---

# 📸 Screenshots

## Main Menu

(Add screenshot here)

---

## Login System

(Add screenshot here)

---

## Puzzle Level

(Add screenshot here)

---

## Memory Game

(Add screenshot here)

---

# 📈 Future Improvements

- Online database integration
- Multiplayer support
- Leaderboard system
- Cloud save system
- Sound effects & animations
- Advanced AI opponent
- Firebase Authentication full integration

---

# 👨‍💻 Author

**Abdullah Aly**  
Computer Science Student & Unity Developer

---

# 📄 License

This project is for educational purposes and portfolio showcase.

---

# ⭐ GitHub Tips

Before uploading:

- Add screenshots
- Add gameplay GIFs
- Upload APK demo
- Write clean commits
- Add project video demo

---

## Example Repository Name

```bash
memory-puzzle-game-unity
```

---

## Example Commit

```bash
Initial release - Memory & Puzzle Educational Game
```