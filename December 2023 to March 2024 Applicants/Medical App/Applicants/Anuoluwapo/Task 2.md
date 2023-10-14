##  Record link

This is the link to the recording of the running app using an android device:
[link](https://drive.google.com/file/d/1BehuW1quo_Z65r7mOo4nwGqgaEI4pn0C/view?usp=drive_link)

##  Project Overview
## 1. Introduction

The project called **mboacare** is a platform for connecting global medical facilities and is developed in collaboration with Mboalab. The aim is to provide a platform where hospitals can sign up, and register the various facilities and services as per their location, and other hospitals can easily refer patients, or patients can easily locate a hospital for each case. It is a platform that allows users to easily find and connect with medical facilities around the world.

## 2. Problem Statement

The application addresses the challenge of finding which hospital can treat a patient of what disease, and where is it located, It also address the finding of suitable medical facilities which leads to the increase mortality rate. Developing and launching this app will save time, and money and most importantly, reduces mortality rate.

## 3. Methodology
The methodology used in the app is called waterfall methodology.
## 4. Technology stack 

- Flutter framework for app development.
- Dart programming language.
- Firebase for authentication and database management
- SendGrid for email communication

## 5. Functional sections of the application

 **Authentication**
 - User can signup and login with email and password. 
 - After regsitration, the user  get a confirmation email.
 - The splash screen is awesome, the animation and friendly welcome message gives a good user experience.
 


 **Hospital Dashboard**

 - The hospital dashboard shows a list of all the hospitals with the service offered and facilities present.

 **Hospital Details**

 - It provides information about each hospital e.g address, phone number,  email facilities available, service offered etc.

 **Settings**
 - It displays only the English language choice.
  

## 6. Non Functional Sections of the Application

 **Authentication**
 - Users should not be asked to fill the hospital form again when they logged in the second time. This should be only one time process. Instead, they should be directly redirected to the list of hospital.
 The users authentication state should be save after sign up.


https://github.com/mercyjae/Outreachy-Applicants/assets/83911888/e432c39b-c08c-4169-bbce-e5dce6413ae9


 - The sign in with Google account doesn't work.

 - https://github.com/mercyjae/Outreachy-Applicants/assets/83911888/587aa2b7-5eb7-4ad7-bf52-db6d86b230d7

  **Hospital Dashboard**
 - The facilities in the hospital card overflows. The hospital container is meant to enlarge as the number of facilities increases. 

https://github.com/mercyjae/Outreachy-Applicants/assets/83911888/66318c51-07b0-466d-98ae-71c0ba75295e


 
**App localisation**
 - Only English works, other languages doesn't work.

https://github.com/mercyjae/Outreachy-Applicants/assets/83911888/aeeaef9d-123f-4731-8647-935cbf190085



  **Profile Page**
 - The logout button doesn't work.
 - The user details is not shown in the profile page.
 
https://github.com/mercyjae/Outreachy-Applicants/assets/83911888/5da7e2d1-ec80-4a92-ae52-0f740f30c345




## 7. Additional Functionalities
- Hospital can be filtered based on public or private.
- Instead of the bed capacity features, it should be if the beds are available at that moment.
- If hospital isn't found, there should be an appropriate answer given to the user.
- There should be an in app chat with hospitals.
- Sign up users information should be added to the profile page and it should be editable.
- Appointment scheduled.
- Hospital shoud be able to get notifications.
- Rating and feedback by hospitals.
- The app should permit users to find and connect with medical facilities around the world. There's no option for user to register. Only hospital registration is available
- Addition of edit profile screen. This makes user to be able to edit their details.

## 6. Suggested UI/UX
- The contrast color of the unselected bottomnavbar icons needs to improve to enable visibility. They're not visible enough.


## 7. Conclusion
- Mboacare application aims to transform healthcare access by providing a user-friendly platform to find and connect with medical facilities globally. By looking into all the stated observations above, the aim will be achieved and the rate of mortality in the society will reduce.
