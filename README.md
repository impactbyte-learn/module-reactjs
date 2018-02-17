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
- Single Page
  - Mobilize Existing Applications
  - Mobile Todo App
  - Social Media Timeline
- Full Fledge
  - E-Commerce
  - Taxi Booking
  - Fitness Tracker

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

## Level 6

### Materials

- React Native
  - Preparing for Android & iOS app development
  - vs NativeScript, Meteor, Ionic, Phonegap, etc
  - vs Java/Kotlin, Objective-C/Swift, etc
- Mobile development tools
  - Android Studio + Gradle
  - Apple XCode + CocoaPods
  - Expo XDE and Snack
- [Debugging React Native Applications – React Native Academy](https://medium.com/reactnativeacademy/debugging-react-native-applications-6bff3f28c375)
- Primitive components
- Animation and styling
- Navigation
  - `StackNavigator`, `TabNavigator`
- Usage with Redux
- Deployment
  - Over the wire updates: [`react-native-auto-updater`](https://github.com/redbooth/react-native-auto-updater)
  - [CodePush](http://microsoft.github.io/code-push)
  - [AppHub Deploy](https://deploy.apphub.io)
- [React-Native—Leading Practices and Learnings](https://accenture.github.io/blog/2017/04/04/reactlearnings.html)
- [React Native Limitations and Best Practices to Deal With Them](https://jssolutionsdev.com/blog/react-native-limitations-and-best-practices-to-deal-with-them)
- [Performance profiling](https://facebook.github.io/react-native/docs/performance.html)

--------------------------------------------------------------------------------

## Level 7

### Materials

- Communication between native and React Native
  - Native Modules
  - Native UI Components
  - Connecting React Native to Java/Kotlin or Objective-C/Swift
- Integration with various APIs
  - Real time data
  - Image processing
  - Analytics
  - Search
  - Maps
- UI components library
  - NativeBase, Shoutem, Nachos, etc
- Final recap and conclusion

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
- [React HMR with `create-react-app`](https://daveceddia.com/hot-reloading-create-react-app)

### React Native

- [React Native - A framework for building native apps using React](https://facebook.github.io/react-native)
- [Expo](https://expo.io)
- [Learn React Native Today](https://egghead.io/browse/tools/react-native)
- [React Navigation](https://reactnavigation.org/)
- [Building a Simple ToDo App With React Native and Firebase](https://youtube.com/watch?v=3ab0K6viEp0)
- [An iOS Developer on React Native](https://medium.com/ios-os-x-development/an-ios-developer-on-react-native-1f24786c29f0)
- [NativeBase - Essential cross-platform UI components for React Native](https://nativebase.io)
- [NativeScript - Cross-Platform Native Development with JavaScript](https://nativescript.org)

### Full Stack Software Development

- [Super Full Stack Web Developer in Modern Expectation](https://mhaidarhanif.com/expectation)
