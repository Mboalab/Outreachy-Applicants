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

### Refactoring of the code base for more reusability 🙂

I appreciate the developer who worked on the current project. Ensuring the project work is always the goal. Let's come to code maintainability, is very important in a project. This ensures project continuity in that another developer should be able to work on the code base with minimal hitch.

- What is Code Refactoring:
Refactoring is the process of restructuring existing code in terms of improving code readability, maintainability, and performance. Refactoring is a disciplined approach to code improvement that is intended to keep the code clean and maintainable. The goal of refactoring is to improve internal code structure by separating business logic from the interface. Refactoring is a fundamental part of software engineering. Note should be taken that refactoring does not affect the external behavior of the software.

- Reusability of Code: Reusability of code is one of the most important aspects of the project. Reusability of code is possible when a piece of code can be reused. The reusability of code is a very important concept in software engineering. It helps in reducing the development time and cost.

### Making use of state management in the application 👍

I do appreciate the developer for making use of state management which is the provider. Though implemented, there is to lot to do when it comes to implementing state management. In building high-quality apps with Flutter, state management is one of the most important aspects of the app. State management is to ensure the app state is saved and restored properly. Some question state management seeks to Answer is: 

- What happens if the app crashes?
- How to save application state across different screens.
- When should the application state be saved?
- How to make data persistent across different devices?
- Checking of connectivity before saving the app state.
There are a lot of questions state management answers.

In Flutter there are a lot of ways to implement state management. Making use of packages and inbuilt state management is one of the ways. Some most commonly used state management packages are:

- Getx
- Provider
- Riverpod
- BloC

For this project, I suggest we use the Getx package. Let's take a deep dive into Getx.
#### What is Getx?😀

Getx is a state management package that provides a simple and intuitive structure and manages our codebase. We can get the documentation and package [Get](https://pub.dev/packages/get). It consists of two patterns clean architecture and Getx pattern. Getx is the most popular state management package for Flutter due to its simplicity, lightweight, and numerous features. Getx is not just a state management package it has other features that come with it. Some include:

- Navigation 🥰: when it comes to navigation in Flutter the first thing that comes to mind is the Navigation module provided by Getx. Though Flutter provides navigation, it is not as flexible as Getx. With Getx we can create reusable navigation modules, add transitions, effects, and many more. Navigation in Getx is straightforward, easy to understand, and easy to implement. For example, we have Get.to(page) and we can just pass the page we want to navigate to.
- Localization 🥳: Getx provides a simple and easy way to localize our app. We can use the Getx package to translate our app and provide users with a localized version. It reduces the time it takes to localize our app. We can use the localization feature by setting up a key-value pair in our app using the localization key. For example locale : [‘en’, “fre”].

- Dependency Institute: Dependency injection is a design pattern used to inject dependencies into an object. It allows us to have a clear dependency relationship between an object and its dependencies. Getx provides a simple way to do dependency injection. We can create a new object by passing a key.

#### Why Getx?😀

Getx is a package that provides a simple and easy way to modularize our application. Since our app consists of two modules, Using Getx partten we can restructure our app by defining the various modules and adding them to our app. Getx pattern breaks down our code into view, binding, and controller.

- Here the view is responsible for displaying the data to the user.
- The controller houses all the logic for the app.
- The binding is responsible for linking various aspects of the app and connecting it to the app engine.

#### Easy to maintain 🙂

one important nice thing about Getx is that it is very easy to maintain. Since the app is divided into different modules. We can change the code of any module without affecting the other module.

### Adding readme on how to set up code base 🎉

This involves documenting the project setup in a Readme.md file. This will enable other developers to set up the code base and contribute to the project. That is a step-by-step process to set up the code base.

### Providing secure communication to the database

The current app makes use of a NoSQL database, which is firebase database. Communication to the database is direct from app which at some point it will be insecure. To ensure security, we implement another layer of security. By developing API it will help remove direct access to the server and will be a better way to protect the data.

### Development of RestFul API to communicate with the database 💯

Developing a RestFul API will ensure security of the database. They won’t be direct access to the database. Also adding security measures such as token base will help prevent unauthorised access. Wth the used of API we turn to improve the following:

- Reducing the server load and network traffic
- Increasing on app performance
- Improving on app response time
- Prevent direct access to the database.
