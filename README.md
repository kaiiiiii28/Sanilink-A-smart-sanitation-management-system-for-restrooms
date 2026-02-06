# Sanilink-A-smart-sanitation-management-system-for-restrooms

# Description
Sanilink is a smart sanitation management system for restrooms used for monitoring with IoT integration. This is designed to improve restroom cleanliness and maintenance efficiency in public and private facilities. Many establishments rely on fixed manual cleaning schedules, which often lead to under-cleaning during peak usage and over-cleaning even though it is not yet needed. The application uses IoT sensors to monitor restrooms usage, air quality, humidity, and trash/suppply level. When the sensors sensed that the restroom has bad odor, no supply, full trash, and too much usage, the app will sends notification alert to the cleaning staff. Sanilink addresses this problems or issues by providing a real-time, and data-driven monitoring with integration of IoT application. 

# Technologies Used
- Flutter
- Dart
- IoT sensors (module sensors if in arduino)
- Firebase Cloud Computing

# Features
- User authentication for admin, managers, and cleaning personnel/staff
- Real-time restroom status monitoring
- Device control for admin
- Automated alerts for trash/supply levels, poor air quality, restroom needs cleaning, and high humidity.
- Analytics reports
- Performance reports
- Personnel tracking
- Status using LEDs (in arduino only)

# Installation Instructions
- Requirements:
  Android Studio, IoT module sensors, Arduino Uno
- Steps in Installation:
  Download the project files. After downloading the files, open the Android Studio. Then, Connect the app to Firebase. Lastly, Run the app on emulator.

# Setup
- First, make sure the sensors are connected to the Arduino Uno to collect data on restroom usage, air quality, humidity, trash level, and supply level. The Arduino sends the sensor data to the Firebase cloud through Wi-Fi. Firebase stores the data and sends alerts to the mobile application. The mobile app displays real-time restroom status and notifications to users. And finally, the system is tested by simulating usage, odor, humidity, and supply conditions to ensure proper operations.

# Contributors
- rcpinca.it@tip.edu.ph
