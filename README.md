# Icarus Joining Process App

Welcome to the Icarus Joining Process App repository! This Android application facilitates the joining process for Icarus, providing functionalities for user login, sign up, and dashboard display. This README provides an overview of the project structure, setup instructions, testing automation using Appium, and the development workflow to achieve the tasks outlined in the quest.

## Project Structure

The project is structured as follows:

- **`app`**: Contains the main source code for the Android application.
  - **`src`**: Source directory for Java and resource files.
    - **`main`**: Main application code.
      - **`java/com/example/icarusjoiningprocess`**: Java code for activities and logic.
        - `LoginActivity.java`: Manages user login functionality.
        - `SignUpActivity.java`: Handles user registration logic.
        - `DashboardActivity.java`: Displays user data in the dashboard.
      - **`res`**: Resource files including layouts (XML) and other resources.
        - **`layout`**: XML layout files for different activities.
          - `activity_login.xml`: Layout for the login screen.
          - `activity_signup.xml`: Layout for the sign-up screen.
          - `activity_dashboard.xml`: Layout for the dashboard screen.
- **`AndroidManifest.xml`**: Manifest file defining application components and permissions.

## Setup Instructions

Follow these steps to set up the development environment and run the application:

1. **Install Android Studio**:
   - Download and install the latest version of Android Studio from the [official website](https://developer.android.com/studio).

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/your/repository.git
   
## Open in Android Studio

1. **Launch Android Studio**:
   - Launch Android Studio.
   - Select "Open an existing Android Studio project" and choose the cloned repository.

2. **Set Up Emulator or Device**:
   - Set up a physical Android device or configure an emulator within Android Studio for testing.

3. **Build and Run**:
   - Build the project and run the application on the configured device/emulator.

## Testing Automation with Appium

To automate testing of the Icarus Joining Process App using Appium, follow these steps:

### Start Appium Server

1. **Install and Start Appium Server**:
   - Install and start the Appium server.

### Set Up Appium Test Environment

1. **Install Necessary Dependencies**:
   - Install necessary dependencies like the Appium Java client.
   - Ensure the Android SDK tools are available.

### Execute Test Script 

