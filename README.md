# NousAppathon

NousAppathon is a creative Android application that blends color exploration with photography. Built using modern Android development practices, it features a playful interface for discovering colors and capturing moments inspired by them.

## Features

- **Color Palette Generator**: Explore a variety of colors through an interactive Lottie-animated wheel. Use the "Randomize" feature to find your next inspiration with haptic feedback.
- **Custom Camera**: A built-in camera experience where the shutter button adapts its color to match your selected palette.
- **Integrated Gallery**: Easily access and view the photos you've captured within the app.
- **Modern UI/UX**: Built entirely with **Jetpack Compose**, featuring smooth transitions, custom fonts (Caveat), and immersive Lottie animations.
- **Haptic Experience**: Integrated vibration and haptic feedback for a tactile feel during interaction.

## Tech Stack

- **Language**: Kotlin
- **UI Framework**: Jetpack Compose
- **Camera Engine**: CameraX
- **Animations**: Lottie for Android
- **Architecture**: Single Activity with Compose-based navigation

## Getting Started

### Prerequisites

- Android Studio Ladybug or newer.
- Android SDK 24+ (Android 7.0 or higher).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/[your-username]/NousAppathon.git
   ```
2. Open the project in Android Studio.
3. Sync the project with Gradle files.
4. Run the app on an emulator or a physical device.

## Permissions

The app requires the following permissions to function correctly:
- `CAMERA`: For taking photos.
- `WRITE_EXTERNAL_STORAGE` (API < 29): For saving photos to the gallery.

## Project Structure

- `MainActivity.kt`: The main entry point managing the state and navigation.
- `ui/`: Contains Compose screens (`CameraScreen`, `GalleryScreen`) and components (`CameraPreview`).
- `ui/theme/`: Defines the app's design system (Colors, Typography, Theme).
- `res/raw/`: Stores Lottie animation files for various color states.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
