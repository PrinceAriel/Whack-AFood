# 🎮 Whack-a-food Unity Game

A fun and challenging whack-a-food style game built in Unity where players must click on food items while avoiding skulls, all within a 60-second time limit!

## 📋 Features

- ✅ **Three Difficulty Levels**: Easy, Medium, and Hard with varying spawn rates
- ✅ **Score Tracking**: Real-time score display that updates with each successful click
- ✅ **Countdown Timer**: 60-second timer that triggers game over when it reaches zero
- ✅ **Game Over Screen**: Displays when time runs out with a restart option
- ✅ **Dynamic Spawning**: Random food and skull objects appear on a 4x4 grid
- ✅ **Restart Functionality**: Seamlessly restart the game after game over

## 🎯 How to Play

1. **Select a Difficulty**: Click Easy, Medium, or Hard to start the game
2. **Click the Food**: Quickly click on food items as they appear to earn points
3. **Avoid the Skulls**: Clicking skulls will end the game immediately
4. **Beat the Clock**: Try to score as many points as possible before the 60-second timer runs out
5. **Restart**: After game over, click the Restart button to play again

## 🕹️ Controls

- **Mouse Click**: Click on food items to destroy them and earn points
- **Difficulty Buttons**: Select your preferred challenge level
- **Restart Button**: Appears after game over to replay

## 🛠️ Technical Details

### Built With
- **Unity Version**: [2022.3 LTS]
- **Language**: C#
- **UI System**: Unity UI (Canvas) with TextMeshPro

### Key Scripts
- `GameManagerX.cs`: Manages game state, scoring, timer, and difficulty settings
- `Target.cs`: Handles individual food/skull click detection and destruction

### Game Mechanics
- **Spawn System**: Uses coroutines to spawn objects at intervals based on difficulty
- **Timer System**: Countdown timer using `Time.deltaTime` with rounded display
- **Difficulty Scaling**: Spawn rate divides by difficulty level (1=Easy, 2=Medium, 3=Hard)

## 📦 Installation & Setup

### Option 1: Play the Game (Build)
1. Download the latest release from the [Releases](../../releases) page
2. Extract the ZIP file
3. Run the executable file
4. Enjoy!

### Option 2: Open in Unity (For Developers)
1. Clone this repository:

   git clone https://github.com/PrinceAriel/Whack-AFood.git