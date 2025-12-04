# Path Highlighter

An Android application designed to highlight streets on a virtual map as you travel, making navigation easier in India.

![App Screenshot](Screenshot.jpg)

## 📱 Features

- **Real-time GPS Tracking** - Automatically tracks your location
- **Path Highlighting** - Draws colored lines on streets as you travel
- **Distance Calculation** - Shows total distance traveled
- **Start/Stop Controls** - Easy buttons to control tracking
- **Clear History** - Remove all highlighted paths
- **Built for India** - Designed for Indian roads and navigation

## 🛠️ Technologies Used

- **Language:** Java
- **Platform:** Android (API 21+)
- **IDE:** Android Studio
- **Map Services:** Google Maps API
- **Location Services:** Google Play Services Location

## 📥 Installation

### Download APK
1. Go to [Releases](../../releases)
2. Download the latest APK file
3. Install on your Android device
4. Grant location permissions when prompted

### Build from Source
1. Clone this repository
2. Open in Android Studio
3. Add your Google Maps API key in `AndroidManifest.xml`
4. Build and run

## 🔑 Setup (For Developers)

### Prerequisites
- Android Studio
- Java JDK 8 or higher
- Google Maps API Key

### Get Google Maps API Key
1. Go to [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project
3. Enable "Maps SDK for Android"
4. Create credentials → API Key
5. Add the key to `AndroidManifest.xml`:
```xml
<meta-data
    android:name="com.google.android.geo.API_KEY"
    android:value="AIzaSyBQHwbxdlEWztCdMRsmlzgTY_7KpMd-JlQ" />
```

### Build Steps
1. Clone the repository
2. Open in Android Studio
3. Sync Gradle files
4. Connect Android device or start emulator
5. Click Run

## 📸 Screenshots

(Screenshot.jpg)

## 🚀 How to Use

1. Open the app
2. Grant location permission
3. Tap **Start** button
4. Move around (walk, drive, etc.)
5. Watch as purple lines appear on roads you've traveled
6. Tap **Stop** to pause tracking
7. Tap **Clear** to remove all paths

## 📂 Project Structure
```
Path-Highlighter/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/pathhighlighter/app/
│   │   │   │   └── MainActivity.java
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   └── activity_main.xml
│   │   │   │   └── values/
│   │   │   └── AndroidManifest.xml
│   │   └── build.gradle
│   └── build.gradle
├── gradle/
└── build.gradle
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License.

## 👤 Lavanya Badyal

**Lavanya Badyal**

- GitHub: [@lavanyabadyal-blip](https://github.com/lavanyabadyal-blip)

## 🙏 Acknowledgments

- Google Maps Platform for mapping services
- Android Developer community
- Built for making navigation easier in India

## 📧 Contact

For any queries, please reach out at: lavanyabadyal@gmail.com

---



Initial release of Path Highlighter Android app

Features:
- GPS tracking
- Path highlighting on map
- Distance calculation
- Start/Stop/Clear controls






```
https://github.com/lavanyabadyal-blip/Path___Highlighter
