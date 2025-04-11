Flutter Project: Splitships
This guide explains how to set up, build, and run the Flutter project in Android Studio.

Prerequisites
Before running the project, ensure the following are installed on your system:

Flutter SDK: Install Flutter   https://docs.flutter.dev/get-started/install
Android Studio: Download Android Studio https://developer.android.com/studio
Dart Plugin: Installed in Android Studio (comes with Flutter plugin).
Flutter Plugin: Installed in Android Studio.
Java Development Kit (JDK): Ensure you have JDK installed. Android Studio usually manages this for you.
Environment Variables:
Add the Flutter SDK to your PATH.
To verify the setup, run:

bash
flutter doctor

Resolve any issues reported by flutter doctor.

Steps to Run the Project
Clone the Repository
Clone the repository to your local machine using Git:

bash
Copy code
git clone [repository-url]
cd [project-directory]
Open the Project in Android Studio

Launch Android Studio.
Click on Open and select the cloned project directory.
Check and Update the pubspec.yaml File

Open the pubspec.yaml file in the project root directory.
Ensure all required dependencies are listed. If there are missing packages or updates needed:

bash
flutter pub get
Verify that all dependencies are successfully resolved. If you encounter any issues, ensure the dependency versions are correct.
Install Dependencies
After confirming the pubspec.yaml file is correct, install all dependencies using:

bash
flutter pub get
Run the App

Connect a physical Android device via USB or start an emulator.
Select the target device in Android Studio.
Run the app by clicking the green Run button or using:

bash
flutter run


Additional Notes
Supported Platforms:
This project is designed for [Android/iOS/Web] platforms. Ensure the proper environment is set up for your target platform.

Debugging:
Use Android Studio's debugger to troubleshoot issues or run:

bash
flutter logs
Flutter Channel:
Ensure you’re on the correct Flutter channel:

bash
flutter channel [stable/beta/dev]
flutter upgrade
Environment-Specific Configurations:
If the project uses environment variables, ensure you configure them in the .env file or as specified.

Known Issues:
List any known issues and troubleshooting steps here.