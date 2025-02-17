# Multi-Form Flutter Application

## Overview
This project is a Flutter-based multi-form application that validates user input fields. The application consists of at least two screens with input fields for Name, Address, Email, and Phone Number. The goal is to demonstrate input validation using Flutter's form validation mechanisms.

## Features
- Two screens for user input.
- Input validation for at least three fields.
- Validation scripts for Name, Email, and Phone Number.
- Error messages displayed when validation fails.
- Well-structured folder organization.
- Documented code with explanations.
- Buttons for user interaction.

## Folder Structure
```
project_root/
│── lib/
│   │── main.dart             # Entry point of the application
│   │── screens/
│   │   │── form_input.dart   # Main input form screen
│   │   │── confirmation.dart # Second screen to show submitted data
│   │── utils/
│   │   │── validation.dart   # Validation functions for input fields
│── pubspec.yaml              # Flutter dependencies
```

## Installation & Setup
1. **Clone the Repository:**
   ```sh
   git clone <your-repo-url>
   cd <project-folder>
   ```
2. **Install Dependencies:**
   ```sh
   flutter pub get
   ```
3. **Run the Application:**
   ```sh
   flutter run
   ```

## Input Validation
- **Name Validation:** Ensures the field is not empty.
- **Email Validation:** Checks if the input matches a valid email format.
- **Phone Number Validation:** Ensures the number is of valid length and format.

## Usage
1. Fill in the required fields on the first screen.
2. If the inputs are valid, proceed to the next screen.
3. If validation fails, error messages are displayed.
4. Submit the form to see a confirmation screen.

## Submission Requirements
- A **PDF document** containing:
  - Your name.
  - A link to the **video demo** of the application.
  - A link to your **GitHub repository** containing the project code.

## Notes
- The user interface is simple but functional.
- Only required components are implemented, as per the assignment guidelines.
- The application follows best practices in structuring and validation.

## Author
[Christophe Gakwaya]
