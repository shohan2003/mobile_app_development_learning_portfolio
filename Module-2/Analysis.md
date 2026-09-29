# Module 2 Analysis: Building App UI & State Management

## 1. Overview
This module focused on creating dynamic user interfaces by handling state changes, accepting user input through interactive fields, and implementing logic for dynamic app updates.

## 2. Key Technical Concepts Learned
* **State Management:** Using `remember` and `mutableStateOf` to store dynamic screen values across re-compositions.
* **State Hoisting:** Moving state to a parent composable to make child composables stateless, reusable, and easily testable.
* **Interactive UI Controls:** Implementing `TextField`, `Button`, and custom layout components for user interaction.

## 3. Comparative Analysis
* **Stateful vs. Stateless Composables:** Stateful composables manage their own internal state, making them self-contained but harder to reuse. Stateless composables receive state from parameters, enabling cleaner UI separation, easier previewing, and enhanced modular testability.

## 4. Strengths and Limitations
* **Strengths:** Clear separation of UI presentation from business state logic, making dynamic inputs easily manageable.
* **Limitations:** State hoists must be carefully structured to prevent deep passing of callbacks down complex UI trees.
