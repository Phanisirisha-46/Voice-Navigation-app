# 📱 Voice-Navigation-app
A voice based navigation app
**Empowering the Visually Impaired with Seamless Navigation**  

---

## 📚 **Project Overview**  
**Voice-Navigation** is an intuitive and accessible Android application designed to assist visually impaired individuals by providing seamless navigation using voice commands and audio guidance. The app allows users to:  

- Input source and destination using voice commands.  
- Select the starting point by tapping anywhere on the screen.  
- Receive real-time step-by-step audio navigation cues for safe mobility.  

---

## 🎯 **Key Features**  

✅ **Voice-to-Text Input**  
- Allows users to input source and destination through voice commands.  
- Utilizes `SpeechRecognizer` API for accurate speech recognition.  

✅ **Tap-to-Select Start Point**  
- Users can manually select their starting point by tapping anywhere on the screen.  
- Simplifies navigation without relying on GPS.  

✅ **Audio Navigation Cues**  
- Provides clear and concise step-by-step voice instructions.  
- Guides users safely to their destination using Google Maps.  

---

## 🛠️ **Technologies Used**  

- **Android Studio** – Development environment for building the app.  
- **Java** – Primary programming language for application logic.  
- **XML** – For designing the user interface.  
- **SpeechRecognizer API** – Converts voice input to text.  
- **Google Maps API** – Provides real-time navigation and route guidance.  

---

## 📂 **Project Structure**  

```
/VoiceNavigationApp
├── /app
│   ├── /src
│   │   ├── /main
│   │   │   ├── /java/com/example/voicenavigationapp
│   │   │   │   ├── MainActivity.java
│   │   │   └── /res
│   │   │       ├── /layout
│   │   │       │   └── activity_main.xml
│   │   │       └── /mipmap
│   │   │           └── App icons and launcher images
│   │   └── AndroidManifest.xml
└── /gradle
    └── Build configuration files
```

---

## 🚀 **Installation and Setup**  

### **Step 1: Clone the Repository**  
```bash
git clone https://github.com/Phanisirisha-46/Voice-Navigation-app.git
```

### **Step 2: Open in Android Studio**  
- Open **Android Studio**.  
- Select **Open an Existing Project** and choose the `VoiceNavigationApp` folder.  

### **Step 3: Configure API Keys**  
- Get your API key from [Google Cloud Console](https://console.cloud.google.com/).  
- Add the API key in the `AndroidManifest.xml` file.  

```xml
<meta-data
    android:name="com.google.android.geo.API_KEY"
    android:value="YOUR_API_KEY_HERE" />
```

### **Step 4: Build and Run**  
- Connect your Android device or use an emulator.  
- Click **Run** to install and launch the application.  

---

## 🎙️ **How to Use**  

1. **Launch the App:** Open the app and press the **"Tap Anywhere to Start"** button.  
2. **Voice Input:** Speak the destination or starting point.  
3. **Manual Start Point:** Tap anywhere on the screen to choose your starting point.  
4. **Audio Cues:** Follow the step-by-step audio instructions to reach your destination safely.  

---
##  **Output Screenshots**  

<img width="210" alt="image" src="https://github.com/user-attachments/assets/b7bdf2c6-3c78-483e-9f68-1bba5b2a6e83" />

<img width="212" alt="image" src="https://github.com/user-attachments/assets/09b40f40-1188-428c-98a6-e4af31be9995" />

<img width="208" alt="image" src="https://github.com/user-attachments/assets/17293471-ae6e-4203-b88b-e73d37ac9e54" />

<img width="203" alt="image" src="https://github.com/user-attachments/assets/ba343aa2-80e0-4aef-9282-9b223309821d" />

<img width="206" alt="image" src="https://github.com/user-attachments/assets/d6aa276a-ee73-43e1-8551-6af890c3ba57" />

<img width="212" alt="image" src="https://github.com/user-attachments/assets/d8a13b47-04b0-4108-8055-b56a38e45ef5" />
<img width="208" alt="image" src="https://github.com/user-attachments/assets/d9c7bf0a-0800-4c0c-9af6-89a592e8f4fb" />



---
## 🔒 **Permissions Required**  

- **Microphone Access:** To capture and process voice input.  
- **Internet Access:** To fetch route data using Google Maps API.  


---

✅ **Voice-Navigation** is committed to enhancing mobility and empowering visually impaired individuals with independence and confidence🌟

---
