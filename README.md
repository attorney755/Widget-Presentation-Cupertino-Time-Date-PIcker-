# Cupertino Date & Time Picker

A Flutter application demonstrating Cupertino-style Date and Time pickers with iOS-style wheel selection and real-time updates.

## Description

A Flutter widget that provides native iOS-style date and time selection using scrollable wheels with real-time updates and AM/PM support.

## Getting Started

```bash
# Clone the repository
git clone https://github.com/attorney755/Widget-Presentation-Cupertino-Time-Date-PIcker-.git

# Navigate to project directory
cd Widget-Presentation-Cupertino-Time-Date-PIcker-

# Get dependencies
flutter pub get

# Run the app
flutter run
```

## Key Attributes

### 1. CupertinoDatePicker

The main widget that provides iOS-style wheel-based selection. It supports two modes:

- **Date Mode**: Selects day, month, and year with a configurable date range (2000–2030)
- **Time Mode**: Selects hours and minutes with AM/PM support using a 12-hour format

### 2. showCupertinoModalPopup

Displays the picker as a bottom sheet, matching iOS native behavior:

- Smooth slide-up animation from the bottom
- Modal interaction (blocks background until dismissed)
- Native iOS feel on both Android and iOS platforms

### 3. Real-Time Updates with setState()

The app updates the UI instantly as the user scrolls:

- `onDateTimeChanged` callback fires on every scroll movement
- `setState()` triggers a UI rebuild with the new value
- Selected values display immediately in the subtitle

## Screenshot

![App Screenshot](screenshots/app_screenshot.png)
