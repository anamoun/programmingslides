# React topics checklist

This is a checklist for React topics you can learn.

This list is not intended for going through it in order.

## React fundamentals

- [ ] use-cases of React
- [ ] JavaScript basics for React
  - [ ] immutability / data management without mutations
    - [ ] updating properties of objects
    - [ ] adding properties to objects
    - [ ] adding elements to arrays (create)
    - [ ] replacing elements in arrays (update)
    - [ ] removing elements from arrays (delete)
  - [ ] destructuring assignment with arrays and objects
  - [ ] imports and exports: named and default
  - [ ] "bare" / "blank" return statements
- [ ] state
  - [ ] using the _state hook_ (_useState_)
  - [ ] minimal state and derived values
  - [ ] input state
    - [ ] connecting input values to state with _value_ and _onChange_
    - [ ] handling various input types
    - [ ] handling numeric inputs
  - [ ] importance of immutability in React state
  - [ ] using the state hook with TypeScript
- [ ] JSX
  - [ ] switching from JS to XML mode
  - [ ] switching from XML to JS mode in content
  - [ ] switching from XML to JSX mode in element properties
  - [ ] including strings and numbers
  - [ ] setting boolean HTML properties (e.g. _disabled_)
  - [ ] _className_
  - [ ] adding event handlers in JSX
  - [ ] whitespace in HTML vs whitespace in JSX
  - [ ] escaping characters like _\<_, _\&_, _\>_
  - [ ] comments
  - [ ] if / else
    - [ ] the operator `&&` in JS and JSX
  - [ ] repeating elements
    - [ ] the _key_ property
  - [ ] event handlers
    - [ ] accessing the event object
    - [ ] `onClick={handleEvent}` vs `onClick={handleEvent()}`
    - [ ] `preventDefault`
    - [ ] event types in TypeScript
  - [ ] JSX fragments
  - [ ] security and XSS attacks
    - [ ] `dangerouslySetInnerHtml`
  - [ ] compilation of JSX
- [ ] TypeScript basics for React
  - [ ] TypeScript benefits: autocompletion and error reporting
  - [ ] type declarations for libraries
  - [ ] type inference
  - [ ] declaring types of variables
  - [ ] primitive types: _number_, _string_, _boolean_
  - [ ] array types
  - [ ] object types
    - [ ] optional entries
  - [ ] any
  - [ ] type aliases and interfaces
    - [ ] exporting and importing type aliases and interfaces
  - [ ] function signatures and function types
    - [ ] _void_
  - [ ] type assertions
  - [ ] using (pre-existing) generics
  - [ ] union types
- [ ] development environment
  - [ ] formatter (e.g. _prettier_)
  - [ ] linter (e.g. _eslint_)
  - [ ] developing with node.js and npm
  - [ ] initializing a React project (e.g. via _create-react-app_)
  - [ ] development server
  - [ ] production build and deployment
  - [ ] _React Developer Tools_ browser plugin
  - [ ] project file structure: common approaches
- [ ] components
  - [ ] overview: function components and class components
  - [ ] defining components as functions
  - [ ] in which component should some state live?
  - [ ] using existing component libraries
  - [ ] props in custom components
  - [ ] events in custom components
  - [ ] passing content to components
  - [ ] wrapping existing elements in components (e.g. `button` -> `StyledButton`)
- [ ] hooks
  - [ ] what are hooks?
  - [ ] rules of hooks
  - [ ] overview of built-in hooks and hooks from libraries
  - [ ] creating custom hooks

## React libraries and tools

- [ ] React ecosystem and libraries for different purposes (overview)
  - [ ] component libraries
  - [ ] API queries
  - [ ] routing
  - [ ] styling tools
  - [ ] form handling
  - [ ] state management
- [ ] querying APIs
  - [ ] network requests in JavaScript
  - [ ] API query libraries for React: e.g. _react-query_
  - [ ] overview: _useEffect_
- [ ] routing basics
  - [ ] client-side routing
  - [ ] _react-router_ library
    - [ ] defining routes
    - [ ] using links
    - [ ] nested routes
    - [ ] route parameters
    - [ ] navigation from JavaScript
    - [ ] active link style
- [ ] styling tools
  - [ ] tools for external stylesheets
    - [ ] _classnames_ package
    - [ ] CSS modules
    - [ ] SCSS
  - [ ] CSS-in-JS
    - [ ] inline styles
    - [ ] "styled components"
  - [ ] animations
    - [ ] animating appearance / disapperance of elements
- [ ] forms
  - [ ] form validation strategies
  - [ ] libraries for forms: _react-hook-form_, _formik_
- [ ] state management overview
  - [ ] libraries: _zustand_, _redux_, _mobX_, ...

## Intermediate React

- [ ] state hook in detail
  - [ ] state transformer functions, outdated state
  - [ ] state initialization function
- [ ] class components
  - [ ] defining components as classes
  - [ ] props in class components
  - [ ] state in class components
  - [ ] potential problems with _this_
- [ ] side effects
  - [ ] side effects in class components
  - [ ] side effects in function components
  - [ ] cleaning up side effects
  - [ ] "strict mode" and double invocation of side effects
- [ ] context
  - [ ] "pure providers" and "stateful providers"
  - [ ] stateful context with _constate_
  - [ ] context with vanilla React
- [ ] refs
  - [ ] refs for storing objects that don't influence the rendering
  - [ ] using refs for avoiding outdated state
  - [ ] the _ref_ property for accessing DOM elements
  - [ ] the _ref_ property in custom components

## Advanced concepts and patterns

- [ ] higher-order components
- [ ] render props
- [ ] portals
- [ ] error boundaries
- [ ] performance optimization
  - [ ] React devtools and performance
  - [ ] memoization
  - [ ] memoization of expensive calculations
  - [ ] skipping unneeded rerenders
  - [ ] virtual DOM
  - [ ] lazy-loading components
  - [ ] reducing bundle size

## Testing

- [ ] testing
  - [ ] assertions
  - [ ] test runners: _Jest_, _node:test_
  - [ ] mocking in JavaScript, mocking network responses
  - [ ] end-to-end testing libraries: _cypress_, _playwright_
  - [ ] testing React components: _react-testing-library_

## State management

- [ ] state management: intermediate
  - [ ] concept: actions
  - [ ] concept: reducers
  - [ ] reducer hook
  - [ ] overview: Redux
  - [ ] immutability helper libraries (_immer.js_, _immutable.js_)

## Other topics

- [ ] React and GraphQL / Apollo
- [ ] user authentication
- [ ] PWAs
- [ ] React Native
- [ ] Internationalization
- [ ] pre-rendering and next.js
- [ ] Redux in depth