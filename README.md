# 🏆 Reversi Supreme

A premium, feature-rich implementation of the classic Reversi (Othello) board game with advanced AI, beautiful graphics, and comprehensive game statistics.

## 🎮 Game Features

### Core Gameplay
- **Classic Reversi Rules**: Strategic board game where players flip opponent pieces by sandwiching them
- **Single Player Mode**: Challenge yourself against sophisticated AI opponents
- **Multiple Difficulty Levels**: From Beginner (Level 1) to Master (Level 8)
- **Color Selection**: Choose to play as Black (first move) or White (second move)

### Advanced Features
- **Turn Timer**: Customizable time limits per turn (10s - 60s or unlimited)
- **Visual Hints**: See suggested optimal moves with the hint system
- **Valid Move Indicators**: Toggle to show all legal moves on the board
- **Undo Functionality**: Take back your last move during gameplay
- **Sound Effects**: Immersive audio feedback powered by Tone.js
- **Theme Toggle**: Switch between light and dark themes

### Statistics & Analytics
- **Real-time Score Tracking**: Live piece count for both players
- **Comprehensive Statistics**:
  - Pieces flipped (total)
  - Moves played
  - Corners captured (most valuable positions)
  - Edges captured
  - Current potential moves
  - Board fill percentage with progress bar

### User Experience
- **Responsive Design**: Optimized for desktop and mobile devices
- **Accessibility**: Full keyboard navigation and screen reader support
- **Smooth Animations**: Polished visual effects and transitions
- **Help System**: Built-in tutorial and strategic tips
- **Modern UI**: Beautiful gradient backgrounds and professional styling

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for Tone.js library loading)
- JavaScript enabled

### Installation
1. **Download the Game**:
   ```bash
   # Clone or download the repository
   # Copy "Reversi Supreme - Pro.html" to your desired location
   ```

2. **Launch the Game**:
   - Open `Reversi Supreme - Pro.html` in your web browser
   - No additional installation required!

### Quick Start
1. **Select Your Color**: Choose Black (first) or White (second)
2. **Choose Difficulty**: Pick from 8 AI difficulty levels
3. **Set Time Limit**: Select turn time or play without time pressure
4. **Configure Options**: Toggle sound effects and valid move indicators
5. **Start Playing**: Click "Start Game" to begin!

## 🎯 How to Play

### Objective
Have the most pieces of your color on the board when the game ends.

### Basic Rules
1. **Black moves first** - Place your piece on an empty square
2. **Sandwich opponent's pieces** - Form a line (horizontal, vertical, or diagonal) between two of your pieces
3. **Flip pieces** - All sandwiched opponent pieces become yours
4. **Valid moves only** - You can only place where you'll flip at least one piece
5. **Pass if blocked** - If no valid moves, your turn is skipped
6. **Game ends** - When neither player can move (board full or blocked)
7. **Winner** - Player with the most pieces wins

### Strategic Tips
- **Corners are king** - They can't be flipped and control board edges
- **Control the edges** - Second most valuable positions
- **Limit opponent mobility** - Reduce their available moves
- **Avoid danger squares** - Don't play adjacent to empty corners (C2, B1, G2, B7, etc.)
- **Position over quantity** - Better placement beats having more pieces

## 🎨 Customization Options

### Game Settings
- **Difficulty Levels**: 8 progressive AI strengths
- **Time Controls**: 6 time limit options plus unlimited
- **Visual Aids**: Toggle valid move indicators and hints
- **Audio**: Enable/disable sound effects

### Theme Options
- **Light Theme**: Clean, bright interface
- **Dark Theme**: Easy on the eyes with dark backgrounds
- **Automatic Persistence**: Your theme choice is remembered

## 🏗️ Technical Details

### Architecture
- **Pure Web Technology**: HTML5, CSS3, ES6+ JavaScript
- **No Dependencies**: Self-contained single HTML file
- **Modular Design**: Well-organized code structure
- **SVG Graphics**: Scalable vector board rendering

### Browser Compatibility
- ✅ Chrome 70+
- ✅ Firefox 65+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Performance
- **Optimized Rendering**: Smooth 60fps animations
- **Efficient AI**: Fast move calculations even at high difficulty
- **Responsive Layout**: Adapts to different screen sizes
- **Memory Efficient**: Minimal resource usage

## 🎵 Audio Features

### Sound Effects
- **Game Start**: Triumphant opening sound
- **Piece Placement**: Satisfying click/place sounds
- **Piece Flipping**: Distinct flip animation sounds
- **Game End**: Victory/defeat audio cues
- **UI Interactions**: Button click feedback

### Audio Technology
- **Tone.js Integration**: Professional audio synthesis
- **Dynamic Audio**: Context-aware sound selection
- **Volume Control**: Respects system audio settings

## 📊 Statistics Explained

### Real-time Metrics
- **Current Score**: Live piece count
- **Pieces Flipped**: Total captures made
- **Moves Played**: Total turns taken
- **Corners Captured**: Most valuable squares controlled
- **Edges Captured**: Second-tier strategic positions
- **Potential Moves**: Current available moves
- **Board Filled**: Percentage completion with visual progress

## 🛠️ Development

### Code Structure
```
Reversi Supreme - Pro.html
├── HTML Structure
│   ├── Game container and layout
│   ├── Setup screen
│   ├── Game board (SVG)
│   ├── Statistics panel
│   └── Help modal
├── CSS Styling
│   ├── Theme variables
│   ├── Responsive design
│   ├── Animations
│   └── Visual effects
└── JavaScript Logic
    ├── Game engine
    ├── AI algorithms
    ├── UI controllers
    ├── Sound system
    └── Statistics tracking
```

### Browser Console
Access browser developer tools (F12) to see:
- Game state debugging
- AI decision logging
- Performance metrics
- Error handling

## 🤝 Contributing

### Ways to Contribute
- **Bug Reports**: Found an issue? Let us know!
- **Feature Requests**: Have ideas for new features?
- **Code Improvements**: Submit pull requests
- **UI/UX Suggestions**: Help improve the user experience

### Development Setup
1. Fork the repository
2. Make your changes
3. Test thoroughly across different browsers
4. Submit a pull request

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- **Reversi/Othello**: Classic board game creators
- **Tone.js**: Professional audio synthesis library
- **Web Standards**: HTML5, CSS3, and ES6+ specifications

## 🎮 Enjoy Playing!

Reversi Supreme - Pro offers hours of strategic gameplay with beautiful visuals and challenging AI opponents. Whether you're a beginner learning the basics or an expert honing your skills, this implementation provides the perfect platform for mastering the game of Reversi!

**Happy gaming!** 🎯
