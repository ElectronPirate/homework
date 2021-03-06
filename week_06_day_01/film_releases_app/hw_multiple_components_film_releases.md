# Homework: React Film Releases

When creating React applications, we want to break up our UI into components, so each component is responsible for one part of the page. Your task for this homework is to start to think about how you might approach this task in your own applications by reading an article published by Facebook (creators of React) and examining an existing codebase.

## Reading

Thinking In React (20 mins) https://facebook.github.io/react/docs/thinking-in-react.html

## Film Releases Application

Run the Film Releases Application:

```bash
npm install
npm start
```
Your task is to get familiar with the application.

## Part 1
Draw a diagram that details:
  - the component hierarchy (which component renders which)
  - any props that are passed from parent to child components
  - any state inside any of the components
  
  
  

## Part 2
Answer the following questions:
  1. Where do we directly access an element from the DOM in our React application?
  In index.js
  2. From looking at the code, what do you think might be the difference between the components in the `containers` and `components` directories?
  Containers seem to store some data that is being referenced, Components do things.
  3. What is the responsibility of the `ReleasesBox` component?
  It's a container for movie links - App.js uses it and it renders header, movie list and more releases.
  3. What is the responsibility of the `MovieList` component?
  It creates a list of movies which is an array.
  4. What is the responsibility of the `MovieItem` component?
  Holds movie links used in MovieList.
  
