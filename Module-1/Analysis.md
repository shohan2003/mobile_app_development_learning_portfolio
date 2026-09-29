# Module 1 Analysis: Android Basics & Jetpack Compose

## 1. Overview
In this module, I completed the foundational Android Developer pathways focused on Jetpack Compose. The exercises involved constructing declarative user interface elements, building basic screen layouts, and displaying text and image components.

## 2. Key Technical Concepts Learned
* **Composable Functions:** Annotating functions with `@Composable` to generate dynamic UI elements directly in Kotlin code.
* **Layout Structure:** Utilizing `Column`, `Row`, and `Box` composables to organize visual components vertically, horizontally, and layered.
* **Modifiers:** Applying modifiers such as `.padding()`, `.fillMaxSize()`, and `.background()` to customize layout spacing and sizing.

## 3. Comparative Analysis
* **Imperative UI (XML) vs. Declarative UI (Jetpack Compose):** Traditional XML requires manual view binding and managing state synchronization across UI trees. Jetpack Compose automatically updates UI elements whenever state changes occur, significantly reducing boilerplate code and preventing view-binding bugs.

## 4. Strengths and Limitations
* **Strengths:** Rapid UI iteration with Android Studio interactive previews, type-safe layout construction in Kotlin, and modular composable design.
* **Limitations:** Requires understanding state re-composition lifecycle to avoid unintended UI re-renders and performance overhead.
