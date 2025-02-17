# Shower Timer

A simple and intuitive Flutter app to track and manage shower time efficiently. The app utilizes Hive for local storage and Riverpod for state management.

## Demo

[Watch the demo](https://drive.google.com/file/d/1NecxDG4YnjZVlKMaq9_XvUnYaKwQvQHx/view?usp=drive_link)

## Features

- Start, pause, and reset the shower timer
- Save and retrieve past shower durations using Hive
- Efficient state management with Riverpod
- Minimal and user-friendly UI
- Track hot and cold phase durations
- Store user preferences for session settings

## Technologies Used

- **Flutter** (Dart)
- **Hive** for local database storage
- **Riverpod** for state management

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/lelonov23/timer-flutter.git
   cd timer-flutter
   ```

2. Install dependencies:
   ```sh
   flutter pub get
   ```

3. Run the app:
   ```sh
   flutter run
   ```

## Usage

1. Tap the start button to begin the timer.
2. Pause the timer at any point.
3. Reset to restart the session.
4. View past recorded shower durations stored in Hive.
5. Customize session preferences (hot/cold phase duration, session length).

## Project Structure

```
lib/
├── main.dart            # Entry point of the app
├── models/
│   ├── shower_session.dart  # Data model for storing shower durations
│   ├── shower_session.g.dart  # Generated Hive adapter
├── providers/
│   ├── session_provider.dart # Riverpod provider for session logic
├── screens/
│   ├── home_screen.dart    # Home UI screen
│   ├── active_session.dart # Active session tracking screen
│   ├── session_overview.dart # Session summary screen
│   ├── session_preferences.dart # User preferences settings
│   ├── session_summary.dart # Review and rate past sessions
├── services/
│   ├── storage_service.dart # Hive storage service
```

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

