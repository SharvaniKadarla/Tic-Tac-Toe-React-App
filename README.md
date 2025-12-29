# Tic-Tac-Toe React App

A fully functional **Tic-Tac-Toe game built using React**.  
This project reimplements the classic Tic-Tac-Toe game using **React’s component-based architecture** and compares the development experience to a vanilla JavaScript implementation.

---

## ✨ Features

- Interactive 3×3 Tic-Tac-Toe board
- Fully component-based UI using React
- State management using `useState`
- Turn tracking (X / O)
- Winner and draw detection
- Automatic UI re-rendering on state changes
- Clean separation of logic and presentation
- Responsive and modern React structure

---

## 🛠️ Tech Stack

- **React**
- **JavaScript (ES6+)**
- **HTML5**
- **CSS3**
- **Create React App**
- **Node.js & npm**

---
## 🚀 Getting Started (Local Setup)
1️⃣ Install Node.js and npm
- `sudo apt update`
- `sudo apt install nodejs npm`
- `node -v`
- `npm -v`

2️⃣ Clone the repository
- `git clone https://github.com/SharvaniKadarla/Tic-Tac-Toe-React-App.git`
- `cd Tic-Tac-Toe-React-App`

3️⃣ Install dependencies
- `npm install`

4️⃣ Start the development server
- `npm start`
- Open your browser at: `http://localhost:3000`

---
## 🧠 React Component Breakdown

The application follows the **Thinking in React** methodology:

**Main Components**
- **Game** – Parent component that holds the main game state
- **Board** – Renders the grid of squares
- **Square** – Represents a single cell in the grid

**State Management**
- Game state (history, current step, player turn) is stored in the top-level component
- State updates automatically trigger UI re-rendering
- Props are passed from parent → child
- Child components communicate updates via callback functions

This ensures **unidirectional data flow**, cleaner logic, and easier debugging.

---
## 🧩 Comparison: React vs Vanilla JavaScript

- In **vanilla JS**, DOM updates and game state must be managed manually

- In **React**, UI updates automatically when state changes

- React’s component-based structure makes the code:

  - More modular

  - Easier to scale

  - Easier to maintain in larger projects

Vanilla JavaScript is still ideal for very small projects or quick prototypes, but React clearly provides better structure for larger applications.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
