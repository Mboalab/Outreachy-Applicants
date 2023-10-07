# Mboacare Screen Record

- Mboacare screen record of app [drive link](https://drive.google.com/file/d/1KD3cRQxA9kqixCYmf1bu3BgX-o4WkqYU/view?usp=sharing).

# Mboacare App  🏥

Mboacare is an open-source mobile application designed and developed by MboaLab. Check more information about Mboalab [here](https://github.com/Mboalab/Outreachy-Applicants).  Accessing quality healthcare services, whether in your local area or abroad, can be a daunting task.  Mboacare is a platform that allows users to easily find and connect with medical facilities around the world.

## Project Motivation 👏

- Getting up-to-date information about medical facilities, services offered, and their location is often difficult.
- Referring patients to the right medical facility by other healthcare providers is also a challenge.

Mboacare is a mobile application that allows users to easily find and connect with healthcare providers both locally and abroad. With Mboacare users are able to get up-to-date information about which health services are provided by which medical facility, and also medical providers are able to refer patients to the right medical facility for proper treatment and diagnosis.

## Methodology 💡

Mboacare is being designed and developed using the following open-source software tools:

- Figma: The design tool used to create the user interface of the application. Figma is a cloud-based tool that allows designers to create and collaborate on design files in real time. Figma has a design library that allows designers to store, organize, and share design files.

- Flutter: The development tool used to create the application. Flutter is an open-source cross-platform application development framework created by Google. It allows developers to create mobile applications using a single codebase for different operating systems (OS) such as Android, iOS, web, windows, macOS, and Linux.

- Dart:  The programming language used to develop the application. Dart is a cross-platform programming language that can be used to develop native desktops. Dart is a statically typed programming language that uses the OOP (Object Oriented Programming) paradigm.  Dart is a general-purpose programming language that has features such as operator overloading, generic types, and static type checking. Dart is designed to work with Flutter and can be used to develop applications for different platforms.
- Firebase: The backend framework used to develop the application. Firebase is a cloud-based platform developed by Google. It allows developers to develop mobile applications that can be used to store and sync data in the cloud. Firebase provides a suite of tools that allow developers to build a backend for their mobile applications. It provides tools such as Firestore, Cloud Firestore, Firebase Realtime Database, Firebase Auth, Firebase Analytics, and Firebase Test Lab

- SendGrid: A third-party email service provider used to send notifications to users.  SendGrid is a cloud-based email service provider that allows developers to send emails to their users.  It provides an API that allows developers to send emails. It also provides a suite of tools that allow developers to manage their email sending and receiving.
Above mention tools are the main tools used in developing the Mboacare mobile application.

## Various user profiles 🥰

Mboacare App consists of two modules which are the User Module (patients) and Hospital Module (hospitals). Below are the various sections available in each module of the application.

### Sections in the User Module 🧑‍⚖️

1. Splash Screen: The first screen that shows up when the app is launched.
2. Dashboard: The dashboard is the main page of the application it also consists of a sub-section that includes:

    - Home: This is the first screen that shows when the splash screen is launched. Has a welcome message and an option for hospitals to sign up.

    - Hospital Dashboard: This screen shows the hospitals that have signed up. It consists list of hospitals, various information about the hospitals, and the hospitals' location. Users can search filters based on the diagnosis.

    - Settings page: The user can set language preference
    - Profile: Here User logout of the application.

### Sections in the Hospital Module 💊

The Hospital module also consists of a dashboard with various sections but with additional features compared to the User module. The extra sections for the hospital are:

- Dashboard: It consists of a welcome message and gives a link that enables hospitals to sign up or log in.
- Sign Up: This screen has a form that allows hospitals to sign up and completely register their information in the app database.

This hospital module consists of extra features like the ability to edit profiles, and to add new types of disease treatment with categories.

## Functional Section of Mboacare App ⛑️

- Splash Screen
- Hospital Dashboard
- Login Screen
- Sign Up
- Hospital registration
- Page to connect hospitals and users to the MboaLab Community.
- Search and filter for Hospitals on the hospital dashboard
- Authentication using Google. (Sign in and sign up)

## Non-Functional Section of Mboacare App 🦥

- Log Out
- Profile section incomplete
- Settings section incomplete
- Authentication incomplete

## Additional functionalities 👍

- User profile management such as updating profiles and changing passwords.
- Users are able to rate a hospital
- Users should be able to get notifications of new features or updates.
- Adding in-app chat feature for users connect with other users

Note: Other additional functionalities have been discussed already by passed interns which are cool futures that will enhance the user experience and usability of the app.

## Suggestions for the UI/UX 🎉

I must appreciate the efforts of the development team of the current Mboacare App. The UI is quite simple and clean. Below are my suggestions for the UI/UX to make it more beautiful and user-friendly:

### For UI  🖥️

- Getting a nice font for the text (font type).
- Improving the Responsiveness of the app.
- Implementing a good color blend.

### For UX 🏜️

- Improving the Navigation in the application.
- Providing users with dialog messages or any other indication of the action performed by the user.
- Adding animations like more good animation libraries like a spin kit.
- Maintaining the consistency of the application in terms of colors, font size, and shapes.
- Adding alert messages based on action taken.
- Adding an onboarding screen to help give first-time users the whole idea about the application.

### For Codebase 🧑‍💻

- Refactoring of the code base for more reusability.
- Making use of state management in the application.
- Improving the Codebase readability
- Adding readme on how to set up code base
- Providing a secure communication to the database.
- Implementing MVC pattern (Model view Controller)
- Implementing Repository format
