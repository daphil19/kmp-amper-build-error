# Kotlin Multiplatform amper build error

This repo is an example of the template amper project found on
the [KMP Wizard](https://kmp.jetbrains.com/#templateGallery).

The only modifications to it should include:

1. adding a custom repository to all projects
2. adding an implementaion dependency to `shared`

The error is a build-time error in `iosApp` that occurs via `./gradlew build`. Launching the app via fleet works as
expected.