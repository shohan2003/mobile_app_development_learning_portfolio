# Course Learning Portfolio Reflection

## 1. Overall Learning Experience
Working through the official Android Developer pathways provided a hands-on foundation in modern Android development using Jetpack Compose and Kotlin. Transitioning from basic layout building to full app architecture enabled a progressive understanding of real-world mobile app design patterns.

## 2. Challenges and Debugging
* **State Management Issues:** Managing re-composition behavior caused initial bugs where form fields reset unexpectedly. This was resolved by implementing state hoisting and using `ViewModel` properties.
* **Gradle Build Errors:** Version mismatches between Compose compiler dependencies were resolved by updating dependency blocks in `build.gradle.kts`.

## 3. Technical Decision Justification
* Adopting Jetpack Compose over traditional XML layouts allowed faster UI construction and cleaner code maintainability.
* Structuring projects with `ViewModel` ensured reliable state handling and clean separation of concerns.

## 4. Future Development
In future mobile engineering tasks, I plan to explore asynchronous data processing using Kotlin Coroutines and integrate remote API communication using Retrofit.
