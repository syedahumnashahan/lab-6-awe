<<<<<<< HEAD
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
=======
# Combined State Management in React.js

## Project Overview
This project demonstrates how to integrate Context API and Redux together in a single React.js application to manage application states effectively.

## Technologies Used
- React.js
- JavaScript
- Context API
- Redux
- React Redux
- CSS
- Git and GitHub

## Task 1: Integrate Context API and Redux

### Context API
- Created UserContext.js using createContext() and useState().
- Managed user information using Context API.
- Added Login and Logout functionality.
- Default username is Guest.
- Login changes the username to Humna Shahan.

### Redux
- Created Redux actions, reducers, and store.
- Managed counter state using Redux.
- Added Increment and Decrement buttons.
- Connected Redux using Provider from react-redux.

## Task 2: Extend Functionality and Implement Theming

### Theme Context
- Created ThemeContext.js.
- Managed light and dark themes using useState().
- Implemented a theme toggle function using Context API.
- Used useContext() to access theme data.
- Applied conditional CSS styling for both themes.

## Project Folder Structure

```text
src/
├── context/
│   ├── UserContext.js
│   └── ThemeContext.js
│
├── redux/
│   ├── actions.js
│   ├── reducers.js
│   └── store.js
│
├── App.js
└── App.css
```

## Application Features
1. User Login and Logout.
2. Display Current Username.
3. Redux Counter.
4. Increment Counter.
5. Decrement Counter.
6. Light Mode.
7. Dark Mode.
8. Reusable React Components.

## How to Run the Project

1. Clone the GitHub repository.
2. Open the project folder in VS Code.
3. Install dependencies:

```bash
npm install
```

4. Start the React application:

```bash
npm start
```

5. Open the application at:

http://localhost:3000

## Conclusion
This project demonstrates the combined use of Context API and Redux for state management in React.js. Context API manages user information and application themes, while Redux manages the counter state.
>>>>>>> 1ac5ea73c7b87530f7ff739bd6aca3d1c0b558e5
