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

### App Observation🧑

#### Good Observation

- Splash Screen: The splash screen is awesome, the animation and friendly welcome message gives a good user experience.
- Color choice: The choice of color for Mboacare is awesome
- Dashboard: The dashboard is simple and clean, users can easily access the app features directly given a good user experience. The dashboard consists of a sub-section that includes:

  - Home: informative, as a user of the I get to know an overview of the application, the community for further help, and register my hospital if i have one or plan to have one

  - Hospital Dashboard: user friendly and access of content is very easy. it features are: display list of sign up hospital, search bar to easily locate a hospital, filter && dropdown menu to narrow my search. All this feature brings about good user experience.

  - Settings page: The user can set language preference
  - Profile: Here User logout of the application.

- Email notification: when user of the application sign up for the first they receive a welcome message with guides on what to do next. This feature is so great as it guides the user on next step.

- Hospital details: Upon clicking on a hospital am redirected to hospital details there am able to get detailed information about the hospital making information access easy.

- Making use of Google Authentication is a good practice when it comes to security of the app and client which the app is making good use of.

#### what can be done to improve the app⛑️

1 - Sign up: The current input fields for registration in to Mboacare app is good,but adding another field such as role(patient or hospital) is good because it will determine the user and what screen to navigate too.

![Input Fields](../Task%202/input%201.jpeg)

2 - Search feature: Adding user friendly message to display to user when the search result is empty will improve on user experience instead of displaying a blank screen. Current search results display an empty or blank screen when result is not found.

![Search Result](../Task%202/search%20message.jpeg)

3 - UI Responsiveness: Some content turns to go out of design rendering some error messages to the user which is not making the user experience friendly. This UI can be improve.

![Responsiveness](../Task%202/responsiveness.jpeg)

4 - Error messages: Return error messages is very important in application, Mboacare currently return error messages which is great the design can be improved upon by providing a friendly messages. This can be done using snackbar, alert notifications.

![current error message](../Task%202/error%20message.jpeg)

Here are some suggestions of error and success response:

![Error](../Task%202/error.png)  ![success](../Task%202/succ.png)

5 - Form validation: The current app does not handle form validation before submission. when user click register it returns the error from the backend. It is good the form is validated before send to the backend.

![Current form](../Task%202/input.jpeg).

Suggest validation:

![Form Validation](../Task%202/registration%20error.png).

6 - No Bottom Navigation: When I registered as a hospital am redirected to the dashboard with no bottom navigation.

![No bottom navigation](../Task%202/hospital%20reg.jpeg).

7 - Location: During registration of a new hospital, another field need to be added for user to be able to search for location this can be done by adding google map

8 - hospital details: The current hospital details displays hospital details how ever some features are missing which if added will improve on user navigation such as google maps and location.

![Location](../Task%202/details.jpeg)

9 - Bottom Navigation improvement: The current bottom Navigation is good how ever changes such as modifying the opacity of the color, new icons and renaming of the nav items will be great.

![Nav bar](../Task%202/nav.jpeg)

Suggestion for name:

1 - For user:

   - Home
   - Hospitals
   - Favorite
   - Profile

2 - For Hospitals:
   - Home
   - Manage Hospital
   - Messages
   - Profile

10 . User Sign up/Sign in : Mboacare is made up of two sections base on documentation how ever only the hospital section consist of this feature. Note should be taken that is one of the most important feature because it will determine where to rout user to.
 
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

### Additional Observation

#### For Codebase 🧑‍💻

- Refactoring of the code base for more reusability.
- Making use of state management in the application.
- Improving the Codebase readability
- Adding readme on how to set up code base
- Providing a secure communication to the database.
- Implementing MVC pattern (Model view Controller)
