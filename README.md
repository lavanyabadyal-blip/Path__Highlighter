# Path Highlighter

An Android application designed to highlight streets on a virtual map as you travel, making navigation easier in India.

![App Screenshot](screenshot.png)

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
    android:value="YOUR_API_KEY_HERE" />
```

### Build Steps
1. Clone the repository
2. Open in Android Studio
3. Sync Gradle files
4. Connect Android device or start emulator
5. Click Run

## 📸 Screenshots

(Add screenshots of your app here)

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

## 👤 Author

**Lavanya Badyal**

- GitHub: [@YourGitHubUsername](https://github.com/YourGitHubUsername)

## 🙏 Acknowledgments

- Google Maps Platform for mapping services
- Android Developer community
- Built for making navigation easier in India

## 📧 Contact

For any queries, please reach out at: your.email@example.com

---

⭐ Star this repo if you find it helpful!
```

5. Scroll down
6. Click **"Commit changes"**
7. Click **"Commit changes"** again in the popup

---

## **STEP 6: ADD SCREENSHOTS (OPTIONAL)**

### Action 1: Take Screenshots
1. Run your app on phone or emulator
2. Take screenshots (press Volume Down + Power on phone)
3. Save screenshots to computer

### Action 2: Upload Screenshots
1. On GitHub repository page
2. Click **"Add file"** → **"Upload files"**
3. Drag your screenshot images
4. Type commit message: `Add app screenshots`
5. Click **"Commit changes"**

### Action 3: Update README with Images
1. Click on `README.md`
2. Click pencil icon to edit
3. Find the line: `![App Screenshot](screenshot.png)`
4. Replace `screenshot.png` with your actual image filename
5. Commit changes

---

## **STEP 7: CREATE A RELEASE (FOR APK DOWNLOAD)**

### Action 1: Build APK First
1. In Android Studio, click **Build** menu
2. Click **Build Bundle(s) / APK(s)** → **Build APK(s)**
3. Wait for build to complete
4. Click **"locate"** in notification
5. Copy `app-debug.apk` file to Desktop

### Action 2: Create Release on GitHub
1. On your GitHub repository page
2. On the right side, click **"Releases"**
3. Click **"Create a new release"**
4. **Choose a tag:** Type `v1.0` and press Enter (creates new tag)
5. **Release title:** Type `Path Highlighter v1.0 - Initial Release`
6. **Description:** Type:
```
Initial release of Path Highlighter Android app

Features:
- GPS tracking
- Path highlighting on map
- Distance calculation
- Start/Stop/Clear controls

Installation:
Download the APK file below and install on your Android device.
```
7. **Attach files:** Drag your `app-debug.apk` file here
8. Click **"Publish release"**

Now anyone can download your APK! ✅

---

## **STEP 8: SHARE YOUR PROJECT**

Your GitHub repository URL is:
```
https://github.com/YourUsername/Path-Highlighter
```

Share this link to:
- Show your project to others
- Let people download the APK
- Allow developers to see your code
- Add to your resume/portfolio

---

## **UPDATING YOUR PROJECT LATER**

When you make changes to your code:

### Simple Update Method:
1. Go to your repository on GitHub
2. Navigate to the file you want to update
3. Click the **pencil icon** (Edit)
4. Make your changes
5. Click **"Commit changes"**

### Upload New Files:
1. Click **"Add file"** → **"Upload files"**
2. Drag updated files
3. Commit changes

---

## **COMPLETE CHECKLIST**

- [ ] GitHub account created
- [ ] Repository created with name "Path-Highlighter"
- [ ] Android gitignore added
- [ ] README file added
- [ ] App folder uploaded
- [ ] Gradle folder uploaded
- [ ] Build files uploaded
- [ ] README edited with project details
- [ ] Screenshots uploaded (optional)
- [ ] Release created with APK (optional)
- [ ] Repository shared

---

## **YOUR PROJECT IS NOW ON GITHUB!** ✅

**Repository URL:**
```
https://github.com/lavanyabadyal-blip/Path-Highlighter
