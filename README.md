# Expenses Tracker

Expenses Tracker is an Android application designed to help users manage and track their expenses efficiently.

## Features

- Add, edit, and delete expense records
- View expense records in a list
- Categorize expenses
- View summary of expenses

## Getting Started

### Prerequisites

- Android Studio
- Java Development Kit (JDK) 8 or higher
- Android SDK

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Hari2048/FinChamp
    ```
2. Open the project in Android Studio.
3. Sync the project with Gradle files.
4. Build and run the project on an emulator or a physical device.

### Running Tests

To run the instrumented tests on an Android device, use the following command:

```sh
./gradlew connectedAndroidTest
```

### Project Structure
```
FinChamp/
├── .gitignore
├── .idea/
├── app/
│   ├── [build.gradle](http://_vscodecontentref_/0)
│   ├── [proguard-rules.pro](http://_vscodecontentref_/1)
│   └── src/
│       ├── androidTest/
│       │   └── java/
│       │       └── com/
│       │           └── example/
│       │               └── expensestracker/
│       │                   └── [ExampleInstrumentedTest.kt](http://_vscodecontentref_/2)
│       └── main/
│           ├── [AndroidManifest.xml](http://_vscodecontentref_/3)
│           ├── java/
│           └── res/
├── [build.gradle](http://_vscodecontentref_/4)
├── gradle/
├── [gradle.properties](http://_vscodecontentref_/5)
├── gradlew
├── [gradlew.bat](http://_vscodecontentref_/6)
├── README.md
└── settings.gradle
```


### Configuration
The project uses the following configurations:
```
Gradle Version: 7.0
Kotlin Version: 1.5.21
Compile SDK Version: 33
Min SDK Version: 21
Target SDK Version: 33
```

### Dependencies
The project includes the following dependencies:

`AndroidX Libraries`
`Kotlin Standard Library`
`AndroidX Test Libraries`\
For a complete list of dependencies, refer to the build.gradle file.


[Watch the video demo here](https://drive.google.com/file/d/1xr9Ld6r3lZAIeQSBm7zUEOGoGzf8Zh53/view?usp=drive_link)
