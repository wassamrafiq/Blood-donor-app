# Blood-donor-app

This is a mobile application built using **Flutter** for facilitating blood donation. It connects potential blood donors with recipients, helping to streamline the donation process through user-friendly features and real-time data integration via Firebase. This project includes source code in the lib/ directory, configuration in pubspec.yaml, and image assets.

## Features

- **User Authentication** using Firebase
- **Donor Profile Management**
- **Blood Donation Activity Tracking**
- **Firebase Firestore Integration** for data storage
- **Modern UI/UX** with image assets
- **Navigation Between Screens** for login, registration, and dashboard

## Technologies Used

- **Flutter** (Dart)
- **Firebase Authentication**
- **Cloud Firestore**
- **Provider / Stateful Widgets**
- **Google Fonts & Material Icons**

## Project Structure



lib/
├── bloodDonorActivity.dart       # Blood donation tracking
├── donorprofile.dart             # Donor profile UI and logic
├── firebase\_options.dart         # Firebase configuration
├── firestorehelper.dart          # Firestore integration logic
├── homepage.dart                 # Main dashboard
├── login.dart                    # Login screen
├── register.dart                 # Registration screen
├── splash.dart                   # Splash screen UI
images/
├── blood\_2.png                   # Image assets
├── blood\_3.png
pubspec.yaml                      # Flutter dependencies and metadata

`
### Prerequisites

- Flutter SDK installed
- Android Studio / VS Code with Flutter plugin
- Firebase project set up

### Installation

1. Clone the repository or download the ZIP:
   bash
   git clone <your-repo-url>
   cd <project-folder>
`
2. Install dependencies:

   bash
   flutter pub get
   
3. Configure Firebase:

   * Replace `firebase_options.dart` with your Firebase configuration or update the existing one using FlutterFire CLI.

4. Run the app:

   bash
   flutter run
   

## Contributors

* 0258-BSCS-21
* 0288-BSCS-21

## License

This project is for educational purposes and may be reused with attribution.
