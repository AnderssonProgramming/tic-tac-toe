# Tic-Tac-Toe React Game

A classic Tic-Tac-Toe game built with React, featuring an interactive game board, move history, and time travel functionality. This project demonstrates fundamental React concepts including components, state management, and event handling.

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Game Rules](#game-rules)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Learning Objectives](#learning-objectives)
- [Available Scripts](#available-scripts)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## 🎯 About

This Tic-Tac-Toe game is based on the official [React Tutorial](https://react.dev/learn/tutorial-tic-tac-toe) and serves as an excellent introduction to React development. The game implements a complete interactive experience with move history and the ability to jump back to previous game states.

## ✨ Features

- **Interactive Game Board**: Click on squares to make your move
- **Player Turn Indicator**: Shows whose turn it is (X or O)
- **Winner Detection**: Automatically detects and announces the winner
- **Move History**: Complete history of all moves made during the game
- **Time Travel**: Jump back to any previous move in the game
- **Game Reset**: Start a new game at any time
- **Responsive Design**: Works on desktop and mobile devices

## 🎮 Demo

The game provides:
- A 3x3 grid where players take turns placing X's and O's
- Real-time game status updates
- A list of moves that allows players to review and jump to any point in the game
- Automatic winner detection with all possible winning combinations

## 🚀 Installation

### Prerequisites

- Node.js (version 14.0 or higher)
- npm (comes with Node.js)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/AnderssonProgramming/tic-tac-toe.git
   cd tic-tac-toe
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to play the game.

## 🎯 Usage

1. **Starting a Game**: The game starts automatically with X going first
2. **Making Moves**: Click on any empty square to place your mark
3. **Viewing History**: Use the move list on the right to see all previous moves
4. **Time Travel**: Click on any move in the history to jump back to that point
5. **Winning**: The game will announce the winner when three marks align
6. **New Game**: Click "Go to game start" to begin a fresh game

## 📜 Game Rules

1. The game is played on a 3×3 grid
2. Players take turns, with X going first
3. Players place their mark (X or O) in empty squares
4. The first player to get 3 marks in a row (horizontally, vertically, or diagonally) wins
5. If all 9 squares are filled and no player has 3 in a row, the game is a draw

## 📁 Project Structure

```
tic-tac-toe/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── App.css
│   ├── App.js              # Main game components
│   ├── App.test.js
│   ├── index.css
│   ├── index.js            # Entry point
│   ├── logo.svg
│   ├── reportWebVitals.js
│   ├── setupTests.js
│   └── styles.css          # Game-specific styles
├── package.json
├── README.md
└── LICENSE
```

### Key Components

- **`Game`**: The main component that manages game state and history
- **`Board`**: Renders the 3x3 game board and handles move logic
- **`Square`**: Individual clickable squares on the board

## 🛠 Technologies Used

- **React 19.1.0**: Frontend framework
- **React DOM 19.1.0**: DOM rendering
- **React Scripts 5.0.1**: Build tools and development server
- **CSS3**: Styling and layout
- **HTML5**: Structure and semantics

### Development Dependencies

- **@testing-library/react**: Testing utilities
- **@testing-library/jest-dom**: Custom Jest matchers
- **@testing-library/user-event**: User interaction simulation
- **web-vitals**: Performance monitoring

## 🎓 Learning Objectives

This project demonstrates key React concepts:

- **Components**: Functional components with props
- **State Management**: Using `useState` hook
- **Event Handling**: onClick events and user interactions
- **Conditional Rendering**: Dynamic UI updates based on game state
- **Lists and Keys**: Rendering move history with proper keys
- **Immutability**: Creating new arrays/objects instead of mutating existing ones
- **Lifting State Up**: Sharing state between components

## 📜 Available Scripts

In the project directory, you can run:

### `npm start`
Runs the app in development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.\
The page will reload when you make changes.

### `npm test`
Launches the test runner in interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

### `npm run eject`
**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time.

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **React Team**: For the excellent [React Tutorial](https://react.dev/learn/tutorial-tic-tac-toe) that this project is based on
- **Create React App**: For providing the initial project setup and build tools
- **React Community**: For the comprehensive documentation and learning resources

## 📚 Learn More

- [React Documentation](https://reactjs.org/)
- [React Tutorial - Tic-Tac-Toe](https://react.dev/learn/tutorial-tic-tac-toe)
- [Create React App Documentation](https://facebook.github.io/create-react-app/docs/getting-started)
- [React Hooks Documentation](https://reactjs.org/docs/hooks-intro.html)

---

**Built with ❤️ using React**
