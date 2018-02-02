# React & React Native Lesson Plan

What you need to learn about React & React Native in a short amount of time.

--------------------------------------------------------------------------------

## Author

- [M Haidar Hanif](https://mhaidarhanif.com): Co-Founder, Program Lead, Tech Mentor of [Impact Byte](http://impactbyte.com)

## Recommended Trainers

- [Simon Sturmer](https://github.com/sstur)
- [Ega Wachid Radiegtya](https://github.com/radiegtya) [<DumbWays.id>](https://dumbways.id)
- [Adityo Pratomo](https://github.com/lunchboxav)

## Knowledge Gain

- React & React Native
- ES6/ES+
- Node.js & npm
- Asynchronous programming
- Routing
- State management
- JavaScript bundler like Webpack

## Recommended Requirements

- Basic programming
- Basic knowledge of Object-Oriented Programming (OOP) and Functional Programming (FP)
- Basic knowledge of clean code and application architecture such as Model-View-Controller (MVC) or others
- Experience with HTML5, CSS3, JavaScript (ES6/ES+), Node.js, npm
  - ES6/ES+: arrow function, classes, enhanced object literals, template strings, destructuring, `default` + `rest` + `spread`, `let` + `const`, `iterators` + `for..of`, modules, module loaders, promise, `async` `await`
- laptop (i5/i7, RAM 8GB, 100GB), mobile device

## Typical Agenda

- Introduction
- Yesterday quick review
- Discussion about the topics
- Individual hands on projects, pair programming, and team work
- Team members should contibute each others in a repository

## Notes

All the materials by level are very comprehensive, therefore, it's okay to readjust the materials according to progress and feedbacks from the learners along the way.

It's possible to shift React Native materials earlier if it's convenient. That also cuts out some of the web-related materials that doesn't directly tied into React Native.

## Project Ideas

- Single Page Application (SPA)
  - Number Conversion
  - Simple Calculator
  - Todo App
- Simulation
  - Restaurant POS (Point of Sales)
  - Book Lending for Library
- System
  - Content Management System (CMS)
  - Student Information System
- Multi States
  - Blog Platform
  - Job Board
  - Inventory Management

--------------------------------------------------------------------------------

## Level 1

### Materials

- JavaScript concept review
- Why React?
  - The main reasons and philosophy
  - Installation and usage
  - Building blocks of React, `react`, `reactDOM`
  - Structure of the project
  - Component and virtual DOM
  - It's just JavaScript!
  - vs jQuery, Vue, Angular, Preact, Web Components, Elm, etc
  - Preparing your code editor (Atom, VS Code, Sublime, Vim, etc) with React plugins
- Component-based development
  - Design planning with wireframe/mockup
  - Parent and child relationship between components
- Rendering user interface (UI)
  - Quickly create a new app with `create-react-app` CLI
  - Creating components and writing HTML with `class` in JSX
  - JSX is a DSL (Domain Specific Language) over JavaScript
  - React DevTools for debugging
- React conventions
  - Element naming
  - Class-based components
  - Stateless functional components
- Understanding state management and holding data
  - Managing state in applications with `this`, `state`, `setState`, `getState`
  - Passing data between components with with `props`, `propTypes`, and `defaultProps`
  - Controlled components
- Event and bind handling
  - Methods in component
  - Fetching data from an AJAX endpoint (open databases/API)
  - Working with forms, retrieving data from DOM inputs
- Rendering with external data
  - Complete lifecycle of a component
  - Explore various lifecycle hooks
  - Persisting data with `localStorage`/`sessionStorage` Virtual DOM
- [Best Practices for Writing React Components](https://engineering.musefind.com/our-best-practices-for-writing-react-components-dec3eb5c3fc8)

--------------------------------------------------------------------------------

## Level 2

### Materials

- Frontend deployment
  - VPS or PaaS: Netlify, Surge, Heroku, Now.sh, etc
  - Process management with pm2
- Routing with React Router
  - Route and Link component
  - Creating different routes/paths
  - Use state to dynamically render different pages
- Styling techniques
  - Regular CSS, Flexbox, Stylus/LESS/SASS
  - Inline styling, CSS in JS
  - CSS modules
  - BEM (Block, Element, Modifier)
- UI components library
  - Reactstrap, Material UI, etc
  
--------------------------------------------------------------------------------

## Level 3

### Materials

- Build system
  - Webpack vs Gulp, Grunt, Rollup, Broccoli, etc
  - Hot reloading/update using `webpack-dev-server`
  - ES+ with Babel
- Static typing
  - Flow static type checker
  - vs PropTypes, TypeScript
- Asynchronous Programming
  - Callback
  - `Promise`
  - `async`, `await`
- Functional Programming (FP)
  - Data immutability
  - Pure function/component
  - Higher Order Component (HOC)
- Integration with other library via npm
  - D3.js

--------------------------------------------------------------------------------

## Level 4

### Materials

- Better state management
  - Flux vs Redux vs MobX
  - Component state vs Redux state
  - Intuition to determine when to use them
  - It can be used with any other library than just React
- React + Redux
  - Reducers
  - Actions and Action Creators
  - `createStore` to create a Redux store
  - `react-redux` to connect React & Redux
  - Data architecture normalization
  - Better Redux store with combineReducers
  - Middleware
  - Authentication when needed

--------------------------------------------------------------------------------

## Level 5

### Materials

- Redux architecture best practices and rules
- Redux + React Router
- `redux-saga`
- Advanced techniques
  - Server side rendering (SSR)
  - Universal/isomorphic React
  - Static site
  - Optimize for SEO
  - Next.js, Gatsby.js, etc
- Frontend testing
  - Jest, Enzyme, etc
  - Snapshot testing
  - Continuous Integration (CI)
- Integration with other application
  - Use your own REST API then connect to ReactJS
- Build your own UI components for reusability
- Build a full fledge application in a teamwork

--------------------------------------------------------------------------------

## References

### JavaScript (ES6/ES+)

- [Eloquent JavaScript: A Modern Introduction to Programming](http://eloquentjavascript.net)
- [Top 10 ES6 Features Every Busy JavaScript Developer Must Know](https://webapplog.com/es6)
- [`es6features`](http://git.io/es6features)
- [ECMAScript 6: New Features: Overview and Comparison](http://es6-features.org)
- [Babel | The transpiler for writing next generation JavaScript](https://babeljs.io)
- [Exploring ES6](http://exploringjs.com/es6)
- [Project Guidelines - A set of best practices for JavaScript projects](https://github.com/wearehive/project-guidelines)

### React

- [React - A JavaScript library for building user interfaces](https://facebook.github.io/react)
- [Fullstack React 🐬 Book - The Complete Guide to ReactJS and Friends](https://fullstackreact.com)
- [Build with React JS](http://buildwithreact.com)
- [Start Learning React - egghead.io](https://egghead.io/courses/start-learning-react)
- [Learn ReactJS: Part I | Codecademy](https://www.codecademy.com/courses/react-101/lessons/react-jsx-intro/exercises/why-react)
- [`react-howto` - Your guide to the (sometimes overwhelming!) React ecosystem]()
- [React Nanodegree by Udacity](https://udacity.com/degrees/react-nanodegree--nd019)
- [React Armory - The simplest way to learn React](https://reactarmory.com/)
  - [Lifecycle Simulators](https://reactarmory.com/guides/lifecycle-simulators)
- [Fullstack React: 30 Levels of React](https://fullstackreact.com/30-days-of-react)
- [Pure React](https://daveceddia.com/pure-react)
  - [Your Timeline for Learning React](https://daveceddia.com/timeline-for-learning-react)
  - [How To Learn React (and what to build along the way)](https://daveceddia.com/how-to-learn-react)
  - [Learning React? Start Small](https://daveceddia.com/learning-react-start-small)
  - [Learning React as an Experienced Developer](https://daveceddia.com/learn-react-as-experienced-developer)
  - [A Visual Guide to State in React](https://daveceddia.com/visual-guide-to-state-in-react)
  - [AJAX Requests in React: How and Where to Fetch Data](https://daveceddia.com/ajax-requests-in-react)
  - [Do I need Node.js in the backend?](https://daveceddia.com/do-i-need-nodejs-backend-for-react-angular)
- [`create-react-app` - Create React apps with no build configuration](https://github.com/facebookincubator/create-react-app)
- [React.parts – A catalog of React components](https://react.parts/)
- [Build with React](http://buildwithreact.com)
- [reactstrap - React Bootstrap 4 components](https://reactstrap.github.io/)
- [Cabin: Thoroughly Learn React and Redux with this example app](http://cabin.getstream.io)
- [8 Key React Component Decisions – freeCodeCamp](https://medium.com/@housecor/8-key-react-component-decisions-cc965db11594)
- [React For Beginners - Learn with Video Tutorials](https://reactforbeginners.com)
- [React Untuk Pemula](https://kandar.id/20-reactjs-untuk-pemula)
- [Stop Using React for EVERYTHING!](https://medium.com/@zackargyle/stop-using-react-for-everything-c8297ac1a644)
- [React Tinkerer Manual](https://github.com/adhywiranata/react-tinkering-manual)
- [Video Tutorial: React untuk Pemula | DumbWays.id - Screencast](https://dumbways.id/p/react-untuk-pemula)
- [React Dasar](https://www.idrails.com/series/react-dasar)

### Full Stack Software Development

- [Super Full Stack Web Developer in Modern Expectation](https://mhaidarhanif.com/expectation)
