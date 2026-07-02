# Project Structure

## Android App Files

```
ff-max-overlay/
├── app/
│   └── src/
│       ├── main/
│       │   ├── AndroidManifest.xml          # App configuration
│       │   ├── java/com/ffmax/overlay/
│       │   │   ├── MainActivity.java        # Main screen
│       │   │   └── OverlayService.java      # Floating overlay
│       │   └── res/
│       │       ├── layout/
│       │       │   └── activity_main.xml    # Main UI layout
│       │       └── values/
│       │           ├── strings.xml          # String resources
│       │           └── styles.xml           # App styles
│       └── build.gradle                     # App build config
├── build.gradle                              # Root build config
├── settings.gradle                           # Gradle settings
└── README.md                                 # Documentation
```

## Key Components

### MainActivity.java
- Start/Stop overlay buttons
- Request permissions
- Handle permission responses

### OverlayService.java
- Creates floating overlay
- Manages aimbot toggle
- Sensitivity slider control
- Draggable menu functionality

### Layout Files
- `activity_main.xml` - Main screen UI
- `styles.xml` - Dark theme styling
- `strings.xml` - App strings and labels

## Building

1. Open in Android Studio
2. Gradle will auto-download dependencies
3. Click "Run" to build and install
4. APK generated in `app/build/outputs/apk/`
