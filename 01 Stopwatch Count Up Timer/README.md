# React Stopwatch

A minimalist **stopwatch application** built with React and styled using Tailwind CSS. This project demonstrates fundamental React concepts like component-based structure, state management, effect hooks, and conditional rendering. It is perfect for beginners to understand React's core principles in a practical way.

## Project Overview

This stopwatch allows users to start, stop, and reset a timer. The display updates every 10 milliseconds and shows hours, minutes, seconds, and milliseconds in a clean and responsive interface. It’s a small project, but it effectively teaches key React concepts.

## Key React Concepts Covered

1. **Component-based Structure**: 
   The entire app is built as a self-contained `App` component, following React's philosophy of breaking down UIs into reusable, manageable components.

2. **State Management (`useState`)**:
   The app manages two key pieces of state: 
   - `time` to keep track of the elapsed time.
   - `running` to control whether the timer is active or paused.

3. **Effect Hook (`useEffect`)**:
   The project uses `useEffect` to handle the timer logic. The timer starts when `running` is set to `true` and stops when it is `false`. The interval is cleaned up efficiently to prevent memory leaks.

4. **Conditional Rendering**:
   The **Start** and **Stop** buttons are conditionally rendered based on the `running` state, demonstrating dynamic updates to the UI based on state changes.

5. **Event Handling**:
   Simple `onClick` event handlers are used to manage user interactions, such as starting, stopping, or resetting the timer.

6. **Tailwind CSS Styling**:
   The app uses Tailwind CSS for quick, utility-first styling, ensuring the UI is responsive and well-designed with minimal custom CSS.

