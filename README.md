
<div align="center">

# 🌙 SOMNIA

### Sleep, made simpler.

A modern Android sleep-tracking application built with Kotlin, Jetpack Compose and Material 3 Expressive.

[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)](https://developer.android.com/)
[![Language](https://img.shields.io/badge/Language-Kotlin-7F52FF?logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![UI](https://img.shields.io/badge/UI-Jetpack%20Compose-4285F4?logo=jetpackcompose&logoColor=white)](https://developer.android.com/compose)
[![Design](https://img.shields.io/badge/Design-Material%203%20Expressive-6750A4)](https://m3.material.io/)
[![Status](https://img.shields.io/badge/Status-In%20Development-orange)]()

</div>

---

## About

**SOMNIA** is an Android application designed to make sleep tracking simple, accessible and intuitive.

Built around Google's Material 3 Expressive design system, SOMNIA combines a distinctive visual identity with an Android-first experience.

The project is developed using Kotlin and Jetpack Compose, with Room providing local database storage.

## Features

- **Sleep Tracking** – Record bedtime, wake-up time and sleep duration.
- **Sleep Insights** – Explore sleep statistics and visualisations.
- **Personalisation** – Configure sleep preferences and application settings.
- **Dark Mode** – Deep Blue dark theme with AMOLED-friendly options.
- **Local Storage** – Store sleep sessions locally using Room.
- **Expressive Interface** – Designed around Material 3 Expressive.

*Features are actively being developed. Not all functionality is currently available.*

## Screenshots

<div align="center">

| Sleep | Insights | Settings | About |
|:---:|:---:|:---:|:---:|
| Coming soon | Coming soon | Coming soon | Coming soon |

</div>

## Design

SOMNIA uses a Deep Blue visual identity, inspired by the calm and quiet of nighttime.

| Element | Value |
|---|---|
| Light primary | `#1E56A0` |
| Dark primary | `#8AB4F8` |
| Light container | `#D3E3FD` |
| Dark container | `#1B3A5C` |
| Dark background | `#0D131D` |
| Dark surface | `#161F2E` |
| Typeface | Google Sans Flex Rounded |
| Icons | Material Symbols Rounded |

The interface follows Android design conventions and uses Material 3 Expressive components.

## Built With

- [Kotlin](https://kotlinlang.org/)
- [Jetpack Compose](https://developer.android.com/compose)
- [Material 3 Expressive](https://m3.material.io/)
- [Room](https://developer.android.com/training/data-storage/room)
- [Kotlin Coroutines](https://kotlinlang.org/docs/coroutines-overview.html)
- [Kotlin Flow](https://kotlinlang.org/docs/flow.html)
- [KSP](https://kotlinlang.org/docs/ksp-overview.html)
- [Gradle](https://gradle.org/)

## Project Information

| Detail | Information |
|---|---|
| Developer | Lowestm3e |
| Application | SOMNIA |
| Package | `com.lowestm3e.somnia` |
| Current version | `0.1.12.1` |
| Platform | Android |
| Minimum Android SDK | 31 |
| Target SDK | 37 |
| Language | Kotlin |
| UI Framework | Jetpack Compose |

## Getting Started

### Requirements

- Android Studio
- JDK 17 or compatible Gradle JVM
- Android SDK 37

### Clone the repository

```bash
git clone https://github.com/Lowestm3e/Somnia.git
```

### Open the project

1. Open Android Studio.
2. Select **Open**.
3. Select the cloned `Somnia` folder.
4. Allow Gradle to synchronise.
5. Run the application on an Android device or emulator.

### Build an APK

On Windows:

```powershell
.\gradlew assembleDebug
```

The APK will be generated at:

```text
app/build/outputs/apk/debug/app-debug.apk
```

## Development Status

SOMNIA is a work in progress.

Development is focused on establishing the core application experience, including reliable sleep logging, persistent storage, genuine sleep insights and a consistent Material 3 Expressive interface.

## Developer

**Lowestm3e**

GitHub: [@Lowestm3e](https://github.com/Lowestm3e)

---

<div align="center">

**SOMNIA**

*A little more rest. A little better tomorrow.*

</div>
