Google Codelabs - https://codelabs.developers.google.com/codelabs/flutter-codelab-first?hl=en#0

# Namer App

The **Namer App** is a simple Flutter application that generates random word pairs using the `english_words` package. Users can save their favorite word pairs and manage them in a separate favorites list. The app uses `provider` for state management and `Material Design 3` for a modern UI experience.

## Features

- **Random Word Generation:** Generate random word pairs and display them in a visually appealing way.
- **Favorites:** Add or remove word pairs to/from your list of favorites.
- **Navigation:** Easily switch between the word generator and the favorites list using a responsive `NavigationRail` that adapts to screen size.

## Screens

- **Home Screen:** Displays a random word pair with options to like or generate a new pair.
![Desktop 2024-10-18 03-38-48-144](https://github.com/user-attachments/assets/18b926bc-eb38-40c7-acad-55ab300d1b79)

  
- **Favorites Screen:** View and manage the list of word pairs you've added to your favorites.
![Desktop 2024-10-18 03-38-51-871](https://github.com/user-attachments/assets/d7ba8a60-8ea8-4882-92bb-201c1e74d18a)


## Getting Started

### Prerequisites

- Install the [Flutter](https://flutter.dev) SDK on your machine.
- For setting up the development environment, use [Android Studio](https://developer.android.com/studio) for Android device emulation and project management, and [Visual Studio Code](https://code.visualstudio.com/ ) as a code editor for writing and debugging your Flutter code.
### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/muhammedahmetsekerci/namer_app.git
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

## License

This project is licensed under the MIT License.
