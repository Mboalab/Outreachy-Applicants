# Mboacare Application

## Running the application
- This is the link to the recording of the running app: https://drive.google.com/file/d/1_CTxQZBa6cbjDxECJtZV2yIHscmCRsbY/view?usp=sharing

# Findings

## 1. Introduction

The project is named "Mboacare". It aims to create a platform for users to find and connect with medical facilities worldwide. It targets both users seeking healthcare facilities and facilities in need of a global reach.

## 2. Problem Statement
The application addresses the challenge of finding medical facilities quickly and efficiently. It aims to solve the problem by providing a platform to easily access medical facilities in the app

## 3. Technology Stack
The technology stack includes:
- Flutter framework for app development.
- Dart programming language.
- Firebase for authentication and database management
- SendGrid for email communication
- Provider package for state management

## 4. User Profiles
   User personas include:
   - Patients: People seeking medical facilities and healthcare services.
   - Support Staff: Personnel to add healthcare facilities information.

## Functional Sections

1.  **Authentication**

This section handles hospital signup. Users can register and log in using email/password. FirebaseAuth is used for secure authentication and email verification
Sendgrid is used to send signup success emails

2. **Hospital Dashboard**

The dashboard displays hospital listings with filtering options for service offered and facilities present. Users can from there view facility details

3. **Hospital Profile**

Hospital profiles provide detailed information about each facility, including services, specialties and contact details. WebView is used to display external hospital websites.

## Non-Functional Sections

 1. **Hospital dashboard**

 - Search is not working
 - Hospital card overflows for some hospitals

2. **Profile Page**

There is a hard coded Log out option even without logging in

3. **App Localisation**

Only English works

## Additional Functionalities

- Google Sign in provides a good option to people who can't easily signup with their emails

## UI/UX Suggestions

### Suggestions for the app as it is now.
- Save authentication state after user signs up
- Filter hospitals by country and state/region
- Mention if beds are available at a given moment
- Determine login state and remove hard coded log out option
- Show submitted hospital verification process progress
- If a hospital is not found, user should be given an appropriate message
- Put hopsital information to the profile for logged in users and make it editable
- Add localisation strings and set default locale to system locale

### Suggestions for split up clients

The Mboacare main app can be split into two different clients, one for users seeking hospitals and another for hospital support staff can offer several benefits that include simplified and user-focused experience.

### Patient Client
- Optional user registration for more personalised experience
- Hospital search dashboard on the landing page
- Search hospitals by country, state/region
- In-app chat with hospitals
- Notifications
- Users book appointments directly from the app
- Ratings and Feedback
- Signed up users information to profile page and make it editable

The suggested screens design is at this figma link: https://www.figma.com/file/XvEjzfI2gKERZUNRYqt5jA/Mbaocare-Patient?type=design&node-id=0%3A1&mode=design&t=YddLIk2bKLMOjpib-1

### Support staff Client
- Link support staff accounts to hospitals
- Main dashboard showing important activity.
- Hospital information editor for adding and updating about info
- Appointment scheduling
- Add hospital information to profile and make it editable
- Secure messaging to attend to querries raised through the app
- Multi-language support for hospital staff

The suggested screens design is at this figma link: https://www.figma.com/file/N0RqxeV3AeRbkUjfLSJFWE/Mbaocare-Staff?type=design&node-id=0%3A1&mode=design&t=eB1T59uA7dt87H5N-1

## Conclusion

Mboacare aims to improve healthcare access by providing a user-friendly platform to discover and connect with medical facilities worldwide.

