# Shishu Sneha

Shishu Sneha is a clean starter Android project structure that you can open in Android Studio or VS Code and push directly to GitHub. This repository is designed as a professional starting point for a maternal and child care application built with Kotlin and Jetpack Compose.

## Folder Structure

```text
shishu-sneha/
├── app/
│   ├── src/main/
│   │   ├── java/com/shishusneha/
│   │   │   ├── MainActivity.kt
│   │   │   └── ui/theme/
│   │   ├── res/values/
│   │   └── AndroidManifest.xml
│   ├── build.gradle.kts
│   └── proguard-rules.pro
├── build.gradle.kts
├── gradle.properties
├── settings.gradle.kts
├── .gitignore
└── README.md
```

## Tech Stack

- Kotlin
- Jetpack Compose
- Material 3
- Gradle Kotlin DSL

## Notes

- This is a starter repository structure meant for clean presentation on GitHub.
- It includes the essential Android files, package naming, theme files, manifest, and a basic Compose screen.
- You can later replace placeholder UI and add real features such as authentication, vaccination tracking, appointments, growth monitoring, and emergency contacts.

## Suggested Next Modules

- `features/auth/`
- `features/home/`
- `features/appointments/`
- `features/growth/`
- `features/vaccination/`
- `core/common/`
- `core/navigation/`
- `data/repository/`

## Push to GitHub

```bash
git init
git add .
git commit -m "Initial commit for Shishu Sneha"
git branch -M main
git remote add origin https://github.com/your-username/shishu-sneha.git
git push -u origin main
```

## Important

If Android Studio asks for missing wrapper files, you can generate them later by opening the project and syncing Gradle. For GitHub presentation, this structure is already clean and repo-ready.