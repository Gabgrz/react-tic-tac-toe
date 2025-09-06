# Tic-Tac-Toe React App

A classic tic-tac-toe game built with **React 19** and modern React patterns. This project demonstrates the latest React features including the new `createRoot` API, functional components with hooks, and modern development practices.

## 🚀 Features

- **React 19** - Latest React version with new features and optimizations
- **Modern React Patterns** - Functional components with hooks instead of class components
- **New React DOM API** - Uses `createRoot` instead of deprecated `ReactDOM.render`
- **Hot Reloading** - Development server with instant updates
- **Production Ready** - Optimized build with code splitting and minification
- **Responsive Design** - Clean, modern UI that works on all devices

## 🎮 How to Play

1. The game starts with player X
2. Click on any empty square to make your move
3. Players alternate between X and O
4. First player to get 3 in a row (horizontally, vertically, or diagonally) wins!
5. The game will show the winner or indicate it's a draw

## 🛠️ Tech Stack

- **React 19.0.0** - Latest React with new features
- **React DOM 19.0.0** - Updated DOM rendering
- **Create React App** - Modern build tooling
- **Webpack 4** - Module bundling
- **Babel** - JavaScript compilation
- **CSS3** - Styling with modern CSS features

## 📦 Installation & Setup

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd tic-tac-toe-react
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📋 Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in development mode with React 19's new features.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

- **Hot Reloading** - Changes are reflected instantly
- **React 19 DevTools** - Enhanced debugging experience
- **Modern Error Overlay** - Better error reporting
- **Fast Refresh** - Preserves component state during updates

### `npm test`

Launches the test runner in interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production with React 19 optimizations.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

**Build Features:**
- **Code Splitting** - Automatic chunk optimization
- **Tree Shaking** - Removes unused code
- **Minification** - Compressed JavaScript and CSS
- **Asset Hashing** - Cache-busting for deployments
- **Source Maps** - Easy debugging in production

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## ⚡ React 19 Upgrade

This project has been upgraded to React 19 with modern patterns:

### **What's New:**
- **React 19.0.0** - Latest React version with performance improvements
- **New `createRoot` API** - Replaced deprecated `ReactDOM.render`
- **Functional Components** - Converted from class components to modern hooks
- **Modern State Management** - Using `useState` hook for state
- **Enhanced DevTools** - Better debugging experience
- **Improved Performance** - Faster rendering and updates

### **Code Changes:**
```javascript
// Old React 16 pattern (deprecated)
ReactDOM.render(<App />, document.getElementById('root'));

// New React 19 pattern
const container = document.getElementById('root');
const root = createRoot(container);
root.render(<App />);
```

### **Component Modernization:**
- Converted class components to functional components
- Replaced `this.state` with `useState` hook
- Simplified component lifecycle with hooks
- Improved code readability and maintainability

## 📁 Project Structure

```
tic-tac-toe-react/
├── public/                 # Static assets
│   ├── index.html         # HTML template
│   └── favicon.ico        # App icon
├── src/                   # Source code
│   ├── index.js          # App entry point with React 19 createRoot
│   └── index.css         # Game styles
├── config/               # Webpack configuration
├── scripts/              # Build scripts
├── package.json          # Dependencies and scripts
└── README.md            # This file
```

## 🔧 Development Notes

### **Node.js Compatibility**
- Requires Node.js 16+ for optimal performance
- Uses legacy OpenSSL provider for webpack compatibility
- Tested with Node.js 24.7.0

### **Browser Support**
- Modern browsers with ES6+ support
- Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- Mobile browsers supported

### **Performance**
- **Bundle Size**: ~60KB gzipped
- **First Load**: Optimized with code splitting
- **Hot Reload**: Sub-second update times
- **Memory Usage**: Efficient with React 19 optimizations

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.


### **Code Style:**
- Use functional components with hooks
- Follow React 19 best practices
- Maintain clean, readable code
- Add comments for complex logic

## 📚 Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
