# BMICalculator

https://github.com/user-attachments/assets/87389509-17e3-4ae4-9d0a-fdd599c65ac2

A Flutter-based Body Mass Index (BMI) calculator app that helps users calculate their BMI and assess their health based on the result. This app features a modern dark-themed design and a customizable UI.

## Features

- **Dark Theme**: Customized dark theme for a visually appealing and modern look.
- **Responsive UI**: Designed to work seamlessly on both iOS and Android devices.
- **Easy Navigation**: Navigate between screens using simple gestures and buttons.

## Screens

- **Input Page**: The main screen where users can input their weight, height, and other parameters.
- **Result Page**: Displays the calculated BMI and health assessment.

## Installation

To run this project locally, follow these steps:

### Clone the repository:
```bash
git clone https://github.com/your-username/bmi-calculator.git
cd bmi-calculator
```

### Install dependencies:
```bash
flutter pub get
```

### Run the app:
```bash
flutter run
```

## File Structure

```
BMICalculator/
├── lib/
│   ├── constants.dart        # Contains app-wide constants like colors and styles
│   ├── main.dart            # Entry point of the application
│   ├── screens/
│   │   ├── input_page.dart  # Screen for user inputs
│   │   ├── result_page.dart # Screen for displaying results
│   └── widgets/             # Reusable widget components
└── pubspec.yaml             # Project configuration file
```

## Customization

### Theme Customization

**AppBar Theme:**
- **Background Color**: `Color(0xFF0A0E21)`
- **Title Text Style**: White text with font size `20.0`

**Scaffold Background**: `Color(0xFF0A0E21)`

**Floating Action Button:**
- **Background Color**: `Colors.cyanAccent`
- **Foreground Color**: `Colors.black`
- **Shape**: Rounded with `40.0` corner radius

## Adding New Features

1. Add new screens under `lib/screens`.
2. Create reusable widgets under `lib/widgets`.
3. Update navigation in `lib/main.dart`.

## Dependencies

This app uses the following Flutter dependencies:

- `flutter/material.dart`: For creating UI components.

## Contribution

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature/bugfix.
3. Submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author

Created by Kevin Narain. Feel free to reach out for feedback or collaboration!
