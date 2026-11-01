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
