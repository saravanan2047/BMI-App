### BMI Calculator Android Application

## Overview
The BMI Calculator is an Android application designed to help users calculate their Body Mass Index (BMI) and categorize their health status based on the calculated BMI. The app features a clean and intuitive interface, guiding users through the process of entering their height and weight, and displaying their BMI along with a health categorization.

## Features
- **Splash Screen**: A welcoming splash screen that appears when the app is launched.
- **BMI Calculation**: Users can input their height and weight to calculate their BMI.
- **Health Categorization**: The app categorizes BMI into different health categories such as underweight, healthy, overweight, and obese.
- **Fragments**: Different fragments are used to display specific information and results, making navigation smooth and organized.

## Design Patterns and Concepts
This application employs several design patterns and architectural concepts to ensure maintainability, scalability, and a clean codebase.

### 1. **Model-View-ViewModel (MVVM)**
The app uses the MVVM architecture to separate the UI logic from the business logic, enhancing testability and separation of concerns.
- **Model**: Represents the data layer, responsible for handling data operations.
- **View**: The UI layer, which includes activities and fragments displaying data to the user.
- **ViewModel**: Acts as a bridge between the Model and View, holding UI-related data in a lifecycle-conscious way.

### 2. **Fragments**
The app is divided into multiple fragments, each representing a different screen or part of the UI.
- **SplashScreenFragment**: Displays the splash screen when the app is launched.
- **CalculateFragment**: Allows users to input their height and weight and calculate their BMI.
- **HealthyFragment**: Displays information for users who have a healthy BMI.
- **LeanFragment**: Displays information for users who are underweight.
- **OverWeightFragment**: Displays information for users who are overweight.
- **ObeseFragment**: Displays information for users who are obese.

### 3. **Navigation Component**
The app uses Android's Navigation Component to handle navigation between fragments, ensuring a seamless user experience.

### 4. **Data Binding**
Data binding is used to bind UI components in the XML layout files to data sources in the ViewModel, promoting a clean and efficient way to update the UI.

### 5. **LiveData**
LiveData is used within ViewModels to observe data changes and update the UI automatically, ensuring that the UI remains in sync with the underlying data.

## Code Structure
Here is a brief overview of the main files and their responsibilities:

- **MainActivity.kt**: The main activity that hosts the fragments and sets up the navigation component.
- **SplashScreen.kt**: Handles the splash screen logic.
- **CalculateFragment.kt**: Contains logic for calculating BMI based on user input.
- **HealthyFragment.kt**: Displays health information for users with a healthy BMI.
- **LeanFragment.kt**: Displays health information for users who are underweight.
- **OverWeightFragment.kt**: Displays health information for users who are overweight.
- **ObeseFragment.kt**: Displays health information for users who are obese.

## Getting Started
### Prerequisites
- Android Studio
- Android SDK

### Installation
1. Clone the repository.
2. Open the project in Android Studio.
3. Build the project and run it on an emulator or a physical device.

### Usage
1. Launch the app.
2. View the splash screen.
3. Navigate to the Calculate screen and enter your height and weight.
4. View your calculated BMI and corresponding health category.

## IMAGES
**1) SPLASH SCREEN**

![launchingpage](https://github.com/saravanan2047/BMI-App/assets/95707512/e7623854-d05f-41ac-8f32-0cb2dd9bbc2c)

**2) HOME PAGE**

![firstpage](https://github.com/saravanan2047/BMI-App/assets/95707512/506d8a38-fae3-40b2-aa93-2c79ac70e46f)

** 3) GIVING INPUT**

![input](https://github.com/saravanan2047/BMI-App/assets/95707512/9e016211-47ae-4ffb-87cc-bed5291d1564)

** 4) HEALTHY **

![Fit](https://github.com/saravanan2047/BMI-App/assets/95707512/adb1ad8e-78f4-49cb-8eb2-14a4940c0483)

** 5) LEAN **

![lean](https://github.com/saravanan2047/BMI-App/assets/95707512/4890ef84-ad7e-42d9-b70d-44e30559f926)

** 6) FAT**

![overweight](https://github.com/saravanan2047/BMI-App/assets/95707512/83c8aa32-ef76-45ed-8e12-edd06e8a17b9)

** 7) OBESE**

![obese](https://github.com/saravanan2047/BMI-App/assets/95707512/e80c9be6-0a27-4ab3-b5a9-a880e5067743)

** 8) HIGHLY OBESE**

![Highlyobese](https://github.com/saravanan2047/BMI-App/assets/95707512/51f67f83-145d-4cfa-8981-3e762a2122a9)


## Conclusion
The BMI Calculator is a simple yet effective tool for monitoring your BMI and understanding your health status. By leveraging modern Android development practices and design patterns, the app is designed to be both user-friendly and maintainable.

Feel free to explore the codebase and contribute to its development!
