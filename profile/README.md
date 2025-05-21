# NaviGuard

## Overview
NaviGuard is an AI-powered navigation and safety assistance system designed to provide real-time weather updates, driving suggestions, accident reporting, and emergency assistance. The platform includes a mobile application (Android) and a website, offering features to enhance road safety and emergency response.

## Features
- **Real-time Weather Updates**: Provides weather data to assist in route planning.
- **Driving Suggestions**: Suggests safe driving tips based on weather conditions.
- **Navigation with Maps**: Displays real-time navigation with distance and estimated time of arrival.
- **Accident Reporting & Notifications**: Users can report accidents, which are validated by police officers. If confirmed, users earn NaviGuard coins.
- **Dashcam Recording**: Automatically records and stores video footage in Firestore with timestamps.
- **Emergency Assistance**: Provides direct calling options for police, hospitals, fire departments, and blood banks.
- **Insurance Services**: Dashcam footage can be used for insurance claims.
- **Officer Interface**: Separate dashboards for police, hospital management, fire department, and blood bank officials.
- **Community Chat & Individual Messaging**: Users and officers can communicate in dedicated chat groups and individual chats.
- **Role-Based Authentication**: Users choose their role (User or Officer) during sign-up, with officers selecting their specific department.
- **AI Assistant Chatbot**: Integrated AI chatbot providing assistance with various features.

## Sustainable Development Goals (SDGs) Covered
NaviGuard aligns with the United Nations Sustainable Development Goals (SDGs), specifically:
- **SDG 3: Good Health and Well-being** – Ensuring timely access to emergency medical services and hospitals.
- **SDG 9: Industry, Innovation, and Infrastructure** – Utilizing AI and technology to enhance road safety and emergency response.
- **SDG 11: Sustainable Cities and Communities** – Improving urban safety through accident reporting and real-time navigation assistance.

## Tech Stack
- **Frontend**: Flutter (Dart)
- **Backend**: Firebase Firestore, Firebase Authentication
- **Cloud Storage**: Firebase Storage, Cloudinary
- **Hosting**: GitHub Pages (for website deployment), Render(for Models deployment)
- **AI & ML**: AI-powered chatbot(Gemini 2.0 Flash Experimental)
- **Maps & Navigation**: Google Maps API, OSRM API(Routing)
- **Authentication**: Google OAuth
- **Weather Data**: Open Weather Map API

## GitHub Organization & Repositories

NaviGuard is maintained under the GitHub organization **SafeGuard**, which hosts multiple repositories related to the project:

- **[NaviGuard Application](https://github.com/Safe-Gaurd/NaviGuard.git)** – The main mobile application built with Flutter.
- **[NaviGuard QR App](https://github.com/Safe-Gaurd/NaviGuardQR.git)** – A QR-based application for quick access and authentication.
- **[NaviGuard ML Model](https://github.com/Safe-Gaurd/NaviGaurd_ML_Model.git)** – Machine learning models used for accident detection and predictions.
- **[AI Assistance Chatbot](https://github.com/Safe-Gaurd/AI_Assisstance_ChatBot.git)** – AI chatbot providing assistance within the app.


## Installation & Setup
### Prerequisites
- Flutter SDK installed
- Firebase setup for authentication, Firestore, and storage
- Google Maps API key

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/Safe-Gaurd/NaviGuard.git
   ```
2. Navigate to the project directory:
   ```sh
   cd SafeGuard
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```
4. Configure Firebase:
   - Add your `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) to the appropriate directories.
5. Run the app:
   ```sh
   flutter run
   ```

## Deployment
- **Website**: Hosted via GitHub Pages(All features are not supported by Web)
- **Android APK**: Built and distributed for Android users

## Contribution Guidelines
1. Fork the repository.
2. Create a new branch (`feature-branch-name`).
3. Commit your changes.
4. Push to your branch and create a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any queries, feel free to reach out at [lokeshsuryaprakashk@gmail.com].

