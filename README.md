# Contrast Shower Companion

## Introduction
Contrast Shower Companion is a Flutter application designed to assist users in performing contrast showers. The app allows users to set the starting phase (hot or cold), the number of repetitions, and the duration for each phase. It also tracks shower sessions, allowing users to view their session history and rate their experiences.

## Features
- **Set Starting Phase**: Choose whether to start the session with hot or cold water.
- **Repetitions and Duration**: Specify the number of repetitions and the duration for each phase.
- **Session Tracking**: Monitor the current phase and time remaining during a session.
- **Session History**: View the history of all completed shower sessions.
- **Session Rating**: Rate each session after completion.
- **Pause and Resume**: Pause and resume the shower timer as needed.
- **Cancel Session**: Cancel the current session and return to the main menu.

## Usage

### Home Screen
1. **Starting Phase**: Select either 'Hot' or 'Cold' to set the starting phase.
2. **Repetitions**: Enter the number of repetitions.
3. **Duration**: Enter the duration for each phase in seconds.
4. **Start Shower**: Begin the shower session with the specified settings.
5. **Session History**: View the history of past sessions.

### Session Screen
- **Current Phase**: Displays whether the current phase is 'Hot' or 'Cold'.
- **Time Remaining**: Shows the remaining time for the current phase.
- **Pause/Resume**: Pause or resume the timer.
- **Pause and Exit**: Cancel the current session and return to the main menu.

### Session History Screen
- View a list of all past sessions, including the start phase, number of repetitions, total duration, and timestamp.

## Code Structure

- **main.dart**: The main entry point of the application.
- **home_screen.dart**: Contains the UI and logic for the home screen where users set up their shower sessions.
- **session_screen.dart**: Manages the UI and logic for tracking the current shower session.
- **session_history_screen.dart**: Displays the history of all completed sessions.
- **shower_timer_provider.dart**: Contains the business logic for managing the shower timer and current session state.
- **shower_session_provider.dart**: Manages the session history and session rating logic.
- **models/session.dart**: Defines the data model for a shower session.
- **utils/constants.dart**: Contains constant values used throughout the application.
- **widgets/custom_button.dart**: A reusable custom button widget used in various screens.


