# Mboacare Application

## Running the application
- This is the link to the recording of the running app: https://drive.google.com/file/d/1_CTxQZBa6cbjDxECJtZV2yIHscmCRsbY/view?usp=sharing

# Findings

## 1. Project Overview
**Introduction**

The project is named "mboacare" and is developed in collaboration with Mboalab. It aims to create a platform for connecting global medical facilities.

**Goals and objectives of the project**

The main goal is to provide an easy-to-use platform for users to find and connect with medical facilities worldwide. It targets both patients seeking healthcare and healthcare facilities looking to reach a global audience.

**Target user base**

The app caters for users in search of healthcare services and hospital support staff who add hospital information.

## 2. Problem Statement
The application addresses the challenge of finding suitable medical facilities quickly and efficiently. It aims to resolve the pain points associated with time-consuming online searches and the lack of a comprehensive platform for accessing global healthcare options.

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
   - Support Staff: Personnel assisting users and healthcare facilities with app related issues.

## Functional Sections

1.  **Authentication and authorisation**

This section handles hospital signup. Users can register and log in using email/password. FirebaseAuth is used for secure authentication and email verification
Sendgrid is used to send signup success emails

2. **Hospital Dashboard**

The dashboard displays hospital listings with filtering options for service offered and facilities present. Users can from there view facility details

3. **Hospital Profile**

Hospital profiles provide detailed information about each facility, including services, specialties and contact details. WebView is used to display external hospital websites.

5. **Settings**

This displays the would be settings for language choice

## Non-Functional Sections

1. **Authentication**
 
 Authentication is not whole functional. User should not be shown sign up again on home page after signing up and the log out button on profile is not working

 2. **Hospital dashboard**

 - Search is not working
 - Hospital card overflows for some hospitals

3. **Profile Page**

There is a hard coded Log out option even without logging in

4. **App Localisation**

Only English works


## Additional Functionalities

- Google Signig provides a good option to people who can't easily signup with their emails if it works

- Firebase Firestore enable scalability to handle a growing user and hospital database.

## UI/UX Suggestions

### Split the app into two clients

Splitting the app into two different clients, one for users seeking hospitals and another for hospital support staff can offer several benefits in terms of usability, security, and efficient development and maintenance processes. The benefits include;

 1. **User-Focused Experience**
   
   Patients typically have different needs and objectives compared to support staff. Separating the clients allows tailoring the user experience to each group's specific requirements.

2. **Security and Privacy**

Seperating clients offers an opportunity for easier data segregation through enforcing strict role based access control firebase rules, reducing the risk of unauthorized access or data breaches and regulatory compliance. 

3. **Simplified User Interfaces**
   
Separate interfaces reduces clutter and make it easier to design clean user interfaces tailored to each user group.

4. **Performance and Scalability**

By creating specialized clients, functionality for each group can be optimized. This can help ensure that the applications remain performant, even as more features and users are added.

5. **Development and Maintenance**

Separating the applications allows for modular development, making it easier to add or modify features without impacting the other client. This can speed up development cycles, reduce the risk of introducing bugs

### General suggestions

- Polish the bottom navigation bar icons' colors so that unselected icons are visible.
- Instead of mentioning bed capacity, It should be if beds are available at that very moment
- If a hospital is not found, user should be given an appropriate message
- Save authentication state after user signs up
- Add localisation strings and set default locale to system locale

### Patient Client
- Optional user registration for more personalised experience
- Move hospital search dashboard to the landing page
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

Mboacare application aims to revolutionize healthcare access by providing a user-friendly platform to discover and connect with medical facilities globally. By splitting clients, this aim will be easier to achieve with hospitals and clients getting customized feautures.

