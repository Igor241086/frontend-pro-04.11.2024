# Front-End Pro: Homework

Homework assignments from the **Front-End Pro** course at Hillel IT School (2024-2025).
The repository follows the course path from JavaScript basics to React, Redux and testing.

## Tech stack

- **Core:** HTML5, CSS3/SCSS, JavaScript (ES6+)
- **Libraries and UI:** jQuery, Bootstrap, Material UI (MUI)
- **React ecosystem:** React, React Router, Context API, Formik + Yup, Redux Toolkit, Redux Saga, TanStack Query
- **Backend basics:** Node.js, Express, MongoDB (Mongoose), json-server
- **Tooling:** npm, Webpack, Babel, Vite, Create React App, ESLint
- **Testing:** Vitest, React Testing Library
- **APIs:** OpenWeatherMap, SWAPI (Star Wars API), Axios / fetch

## Structure

All tasks are in the [`front-end pro`](./front-end%20pro) folder, one folder per task: `Task 3` ... `Task 33`.

### JavaScript basics

| Task | Topic | What was done |
| --- | --- | --- |
| [Task 3](./front-end%20pro/Task%203) | Data types, user input | `typeof` for all data types, `prompt` input, splitting a number into digits |
| [Task 4](./front-end%20pro/Task%204) | Conditions | `if/else`, `switch`, checking digits of a three-digit number, validating user input |
| [Task 5](./front-end%20pro/Task%205) | Loops | `for`/`while`, USD to UAH conversion table, squares not exceeding N, prime number check |
| [Task 6](./front-end%20pro/Task%206) | Functions | Removing characters from a string, calculating an average, helper functions |
| [Task 7](./front-end%20pro/Task%207) | Closures, currying | Accumulator via closure, `multiply(a)(b)`, input with a limited number of attempts |
| [Task 8](./front-end%20pro/Task%208) | `this`, method chaining | `ladder` object with `up().down().showStep()` |
| [Task 9](./front-end%20pro/Task%209) | Recursion | Recursive sum of salaries in a nested company object |
| [Task 10](./front-end%20pro/Task%2010) | Objects and prototypes | Object literals, constructor functions, prototype methods, getters/setters, contact book |

### DOM, events and browser

| Task | Topic | What was done |
| --- | --- | --- |
| [Task 11](./front-end%20pro/Task%2011) | DOM manipulation | 10x10 table with images, random image, button that toggles text color |
| [Task 12](./front-end%20pro/Task%2012) | Events, Bootstrap | Saving a link and following it, event delegation, TODO list |
| [Task 13](./front-end%20pro/Task%2013) | Forms | Contact form with field validation and error messages |
| [Task 14](./front-end%20pro/Task%2014) | UI components | Image slider with prev/next buttons and dot navigation |
| [Task 15](./front-end%20pro/Task%2015) | localStorage | ToDo list that keeps tasks between page reloads |

### OOP and asynchronous code

| Task | Topic | What was done |
| --- | --- | --- |
| [Task 16](./front-end%20pro/Task%2016) | Classes | `Student` class: average grade, attendance tracking, age |
| [Task 17](./front-end%20pro/Task%2017) | Classes, validation | `Calculator`, `Coach`, `BankAccount` with input validation and errors |
| [Task 18](./front-end%20pro/Task%2018) | Private fields, timers | Countdown timer class with private fields (`#`) and start/pause controls |
| [Task 19](./front-end%20pro/Task%2019) | async/await, REST API | Weather widget using the OpenWeatherMap API |

### Libraries, bundlers and backend

| Task | Topic | What was done |
| --- | --- | --- |
| [Task 20](./front-end%20pro/Task%2020) | jQuery, Bootstrap | TODO list with a Bootstrap modal, built with jQuery |
| [Task 21](./front-end%20pro/Task%2021) | Babel | Transpiling the jQuery TODO app with Babel |
| [Task 22](./front-end%20pro/Task%2022) | Webpack | Webpack build with SCSS, CSS minification and hashed output files |
| [Task 23](./front-end%20pro/Task%2023) | Node.js, Express, MongoDB | REST API with CRUD for todos (Express + Mongoose) and a frontend connected to it |

### React and state management

| Task | Project | What was done |
| --- | --- | --- |
| [Task 24](./front-end%20pro/Task%2024) | `swapi-ui` | First React app (CRA): character card with Bootstrap |
| [Task 25](./front-end%20pro/Task%2025) | `emoji-voting` | Emoji voting with a class component, results saved in localStorage |
| [Task 26](./front-end%20pro/Task%2026) | `emoji-vote` | The same app rewritten with hooks (`useState`), testing library set up |
| [Task 27](./front-end%20pro/Task%2027) | `my-spa-app` | SPA with React Router, theme switcher via Context API, `ErrorBoundary` (Vite) |
| [Task 28](./front-end%20pro/Task%2028) | `todo-app` | Todo app with Formik + Yup validation and a custom `useTodos` hook |
| [Task 29.1](./front-end%20pro/Task%2029.1) | `counter-app` | Counter on Redux Toolkit (store, slice) |
| [Task 29.2](./front-end%20pro/Task%2029.2) | `todo-redux` | Todo list on Redux Toolkit with a footer and filters |
| [Task 30](./front-end%20pro/Task%2030) | `swapi-app` | SWAPI search app: Redux Toolkit, Axios, loader, service layer |
| [Task 31](./front-end%20pro/Task%2031) | `todo-app` | Todo app with Redux Toolkit + Redux Saga, Axios and json-server as a mock API |
| [Task 32](./front-end%20pro/Task%2032) | `my-portfolio-app` | Portfolio app: MUI, React Router, TanStack Query, SWAPI and Todo pages |
| [Task 33](./front-end%20pro/Task%2033) | `my-todo-app` | Todo app covered with unit tests (Vitest + React Testing Library) |

## How to run

Tasks 3-20 are plain HTML/JS: open `index.html` in a browser (or use the VS Code Live Server extension).

For projects with `package.json` (Task 21 and later):

```bash
cd "front-end pro/Task 28/todo-app"
npm install
npm run dev     # Vite projects
npm start       # Create React App projects (Tasks 24-26)
```

Some tasks need extra steps:

- **Task 23:** create a `.env` file with your MongoDB connection string, then run `node server.js`.
- **Task 31:** start the mock API with `npm run start:server` (json-server) in a separate terminal.
- **Task 33:** run the tests with `npm test`.

## Author

**Ihor Mahats**, junior front-end developer, Odesa, Ukraine.
GitHub: [Igor241086](https://github.com/Igor241086)
