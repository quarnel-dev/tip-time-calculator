# Tip Time Calculator

[Read in Russian](README.ru.md) | English

Android tip calculator built with Jetpack Compose. A college assignment for the **Mobile Development** course.

<p align="center">
  <img src="assets/photo_1.jpg" alt="Screenshot" width="220">
</p>

The app lets the user enter a bill amount and automatically calculates a 15% tip, displaying the result in local currency format. Built as part of a lab assignment on state management in Jetpack Compose.

## Stack

- Kotlin
- Jetpack Compose
- Material 3    
- Gradle (Kotlin DSL)

## Features

- Bill amount input via text field
- Automatic tip calculation (15%)
- Currency-formatted output
- Numeric keyboard for input

## What I Learned

- **State & MutableState** — observable state in Compose
- **`remember`** — preserving state across recompositions
- **Property delegation (`by`)** — cleaner `MutableState` access
- **State Hoisting** — moving state up to the parent composable
- **Positional formatting** — `%s` placeholders in `strings.xml`
- **Stateless composables** — reusable, testable UI components

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/quarnel-dev/tip-time-calculator.git
```

2. Open the project in Android Studio
3. Wait for Gradle sync
4. Run on an emulator or physical device (Android 7.0+)

*Made with ❤️ by Quarnel*
