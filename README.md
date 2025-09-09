<!-- 
font: http://patorjk.com/software/taag/

Big type
 -->

# Frontend Interview Question and Answers
This repo contains the list of questions and answers commonly asked in interviews

## Categories

- ### [ReactJS](https://github.com/sailendrachettri/interview-questions-answer/tree/main?tab=readme-ov-file#reactjs-1)
- ### [.NET](https://github.com/sailendrachettri/interview-questions-answer?tab=readme-ov-file#netl)
- ### [HyperText Markup Language(HTML)](https://github.com/sailendrachettri/interview-questions-answer?tab=readme-ov-file#html)
- ### [Cascading Style Sheets(CSS)](https://github.com/sailendrachettri/interview-questions-answer?tab=readme-ov-file#css)
- ### [Object Oriented Programming(OOP)](https://github.com/sailendrachettri/interview-questions-answer?tab=readme-ov-file#oops)
- ### [RDBMS & DBMS](https://github.com/sailendrachettri/interview-questions-answer?tab=readme-ov-file#rdbms--dbms)
- ### [Structured Query Language(SQL)](https://github.com/sailendrachettri/interview-questions-answer?tab=readme-ov-file#sql)
- ### [non-Structured Query Language(noSQL)](https://github.com/sailendrachettri/interview-questions-answer?tab=readme-ov-file#nosql)
- ### [Git and Github](https://github.com/sailendrachettri/interview-questions-answer?tab=readme-ov-file#git-and-github-1)
- ### [JavaScript(Js) Programming Language](https://github.com/sailendrachettri/interview-questions-answer?tab=readme-ov-file#javascript)


<!-- 
  _____                 _       _  _____ 
 |  __ \               | |     | |/ ____|
 | |__) |___  __ _  ___| |_    | | (___  
 |  _  // _ \/ _` |/ __| __|   | |\___ \ 
 | | \ \  __/ (_| | (__| || |__| |____) |
 |_|  \_\___|\__,_|\___|\__\____/|_____/ 
                                         
                                         
 -->

 ## ReactJS

1. **What is ReactJS?**

   * It is an open-source JavaScript library.
   * It is used to build `Single Page Applications` using reusable components.
   * Maintained by Meta (Facebook).

2. **What are the key features of ReactJS?**

   * Virtual DOM.
   * React Hooks.
   * Reusable Components.

3. **What is state in ReactJS?**

   * State is a built-in object used to store dynamic data in a component.
   * It allows components to re-render automatically when the data changes.
   * Managed internally by the component.

4. **What is Virtual DOM?**

   * Virtual DOM is a copy of the real DOM.
   * When the state changes, React updates the Virtual DOM first, compares it with the previous one, and then makes the necessary changes in the real DOM.
   * This process leads to faster and more efficient performance.

5. **What are the advantages of ReactJS?**

   * Simple to build SPA by using components.
   * It is open-source and backed by Meta.
   * Very fast and lightweight (Virtual DOM).

6. **What are the disadvantages of ReactJS?**

   * Not good for very small and static applications.
   * Steeper learning curve (JSX, Hooks).
   * Requires integration with other libraries for full-stack development.

7. **What are props in ReactJS?**

   * Props are inputs passed to a component from its parent.
   * They are read-only and immutable.
   * Help make components reusable.

8. **What is the difference between state and props?**

   * State is local and mutable; Props are external and immutable.
   * State is managed inside the component; Props are passed by parent.
   * State changes trigger re-renders, props reflect parent updates.

9. **What is JSX in ReactJS?**

   * JSX stands for JavaScript XML.
   * It allows writing HTML inside JavaScript.
   * Transpiled into `React.createElement()` calls.

10. **Why use JSX instead of plain JavaScript?**

    * Makes code more readable and declarative.
    * Allows embedding JavaScript expressions inside UI code.
    * Improves development productivity.

11. **What are functional components?**

    * Functions that return JSX.
    * Use hooks for state and lifecycle.
    * Easier to write and maintain.

12. **What are class components?**

    * ES6 classes extending `React.Component`.
    * Use `this.state` and lifecycle methods.
    * Older approach before hooks.

13. **What are controlled components?**

    * Form elements controlled by React state.
    * Value comes from `state`.
    * Ensures React fully controls input changes.

14. **What are uncontrolled components?**

    * Form elements controlled by the DOM itself.
    * Accessed via `refs`.
    * Simpler but less React-friendly.

15. **What is React Router?**

    * Standard library for routing in React apps.
    * Provides `BrowserRouter`, `Routes`, and `Route`.
    * Enables navigation without reloading.

16. **What is SPA (Single Page Application)?**

    * Application that loads a single HTML file.
    * Updates views dynamically using JavaScript.
    * No full-page reloads required.

17. **What is useEffect hook?**

    * Used for side effects (API calls, subscriptions).
    * Runs after render by default.
    * Supports cleanup via return function.

18. **What is useState hook?**

    * Hook for declaring state in functional components.
    * Returns state variable and updater function.
    * Triggers re-render on update.

19. **What is useContext hook?**

    * Access context values without prop drilling.
    * Works with `React.createContext()`.
    * Provides global state management.

20. **What is useRef hook?**

    * Stores mutable values across renders.
    * Can reference DOM elements directly.
    * Does not trigger re-renders.

21. **What is useMemo hook?**

    * Caches computed values.
    * Prevents expensive recalculations.
    * Optimizes performance.

22. **What is useCallback hook?**

    * Returns memoized callback function.
    * Prevents unnecessary re-creations.
    * Useful in child components with `React.memo`.

23. **What is React.memo?**

    * Higher-order component for memoization.
    * Prevents unnecessary re-renders.
    * Compares props before re-rendering.

24. **What is key in React lists?**

    * Unique identifier for list items.
    * Helps React optimize rendering.
    * Should be stable and unique.

25. **Why are keys important in React?**

    * Helps React identify changed elements.
    * Improves reconciliation efficiency.
    * Avoids re-rendering unchanged items.

26. **What is reconciliation in React?**

    * Process of updating DOM efficiently.
    * Uses diffing algorithm.
    * Minimizes actual DOM operations.

27. **What are fragments in React?**

    * Used to group multiple elements.
    * Written as `<></>`.
    * Prevents adding extra DOM nodes.

28. **What are portals in React?**

    * Renders children into a DOM node outside parent hierarchy.
    * Useful for modals, tooltips.
    * Created using `ReactDOM.createPortal()`.

29. **What are higher-order components (HOC)?**

    * Function that takes a component and returns a new one.
    * Used for reusing logic.
    * Example: authentication wrappers.

30. **What is the difference between HOC and Hooks?**

    * HOC → wraps components.
    * Hooks → reuse logic inside components.
    * Hooks are cleaner and modern approach.

31. **What are lifecycle methods in React class components?**

    * Mounting (constructor, componentDidMount).
    * Updating (componentDidUpdate).
    * Unmounting (componentWillUnmount).

32. **How does React handle events?**

    * Uses camelCase event names.
    * Event handlers are functions.
    * Synthetic events for cross-browser compatibility.

33. **What is prop drilling?**

    * Passing props through multiple levels.
    * Leads to unnecessary complexity.
    * Avoided using `useContext` or state management libraries.

34. **What is lazy loading in React?**

    * Loading components only when needed.
    * Improves performance.
    * Implemented with `React.lazy()` and `Suspense`.

35. **What is code splitting in React?**

    * Splits bundle into smaller chunks.
    * Loads only required code.
    * Reduces initial load time.

36. **What is React.StrictMode?**

    * Wrapper component for highlighting issues.
    * Checks for unsafe lifecycle methods.
    * Does not affect production build.

37. **What is context API in React?**

    * Provides global state without prop drilling.
    * Uses `createContext` and `useContext`.
    * Good for theme, language, auth.

38. **What is Redux in React?**

    * State management library.
    * Uses single global store.
    * Works with actions and reducers.

39. **What are reducers in Redux?**

    * Pure functions.
    * Take current state and action, return new state.
    * Must not mutate state directly.

40. **What are actions in Redux?**

    * Objects describing state changes.
    * Have `type` and optional `payload`.
    * Dispatched to reducers.

41. **What is Redux middleware?**

    * Functions between dispatch and reducer.
    * Used for async operations (API calls).
    * Example: Redux Thunk, Redux Saga.

42. **What is Redux Thunk?**

    * Middleware for async actions.
    * Allows dispatching functions.
    * Commonly used for API requests.

43. **What is Redux Saga?**

    * Middleware for handling side effects.
    * Uses generator functions.
    * Better for complex async flows.

44. **What is the difference between Redux and Context API?**

    * Redux: powerful, structured, suitable for large apps.
    * Context: simpler, built-in, suitable for small apps.
    * Redux offers middlewares and dev tools.

45. **What is server-side rendering (SSR) in React?**

    * Rendering React components on server.
    * Improves SEO and performance.
    * Used in frameworks like Next.js.

46. **What is hydration in React?**

    * Process of attaching event listeners to server-rendered HTML.
    * Converts static markup into interactive app.
    * Happens in SSR apps.

47. **What is Next.js?**

    * React framework.
    * Supports SSR, SSG, API routes.
    * Improves SEO and performance.

48. **What is Gatsby in React?**

    * React-based static site generator.
    * Focused on speed and SEO.
    * Uses GraphQL for data fetching.

49. **What is React Native?**

    * Framework for building mobile apps using React.
    * Supports Android and iOS.
    * Uses native components instead of web components.

50. **What are synthetic events in React?**

    * Wrapper around browser events.
    * Provides cross-browser compatibility.
    * Pooled for performance optimization.

51. **What are propTypes in React?**

    * Type-checking for props.
    * Helps catch bugs early.
    * Uses `prop-types` package.

52. **What is defaultProps in React?**

    * Defines default values for props.
    * Prevents `undefined` issues.
    * Useful for optional props.

53. **What is an error boundary in React?**

    * Component that catches JavaScript errors.
    * Prevents crashing of entire app.
    * Uses `componentDidCatch` lifecycle.

54. **What is React DevTools?**

    * Browser extension for debugging React apps.
    * Inspect component hierarchy and props/state.
    * Available in Chrome and Firefox.

55. **What is forwardRef in React?**

    * Passes ref from parent to child component.
    * Useful for accessing DOM nodes.
    * Created with `React.forwardRef()`.

56. **What is React Suspense?**

    * Handles lazy-loaded components.
    * Displays fallback UI while loading.
    * Works with `React.lazy()`.

57. **What are controlled vs uncontrolled inputs?**

    * Controlled → value controlled by React state.
    * Uncontrolled → value controlled by DOM.
    * Controlled ensures React has full control.

58. **What is the difference between React and Angular?**

    * React is a library; Angular is a framework.
    * React uses JSX; Angular uses TypeScript templates.
    * React is more flexible, Angular is opinionated.

59. **What is the difference between React and Vue?**

    * React uses JSX, Vue uses templates.
    * React ecosystem is larger.
    * Vue is simpler for beginners.

60. **What are stateless vs stateful components?**

    * Stateless → functional, no local state.
    * Stateful → manage local state.
    * Hooks allow functional components to be stateful.

61. **What is React Fiber?**

    * React’s new reconciliation engine.
    * Enables incremental rendering.
    * Improves performance for large apps.

62. **What is concurrent mode in React?**

    * Allows rendering multiple tasks simultaneously.
    * Improves responsiveness.
    * Helps with smoother UI updates.

63. **What are React keys best practices?**

    * Use stable unique IDs.
    * Avoid using array index.
    * Keys should not change across renders.

64. **What is strict equality check in React.memo?**

    * Shallow compare of props.
    * Prevents re-render if props unchanged.
    * Optimizes performance.

65. **What is diffing algorithm in React?**

    * Compares old and new virtual DOM.
    * Identifies minimal updates.
    * Uses heuristics for efficiency.

66. **What is batching in React?**

    * Groups multiple state updates into one re-render.
    * Improves performance.
    * Happens automatically in React 18.

67. **What is React DOM?**

    * Package for rendering React in browser DOM.
    * Provides `ReactDOM.render()` and `createRoot()`.
    * Separate from core React.

68. **What is React Fiber priority levels?**

    * Assigns priority to tasks.
    * High priority → urgent updates.
    * Low priority → background tasks.

69. **What is controlled form in React?**

    * Form data controlled by component state.
    * Provides full control of validation.
    * Recommended approach.

70. **What are pure components in React?**

    * Components that prevent unnecessary renders.
    * Implement `shouldComponentUpdate`.
    * Functional equivalent is `React.memo`.

71. **What is reconciliation strategy in React?**

    * Tree diffing.
    * Component diffing.
    * Element diffing.

72. **What are stateless functional components benefits?**

    * Easier to read and test.
    * Perform better (before hooks).
    * Encourage reusability.

73. **What is component composition?**

    * Building UI by combining smaller components.
    * Promotes reusability.
    * Preferred over inheritance.

74. **What is React hydration warning?**

    * Mismatch between server HTML and client render.
    * Happens in SSR apps.
    * Fixed by ensuring consistent output.

75. **What are suspense boundaries?**

    * Divide app into loading boundaries.
    * Show fallback UI per boundary.
    * Improves user experience.

76. **What is lazy initialization in useState?**

    * Initialize state with a function.
    * Function runs only once.
    * Optimizes performance.

77. **What is cleanup function in useEffect?**

    * Returned function inside `useEffect`.
    * Runs before component unmounts.
    * Used for unsubscribing or clearing timers.

78. **What is strict mode double rendering?**

    * In development, React renders components twice.
    * Helps detect side effects.
    * Only affects dev environment.

79. **What are React controlled checkboxes?**

    * Checked state stored in component.
    * Controlled via state updates.
    * Useful for form handling.

80. **What is React profiler?**

    * Tool to measure rendering performance.
    * Available in React DevTools.
    * Helps identify bottlenecks.

81. **What is the difference between useEffect and useLayoutEffect?**

    * `useEffect` runs after painting.
    * `useLayoutEffect` runs synchronously after DOM updates.
    * `useLayoutEffect` blocks painting until execution.

82. **What is useImperativeHandle hook?**

    * Customizes ref handling.
    * Works with `forwardRef`.
    * Exposes imperative methods to parent.

83. **What is shallow rendering in testing React?**

    * Renders component without children.
    * Used for unit testing.
    * Provided by Enzyme.

84. **What is Jest in React?**

    * JavaScript testing framework.
    * Provides assertions and mocks.
    * Often used with React Testing Library.

85. **What is React Testing Library?**

    * Lightweight testing library.
    * Focuses on user behavior.
    * Works well with Jest.

86. **What is snapshot testing in React?**

    * Captures component output.
    * Compares with saved snapshot.
    * Detects unintended changes.

87. **What is enzyme in React testing?**

    * Testing utility for React.
    * Provides shallow, mount, render APIs.
    * Useful for unit/integration testing.

88. **What is act() in testing React?**

    * Helper function in testing.
    * Ensures all updates are processed.
    * Prevents inconsistent test results.

89. **What is the difference between mount and shallow in Enzyme?**

    * `shallow` renders component only.
    * `mount` renders component + children.
    * `mount` is closer to real DOM.

90. **What are mock functions in Jest?**

    * Simulated functions.
    * Used for testing dependencies.
    * Verify calls and arguments.

91. **What are environment variables in React?**

    * Store config values.
    * Start with `REACT_APP_`.
    * Loaded via `.env` files.

92. **What is process.env in React?**

    * Object containing environment variables.
    * Accessed during build time.
    * Useful for API keys.

93. **What is tree shaking in React?**

    * Removing unused code.
    * Done by bundlers like Webpack.
    * Reduces bundle size.

94. **What is Hot Module Replacement (HMR)?**

    * Updates modules without full reload.
    * Speeds up development.
    * Provided by webpack-dev-server.

95. **What is webpack in React?**

    * Module bundler.
    * Converts code into optimized bundles.
    * Supports loaders and plugins.

96. **What is Babel in React?**

    * JavaScript compiler.
    * Transpiles JSX to JavaScript.
    * Ensures compatibility across browsers.

97. **What are React build optimizations?**

    * Minification and compression.
    * Code splitting.
    * Tree shaking.

98. **What is service worker in React?**

    * Script running in background.
    * Enables offline support.
    * Used in PWA apps.

99. **What is a PWA in React?**

    * Progressive Web App.
    * Works offline and installs like native.
    * Uses service workers and manifest.

100. **What is the future of ReactJS?**
   * Focus on concurrent rendering.
   * More performance optimizations.
   * Strong ecosystem growth.


<!-- 
_____   ____ _______   _   _ ______ _______ 
|  __ \ / __ |__   __| | \ | |  ____|__   __|
| |  | | |  | | | |    |  \| | |__     | |   
| |  | | |  | | | |    | . ` |  __|    | |   
| |__| | |__| | | |    | |\  | |____   | |   
|_____/ \____/  |_|    |_| \_|______|  |_|  
-->                                        

## .NET 

| **Term**   | **Full Form**                     | **Meaning (1 line)** |
|------------|-----------------------------------|-----------------------|
| ASP        | Active Server Pages               | Microsoft’s old server-side scripting technology. |
| .NET       | Network Enabled Technologies      | Framework for building apps on Windows (web, desktop, mobile). |
| ASP.NET    | Active Server Pages .NET          | Web framework built on top of .NET. |
| MVC        | Model View Controller             | Design pattern separating business logic, UI, and input control. |
| WCF        | Windows Communication Foundation  | Framework for building service-oriented applications. |
| WPF        | Windows Presentation Foundation   | UI framework for building Windows desktop applications. |
| ADO.NET    | ActiveX Data Objects .NET         | Data access framework to interact with databases. |
| CLR        | Common Language Runtime           | Runtime environment for executing .NET programs. |
| CLS        | Common Language Specification     | Rules to ensure cross-language interoperability in .NET. |
| CTS        | Common Type System                | Defines how types are declared and used in .NET. |
| DTO        | Data Transfer Object              | Simple object used to transfer data between layers without business logic. |
| EF         | Entity Framework                  | Object-relational mapper (ORM) for database operations in .NET. |


1. **What is .NET Core?**
   * It is a free and open-source framework developed by Microsoft.
   * It is cross-platform – runs on Windows, Linux, and macOS.
   

2. **Waht are the advanteges of .NET core over .NET framework?**
   * Cross-platform → Runs on Windows, Linux, and macOS (but .NET Framework is Windows-only).
   * It is modular and lightweight – applications can include only the required packages (via NuGet).
   * .NET core support containerized deployment (Docker)
   * .NET core is free and open-source but .NET framework is paid
   * .NET core Support multiple IDE but .NET framework supports only Visual Studio 

3. **What is the role of Program.cs file in ASP.NET Core**
   * It contains the application startup code

4. **What is Dependency Injection in ASP.NET core**
   * It is software design pattern
   * It allows use to develop loosely coupled application.

<!-- 
  _    _ _______ __  __ _      
 | |  | |__   __|  \/  | |     
 | |__| |  | |  | \  / | |     
 |  __  |  | |  | |\/| | |     
 | |  | |  | |  | |  | | |____ 
 |_|  |_|  |_|  |_|  |_|______|

-->                            
                               
## HTML
1. **What is HTML?**
   * HTML stands for HyperText Markup Language. 
   * It is used to design web pages using a markup language. 
   * HTML is a combination of Hypertext and Markup language. 
   * Hypertext defines the link between the web pages. 
   * The markup language is used to define the text document within the tag which defines the structure of web pages.

2. **What are the various markup languages available?**
   * HTML: Hypertext Markup Language
   * KML: Key whole Markup Language
   * MathML: Mathematical Markup Language
   * SGML: Standard Generalized Markup Language
   * XHTML: eXtensible Hypertext Markup Language
   * XML: eXtensible Markup Language

3. **What is !DOCTYPE?**
   * The doctype is not an element or tag, it lets the browser know about the version of or standard of HTML

4. **Difference between HTML Tag & HTML Element**

   **HTML Tag**
   * Either opening or closing is used to mark the start or end of an element.
   * Used to hold the HTML element.
   * Starts with < and ends with >

   **HTML Element**
   * Collection of a start tag, end tag, and its attributes.
   * Holds the content.
   * Whatever is written within an HTML tag are HTML elements.

5. **What are the various heading tags and their importance?**
   * There are 6 levels of headings defined by HTML. 
   * These six heading elements are H1, H2, H3, H4, H5, and H6
   * With H1 being at the highest level and H6 at the least.

6. **How to redirect to a particular section of a page using HTML?**
   * One can use the anchor tag to redirect to a particular section on the same page.

7. **What are attributes?**
   * An attribute is used to provide extra or additional information about an element.

8. **What is the use of alt attribute in images?**
   * The img alt attribute is used to specify the alternate text for an image.

9. **What are the different types of lists in HTML?**
   * Unordered List: It will list the items using plain bullets.
   * Ordered List: It will use different schemes of numbers to list your items.
   * Definition List: It arranges your items in the same way as they are arranged in a dictionary.

10. **What is the difference between block and inline elements?**
   * Block level elements would create a new line of content, stacking on top
of one anther.
   * Inline elements stay within the flow of what surrounds them.

11. **Difference between DOM & HTML?**
   * HTML: Markup language (what we write).
   * DOM: Object model (what browser creates).
   * HTML is static, DOM is dynamic.
   * DOM can be modified with JavaScript, HTML cannot.

12. **What is DOM?**
   * DOM = Document Object Model.
   * It is a tree-like structure of an HTML page created by the browser.
   * JavaScript uses DOM to read, add, update, or delete elements on a webpage.

<!-- 
   _____  _____ _____ 
  / ____|/ ____/ ____|
 | |    | (___| (___  
 | |     \___ \\___ \ 
 | |____ ____) ____) |
  \_____|_____|_____/ 
                      
                      
 -->
## CSS
1. **What is CSS?**
   * It stands for *Cascading Style Sheets*
   * CSS allows you to apply styles to web pages.

2. **What is the current version of CSS?**
   * CSS3 is the latest version of CSS.

3. **List any three CSS Frameworks.**
   * Bootstrap
   * Materialize
   * Tailwind CSS

4. **In how many ways can we add CSS to our HTML file?**
   * In Three ways we can add CSS in our HTML file
   * Inline CSS: This kind of style is specified within an HTML tag using the style attribute.
   * Internal or Embedded CSS: the CSS is embedded within the HTML file.
   * External CSS: written in a separate file with .css extension

5. **Which type of CSS holds the highest priority?**
   * Inline CSS has the highest priority

6. **What are CSS Selectors?**
   * CSS Selectors are used to selecting HTML elements based on their element name, id, attributes, class name, etc. It can select one or more elements simultaneously.

7. **What does the ‘a’ in rgba mean?**
   * RGBA contains A (Alpha) which specifies the transparency of elements. 

<!-- 
   ____   ____  _____   _____ 
  / __ \ / __ \|  __ \ / ____|
 | |  | | |  | | |__) | (___  
 | |  | | |  | |  ___/ \___ \ 
 | |__| | |__| | |     ____) |
  \____/ \____/|_|    |_____/ 
                              
                              
 -->
## OOPs
- work in progress

<!-- 
  _____  _____  ____  __  __  _____            _____  ____  __  __  _____ 
 |  __ \|  __ \|  _ \|  \/  |/ ____|   ___    |  __ \|  _ \|  \/  |/ ____|
 | |__) | |  | | |_) | \  / | (___    ( _ )   | |  | | |_) | \  / | (___  
 |  _  /| |  | |  _ <| |\/| |\___ \   / _ \/\ | |  | |  _ <| |\/| |\___ \ 
 | | \ \| |__| | |_) | |  | |____) | | (_>  < | |__| | |_) | |  | |____) |
 |_|  \_|_____/|____/|_|  |_|_____/   \___/\/ |_____/|____/|_|  |_|_____/ 
                                                                          
                                                                          
 -->
 ## RDBMS & DBMS
 - work on progress

<!-- 

   _____  ____  _      
  / ____|/ __ \| |     
 | (___ | |  | | |     
  \___ \| |  | | |     
  ____) | |__| | |____ 
 |_____/ \___\_|______|
                       
                       
 -->
## SQL
- work in progress

<!-- 

  _   _  ____     _____  ____  _      
 | \ | |/ __ \   / ____|/ __ \| |     
 |  \| | |  | | | (___ | |  | | |     
 | . ` | |  | |  \___ \| |  | | |     
 | |\  | |__| |  ____) | |__| | |____ 
 |_| \_|\____/  |_____/ \___\_|______|
                                      

 -->
## noSQL
- work in progress

<!-- 

   _____ _____ _______ 
  / ____|_   _|__   __|
 | |  __  | |    | |   
 | | |_ | | |    | |   
 | |__| |_| |_   | |   
  \_____|_____|  |_|   
                       
                       
 -->
## Git and Github
- work in progress


<!-- 
       _    __      __      _____  _____ _____  _____ _____ _______ 
      | |  /\ \    / /\    / ____|/ ____|  __ \|_   _|  __ |__   __|
      | | /  \ \  / /  \  | (___ | |    | |__) | | | | |__) | | |   
  _   | |/ /\ \ \/ / /\ \  \___ \| |    |  _  /  | | |  ___/  | |   
 | |__| / ____ \  / ____ \ ____) | |____| | \ \ _| |_| |      | |   
  \____/_/    \_\/_/    \_|_____/ \_____|_|  \_|_____|_|      |_|   
                                                                    
                                                                  
 -->
## JavaScript

1. **Block Scope vs Local Scope**
   * In local scope, variables are typically defined within a function
   * While block scope is created within code blocks like if, for, or while statements.

2. **What is Callback hell?**
   * Callback hell, also known as the "pyramid of doom"
   * It is a phenomenon in JavaScript that occurs when multiple callback functions are nested inside each other.

3. **How many arguments hold promise in JavaScript?**
   * Two Arguments
   * Resolve and Reject

4. **What is map filter and reduce in javascript?**
   * Map, reduce, and filter are all array methods in JavaScript.
   * `map():` the map method is used to create a new array from an existing one.
   * `filter():` removes elements that are not required and creates a new array containing the ones needed.
   * `reduce():` reduces all array elements into a single value.

5. **How many scopes are in Javascript?**
   * Mainly Four scopes
      * Global Scope
      * Local Scope
      * Block level scope
      * **Lexical scope:** is the ability of a function scope to access variables from the parent scope.

6. **What is closure in JavaScript?**
   * A **closure** is the combination of a function bundled together or nested function.
   * A closure gives you access to an outer function's scope from an inner function.

7. **What is Hoisting?**
   * Hoisting is JavaScript's default behavior of moving declarations to the top.
   * A variable can be *used* before it has been declared.
   * let, var, const, normal function will be hoisted
   * but `let, const` will go to *Temporal Dead Zone* so *we'll get error*
   * JavaScript only hoists declarations, not initializations.
   * function expression and class expression will **NOT** be hoisted

8. **What is JSON?**
   * JavaScript Object Notation
   * It is  a lightweight  data interchange format (between client and server using api).
   * It consist  of key-value pairs

9. **Data Types in JavaScript**
   * Primitive: It stores the single value (number, string, boolean, undefine, null)
   * Non-Primitive: It holds multiple values (array, object, functions)

10. **Difference between null and undefine**
   * undefined: Variable is declared but not assigned any value.
   * null:  Variable is assigned with "no value" (intentional empty value).
   * null == undefined → true (loose equality).
   * null === undefined → false (strict equality).
11. **What is operator precedence?**
   * As per the operator precedence, operator with *higher* precedence are evaluated first.
   * It is like a BODMAS rule in maths