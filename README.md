# BMI Calculator (Android)

Android app that calculates Body Mass Index (BMI) from age, weight, height, and gender. Results are categorized and can be saved locally.

## Features

- **BMI calculation** — Input age, weight, height; select gender; get BMI and category.
- **Local storage** — Save results with SharedPreferences.
- **UI** — Material Design, color-coded results (Underweight / Normal / Overweight / Obese), input validation.

## Tech stack

- **Java** · **Gradle** · **Android**
- AndroidX (AppCompat, ConstraintLayout), View Binding, SharedPreferences

## Requirements

- Android Studio 4.1+
- JDK 11+
- Min SDK: API 28 (Android 9.0) · Target SDK: API 34

## Setup & run

1. Clone the repository.
2. Open the project in Android Studio and sync Gradle.
3. Connect a device or start an emulator, then Run.

## Project structure

- `app/` — app module, activities (e.g. Calculation, Results), utilities (BMI calculation, SharedPreferences).
- `build.gradle` / `settings.gradle` — Gradle configuration.

## License

MIT
