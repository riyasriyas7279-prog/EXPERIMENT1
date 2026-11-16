Objective
To install and configure Android Studio, understand the Android project structure, and develop a basic Android application that displays a "Hello World" message.

Software Requirements
Android Studio (Latest Stable Version)
Java Development Kit (JDK 21 - bundled with Android Studio)
Android SDK
Android Emulator or Physical Android Device
Windows 10/11
Android Studio Configuration
IDE
Android Studio (Latest Stable Release)
Programming Language
Kotlin
Build System
Gradle (Kotlin DSL)
Minimum SDK
API Level 24 (Android 7.0 Nougat)
Target SDK
API Level 36
Compile SDK
API Level 36
Build Tools
Android SDK Build Tools (Latest Installed)
Gradle Version
Latest compatible version provided by Android Studio
Project Structure
MyApplication
│
├── app
│   ├── manifests
│   ├── java
│   ├── res
│   │   ├── drawable
│   │   ├── layout
│   │   ├── mipmap
│   │   └── values
│   └── build.gradle.kts
│
├── Gradle Scripts
└── settings.gradle.kts
Main Components
MainActivity.kt
This is the entry point of the application. It initializes the activity and displays the user interface.

activity_main.xml
Defines the graphical user interface (UI) of the application.

AndroidManifest.xml
Contains application configuration such as application name, icon, permissions, and launcher activity.

Working
Android Studio creates a new Android project.
The application starts from MainActivity.kt.
The layout file is loaded.
A TextView displays the message.
The application runs successfully on an emulator or Android device.
Hello World Output
The application displays the following text on the screen:

Hello Santhosh Kumar S!
Features
Basic Android application
Uses Kotlin programming language
Material Design theme
Simple TextView
Runs on Android 7.0 and above
Learning Outcomes
After completing this experiment, the following concepts were learned:

Installation of Android Studio
Android SDK configuration
Creating Android projects
Understanding Android project structure
Activity lifecycle basics
XML layout design
Running applications on emulator/device
Screenshots
Screenshot 1 – Android Studio Project
Android Studio Project

Screenshot 2 – Application Output
Application Output

Conclusion
The experiment was successfully completed by configuring Android Studio, understanding the Android project structure, and developing a simple Hello World application using Kotlin.# EXPERIMENT1
