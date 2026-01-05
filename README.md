# Unity Game - Antimatter Dimensions Clone

A Unity-based incremental/idle game inspired by Antimatter Dimensions, featuring exponential growth mechanics and prestige systems.

## 🎮 Game Overview

**Genre**: Incremental/Idle Game  
**Engine**: Unity 2022+  
**Platform**: PC, Mobile  
**Status**: In Development

## 📋 Features

### Core Gameplay
- **8 Dimensional Tiers**: Each dimension produces the one below it
- **Antimatter Economy**: Exponential currency growth system
- **BigDouble Math**: Handle numbers up to infinity
- **Prestige System**: Reset for permanent upgrades
- **Dimension Boost**: Multiply production rates
- **Tickspeed**: Increase game calculation speed

### UI/UX
- **Modern UI Toolkit**: Responsive, scalable interface
- **Adaptive Layout**: Supports multiple screen sizes
- **Gradient Backgrounds**: Visually appealing design
- **Progress Bars**: Visual feedback for progression
- **Buy Modes**: Purchase 1 or until next milestone

### Technical Features
- **Save/Load System**: JSON-based persistent data
- **Singleton Pattern**: Clean manager architecture
- **Platform Detection**: Mobile/Desktop optimization
- **Universal Render Pipeline (URP)**

## 🗂️ Project Structure

```
Assets/
├── Scripts/              # Game logic (69 C# scripts)
│   ├── GameManager.cs
│   ├── DimensionsPanelController.cs
│   ├── PrestigePanelController.cs
│   ├── BigDouble.cs
│   └── ...
├── Scenes/              # Unity scenes
│   └── SampleScene.unity
├── UI/                  # UI resources
│   ├── UXML/           # UI Toolkit layouts
│   └── USS/            # Stylesheets
├── Resources/          # Game resources
├── Settings/           # Project settings
└── TextMesh Pro/       # Text rendering

```

## 🚀 Getting Started

### Prerequisites
- Unity 2022.3 LTS or later
- Universal Render Pipeline (URP)
- TextMesh Pro (included)

### Installation
1. Clone this repository
```bash
git clone https://github.com/jjkkhh123/my_Unity_Game.git
```

2. Open the project in Unity

3. Open `Scenes/SampleScene.unity`

4. Press Play to start

## 🎯 Gameplay Mechanics

### Dimension System
- Dimension 1 produces Antimatter
- Dimension 2 produces Dimension 1
- ... and so on up to Dimension 8
- Each purchase increases cost exponentially

### Progression Path
1. **Early Game**: Unlock first dimensions
2. **Mid Game**: Use Dimension Boosts for multipliers
3. **Late Game**: Prestige for Prestige Points
4. **End Game**: Shop upgrades and optimization

### Prestige Shop
- **Tickspeed Power**: Increase calculation speed
- **Dimension Multipliers**: Boost specific dimensions (2x per level)
- **Bulk Bonus**: Enhance bulk purchase multiplier

## 💻 Development

### Architecture
- **Manager Pattern**: Centralized game state management
- **UI Toolkit**: Modern declarative UI framework
- **Event-Driven**: Clean component communication

### Key Systems
- `GameManager`: Core game loop and dimension logic
- `PrestigeManager`: Prestige mechanics and upgrades
- `DimBoostManager`: Dimension boost system
- `TickSpeedManager`: Game speed controller
- `SaveManager`: Persistent data handling
- `UIManager`: UI state management

## 📝 Roadmap

- [ ] Additional prestige upgrades
- [ ] Challenge system
- [ ] Achievement system
- [ ] Statistics panel
- [ ] Offline progression
- [ ] Cloud save integration
- [ ] Sound effects and music
- [ ] Particle effects
- [ ] Mobile optimization

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests.

## 📄 License

This project is for educational purposes.

## 🔗 Links

- [Antimatter Dimensions (Original)](https://ivark.github.io/)
- [Unity Documentation](https://docs.unity3d.com/)
- [UI Toolkit Guide](https://docs.unity3d.com/Manual/UIElements.html)

## 📧 Contact

GitHub: [@jjkkhh123](https://github.com/jjkkhh123)

---

**Note**: This is a fan project inspired by Antimatter Dimensions. All credits for the original game concept go to the original creators.
