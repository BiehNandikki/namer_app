# Namer App

The **Namer App** is a simple Flutter application that generates random word pairs using the `english_words` package. Users can save their favorite word pairs and manage them in a separate favorites list. The app uses `provider` for state management and `Material Design 3` for a modern UI experience.

## Features

- **Random Word Generation:** Generate random word pairs and display them in a visually appealing way.
- **Favorites:** Add or remove word pairs to/from your list of favorites.
- **Navigation:** Easily switch between the word generator and the favorites list using a responsive `NavigationRail` that adapts to screen size.

## Screens

- **Home Screen:** Displays a random word pair with options to like or generate a new pair.
- **Favorites Screen:** View and manage the list of word pairs you've added to your favorites.

## Getting Started

### Prerequisites

- [Flutter](https://flutter.dev) SDK installed on your machine.
- An IDE like [Android Studio](https://developer.android.com/studio) or [Visual Studio Code](https://code.visualstudio.com/).

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/namer_app.git
    ```
2. Navigate to the project directory:
    ```bash
    cd namer_app
    ```
3. Install dependencies:
    ```bash
    flutter pub get
    ```
4. Run the app:
    ```bash
    flutter run
    ```

## Technologies Used

- **Flutter**: The framework used to build the app.
- **Dart**: Programming language used with Flutter.
- **english_words**: A package that provides a large set of English word pairs.
- **provider**: State management solution for handling app state efficiently.

## Future Improvements

- Add persistent storage for favorites using local databases like `sqflite`.
- Enhance UI with more animations and custom themes.
- Allow users to share their favorite word pairs.

## Contributing

Feel free to open issues or submit pull requests with improvements!

## License

This project is licensed under the MIT License.
