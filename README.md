# StateCraft: Mastering State Management with Redux & Context API

A project series demonstrating different approaches to state management in React applications by building an interactive counter application. Starting with React’s built-in useState hook, we progressively implement more sophisticated state management solutions including Context API and Redux. The project showcases how to share state across multiple components and maintain application-wide data consistency.

## Objectives

1. Understand fundamental React state management using useState
2. Learn to implement global state management with Context API
3. Master Redux for complex state management scenarios
4. Compare different state management solutions
5. Implement state persistence across components
6. Understand the concept of single source of truth
7. Learn to structure applications for scalable state management

## Project Structure
Common Files
1. pages/: Contains page components
      - counter-app.tsx: Main counter application
2. components/: Reusable UI components
      - layouts/: Application layout components
      - Header.tsx: Shared header component
  
## Variant-Specific Files
1. useState Version (0x04)
    - Simple state management within a single component
    - Context API Version (0x05)
2. context/CountContext.tsx: Context provider and hooks
    - Modified _app.tsx to wrap application with provider
3. Redux Version (0x06)
    - store/store.ts: Redux store configuration
    - Updated components to use Redux hooks
  
## Expected Outcomes
1.  A working counter application with three different state management implementations
2.  Understanding of when to use each state management solution
3.  Practical experience with modern React state management patterns
4.  A foundation for building more complex stateful applications
5.  Ability to make informed decisions about state management in your projects
