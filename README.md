# React Multi-Game Application

A comprehensive React application featuring three interactive games built with React 19, Vite, and React Router. This project demonstrates modern React concepts including hooks, state management, component composition, and responsive design.

## 🎮 Games Included

**Tic-Tac-Toe** - Classic two-player game with editable names, winner detection, move history, and rematch feature.

**Quiz Game** - Timed multiple-choice quiz with answer feedback, skip option, and score summary.

**Pause & Play** - Timing challenge with multiple difficulty levels testing reaction time and precision.


## 🚀 Tech Stack

React 19.1.1 • React Router 7.9.1 • Vite 7.1.2 • CSS Modules • ESLint

## 📦 Quick Start

```bash
git clone https://github.com/Rajat-22/Tic-Tac-Toe.git
cd tic-tac-toe
npm install
npm run dev
```

**Scripts:** `dev` • `build` • `lint` • `preview`

## 📁 Project Structure

```
src/
├── components/
│   ├── Tic-Tac-Toe Game/
│   │   ├── TicTacToe.jsx
│   │   ├── TicTacToe.module.css
│   │   ├── Player.jsx
│   │   ├── GameBoard.jsx
│   │   ├── GameOver.jsx
│   │   ├── Log.jsx
│   │   └── winning-combination.js
│   ├── Quiz/
│   │   ├── ReactQuiz.jsx
│   │   ├── Quiz.jsx
│   │   ├── Quiz.module.css
│   │   ├── Header.jsx
│   │   ├── Answers.jsx
│   │   ├── QuestionTimer.jsx
│   │   └── questions.js
│   └── Pause & Play/
│       ├── PausePlay.jsx
│       ├── PausePlay.module.css
│       ├── Player.jsx
│       ├── TimerChallenge.jsx
│       └── ResultModal.jsx
├── App.jsx
├── main.jsx
└── index.css
```

## 🎨 Features

- **Responsive Design**: All games are fully responsive and work on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, intuitive interfaces with smooth animations
- **Component-Based Architecture**: Reusable and maintainable code structure
- **CSS Modules**: Scoped styling to prevent conflicts
- **State Management**: Efficient use of React hooks (useState, useRef, useEffect)
- **React Router**: Seamless navigation between games
- **Fast Development**: Powered by Vite for instant HMR

## 🌐 Navigation

The application includes a navigation bar at the top with links to:
- **Tic Tac Toe** - `/tic-tac-toe`
- **Play & Pause** - `/play-pause`
- **Quiz** - `/quiz`

The root path (`/`) automatically redirects to the Tic Tac Toe game.

## 📱 Responsive Breakpoints

- **Desktop**: Full-size layouts with optimal spacing
- **Tablet**: Optimized for screens up to 768px
- **Mobile**: Compact layouts for screens up to 480px

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

**Rajat-22**
- GitHub: [@Rajat-22](https://github.com/Rajat-22)

## 🙏 Acknowledgments

- Built with React and Vite
- Inspired by classic games and modern web development practices
- Designed with a focus on learning and demonstrating React concepts