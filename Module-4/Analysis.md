# Module 4 Analysis: Architecture & App Navigation

## 1. Overview
This module focused on structuring complex Android applications using recommended architecture patterns, integrating `ViewModel` for UI state persistence, and managing multi-screen navigation using the Jetpack Navigation component.

## 2. Key Technical Concepts Learned
* **ViewModel Architecture:** Separating UI logic from business logic while preserving screen data across configuration changes (e.g., screen rotation).
* **Jetpack Navigation Component:** Utilizing `NavHost`, `NavController`, and composable routes to transition between application screens seamlessly.
* **Unidirectional Data Flow (UDF):** Ensuring data flows down from ViewModel to UI while user events flow up from UI to ViewModel.

## 3. Comparative Analysis
* **Direct Composable State vs. ViewModel State:** Direct composable state managed via `rememberSaveable` is reset during app lifecycle events or complex navigation flows. `ViewModel` state survives screen orientation changes and decouples business decisions completely from layout renderers.

## 4. Strengths and Limitations
* **Strengths:** Maintainable app code structure, robust handling of lifecycle configuration changes, and streamlined multi-screen transitions.
* **Limitations:** Increases upfront architectural complexity for small applications and requires strict navigation route string management.
