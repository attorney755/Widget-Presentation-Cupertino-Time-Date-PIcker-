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

This is the main widget that provides iOS-style wheel-based selection. It supports two modes:

- **Date Mode**: THis is the mode that is used to select day, month, and year and I set the minimum year to 2000 and the maximu to 2030
- **Time Mode**: Selects hours and minutes with AM/PM support where I used a 12-hour format

### 2. showCupertinoModalPopup

The attribute is the showCupertinoModalPopup which Displays the picker as a bottom sheet, matching iOS native behavior:

- Smooth slide-up animation from the bottom
- Modal interaction (blocks background until dismissed)
- Native iOS feel on both Android and iOS platforms

### 3. Real-Time Updates with setState()

Another attribute is a Real-Time Updates with setState() which updates the UI instantly as the user scrolls where I used: 

- `onDateTimeChanged` callback fires on every scroll movement
- `setState()` triggers a UI rebuild with the new value
- Selected values display immediately in the subtitle

## Screenshot
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6c8ae3ba-6307-44d4-91cb-92eb4807a21b" />

