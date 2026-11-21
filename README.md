
<div align="center">

<img src="https://mark.sylphx.com/api/v1/mark/hero?type=aurora&theme=ocean&text=SOMNIA&desc=Sleep%2C%20made%20simpler." width="100%" />

<br/>

<a href="https://developer.android.com/">
<img src="https://flat.badgen.net/badge/Android/16/1E56A0?labelColor=1B3A5C&icon=android" />
</a>
<a href="https://kotlinlang.org/">
<img src="https://flat.badgen.net/badge/Kotlin/2.2.10/526780?labelColor=1B3A5C&icon=kotlin" />
</a>
<a href="https://developer.android.com/compose">
<img src="https://flat.badgen.net/badge/Jetpack%20Compose/UI/6750A4?labelColor=1B3A5C&icon=jetpackcompose" />
</a>
<a href="https://m3.material.io/">
<img src="https://flat.badgen.net/badge/Material%203/Expressive/8AB4F8?labelColor=1B3A5C" />
</a>

<br/>

<a href="https://github.com/Lowestm3e/Somnia">
<img src="https://flat.badgen.net/badge/version/0.1.12.1/D3E3FD?labelColor=1B3A5C" />
</a>
<img src="https://flat.badgen.net/badge/status/in%20development/526780?labelColor=1B3A5C" />

</div>

---

## About

SOMNIA is a sleep-tracking app for Android, built with Kotlin and Jetpack Compose.

The project uses Material 3 Expressive and a custom Deep Blue theme. I'm building it with a focus on sleep logging, sleep history and useful insights.

## Screens

| Screen | Purpose |
|---|---|
| Sleep | Start and stop sleep sessions |
| Insights | View sleep history and statistics |
| Settings | Change app preferences |
| About | App information and credits |

## Features

- Sleep session tracking
- Sleep history stored locally
- Sleep statistics and charts
- Light and dark themes
- Optional AMOLED mode
- Customisable sleep settings

*Some features are still being developed.*

## Design

SOMNIA uses a Deep Blue colour scheme.

| Colour | Hex |
|---|---|
| Primary | `#1E56A0` |
| Primary dark | `#8AB4F8` |
| Primary container | `#D3E3FD` |
| Dark primary container | `#1B3A5C` |
| Dark background | `#0D131D` |
| Dark surface | `#161F2E` |

The interface uses Material 3 Expressive components, rounded typography and Material Symbols.

## Built with

- Kotlin
- Jetpack Compose
- Material 3 Expressive
- Room
- Kotlin Coroutines
- Flow
- Navigation Compose
- KSP

## Project details

| | |
|---|---|
| Name | SOMNIA |
| Developer | Lowestm3e |
| Package | `com.lowestm3e.somnia` |
| Version | `0.1.12.1` |
| Minimum Android SDK | 31 |
| Compile SDK | 37 |
| Target SDK | 37 |

## Building

Clone the repository:

```bash
git clone https://github.com/Lowestm3e/Somnia.git
```

Open the project in Android Studio and let Gradle sync.

To build a debug APK on Windows:

```powershell
.\gradlew assembleDebug
```

The APK will be generated at:

```text
app/build/outputs/apk/debug/app-debug.apk
```

## Development

SOMNIA is a personal development project and is still a work in progress.

Current work includes improving sleep tracking, connecting the screens to the local database and refining the interface.

---

<div align="center">

**SOMNIA**

[GitHub repository](https://github.com/Lowestm3e/Somnia)

</div>
