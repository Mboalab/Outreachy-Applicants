
# Table of Contents

1. [Chapter 1: Introduction](#chapter-1-introduction)
    - [problem Statement](#11-problem-statement)
    - [Objectives](#13-objectives)
    - [Scope of Study](#14-scope-of-study)
    - [Software and Hardware Requirements](#15-software-and-hardware-requirements)

2. [Chapter 2: Research methodology](#chapter-2-research-methodology)
    - [Introduction](#21-introduction)
    - [Software Development Methods](#22-software-development-methods)

3. [Chapter 3: Analysis](#chapter-3-analysis)
    - [User Requirements](#32-user-requirements)
    - [System Requirements](#33-system-requirements)
        - [Functional](#331-functional)
        - [Nonfunctional](#332-nonfunctional)
    - [Summary](#34-summary)

4. [Chapter 4: Design](#chapter-4-design)
    - [System Design](#41-system-design)
    - [Database Design](#42-database-design)
    - [Interface Design](#43-interface-design)
    - [Design Recommendation](#44-design-recommendation)

5. [Implementation](#chapter-5-implementation)

# Chapter 1: Introduction
## 1.1 Problem Statement
Healthcare is very important to us humans, and the first place that comes to our minds when we think of healthcare is a hospital. Finding a good hospital or health facility depending on your health condition is a major problem in Cameroon, Africa, the world. Many people book appointments at hospitals only to get there and realise that there are no specialists or doctors for their case. Travellers also have difficulties with healthcare on their trips abroad. For example, if you have heart problems, you have to be sure that your destination has at least one health facility with a cardiologist. The internet has helped a lot in this domain but having a platform that gives people such information is vital.

That’s where Mboacare steps in. Mboacare is a platform that allows users to easily find and connect with medical facilities around the world. You're on the hunt for top-notch healthcare recommendations, whether you're in your own state or in a whole different country. You can find hospitals that offer a variety of healthcare services at your finger tips. No more wasting hours on Google and clicking through a gazillion hospital websites. That's where our super awesome application swoops in.

It's a game-changer in terms of usability and convenience. Just a few clicks and you can access a comprehensive list of hospitals, filter them according to your specific needs, and even contact them with ease.

Mboacare goes beyond the boundaries of a single hospital or location. Mboacare provides a global healthcare experience. You can explore healthcare facilities from different parts of the world, compare their services, and make informed decisions. Whether you are planning a trip abroad or searching for the best healthcare options locally, Mboacare has got you covered. And it's not just for patients! Healthcare facilities can also register and showcase their services on our platform, giving them the opportunity to reach a global audience.
With Mboacare, most of the problems listed above will be reduced if not solved.

## 1.3 Objectives
### Main Objectives
The main objective of this project is to develop a platform that can help users to easily find and connect with medical facilities around the world.
### Specific Objectives
The following are specific objectives based on the services to be offered by the application.
-The core objectives which have been designated as fundamental to the project are:
-Give hospitals the ability to create account and have a profile.
-Allow users to view a list of all the hospitals and medical facilities on the platform.
-Allow users to contact a particular hospital.

## 1.4 Scope of Study
The platform will be used as an application that serves individuals, hospitals, and health facilities. The intention is to help patients find and connect with medical facilities around the world with ease.

## 1.5 Software and Hardware Requirements
- An Android device(phones or tablets) running Android version 8 or higher can be used to run the application.
- The device should have at least 2 gigabytes of Ram. 
- Google Play Services should also be installed.
- An active internet connection is required as well.
- The application can also run on an emulator so far as the above criteria are met.


# Chapter 2: Research Methodology

## 2.1 Introduction
The are several methods that can be implemented here, like Data collection methods, data analysis methods, and Software development methods. I'll talk briefly only on Software Development Methods because there's no information to my knowledge as of now concerning the other two.

## 2.2 Software Development Methods
The team uses the Agile Software Development Methodology. With Agile the team can easily build the application incrementally, adding new features on the go. Changes can also be made with ease as development advances.

# Chapter 3: Analysis
## 3.2 User Requirements
- Hospital should be able to register 
- Hospital should be able to login
- Hospital should be able to edit their profile
- All users can view a list of hospitals
- All users can view hospital information

## 3.3 System Requirements
### 3.3.1 Functional
- The system must allow hospitals to create accounts using unique emails and passwords.
- The system must allow hospitals to log into their accounts.
- All users can view the list of hospitals and be able to search and filter through the hospitals.
- The system should provide a form during hospital registration for hospitals to fill their profiles and show the services they offer.
### 3.3.2 Nonfunctional
#### Performance Requirements
- **Response time:** The application launches fast and information is loaded in less than 2seconds provided the internet connection is stable.

- **Capacity:** The system shall support more than 1000 concurrent users without crashing.
- **UI/UX:** Navigating the system is smooth.

#### Security Requirements
- Any personal information provided by the users shall be kept securely. Information is safely encrypted.
- All user paswords are hashed before stored.

#### Software System Attributes
- **Usability:** The system shall be used continuously without a crash.
- **Availability:** The system shall be available for use all the time.
- **Correctness:** Bugs are glitches are constantly fixed to ensure a smooth user experience.
- **Maintainability:** The system shall be maintainable with new updates.
- **Accessibility:** All users can access the system but the access level depends on the type of user, that is, a normal user or a hospital.

## 3.4 Functional and Nonfunctional sections of the application

### 3.4.1 Functional Sections
- Registration and login forms work.
- Hospital information form works. That is the form immediately after entering the email and password.
- The list of hospitals displays.
### 3.4.1 Nonfunctional Sections
- The application isn’t responsive.
- There is no form validation on all forms.
- The user profiles and logout button doesn’t work.
- It is not possible to view or edit profile information once logged in as a hospital.
- When the number of tags on the hospital card are too many, there is an overflow error.
- Once you create your hospital account and get redirected the list of hospitals page, pressing the back button takes you the hospital information page. It would be better if the hospital information form was available under user profile.
- The hospital website link does not work.
- The language drop-down doesn’t work.
There is no profile page and no edit profile option on the application.

- The inactive tabs of the bottom navigation have a colour and contrast similar to the application background colour. Which makes it difficult to view the tabs.
- The Log in form for hospitals doesn’t work even after creating an account several times.

- User session is not saved. As such even after creating a hospital account, the user can press the back button and go back to the home page.

## 3.5 Additional Functionalities
- Adding modal spinners after a button is clicked would be great.
## 3.6 Suggestions to the UI/UX
- There is no dark mode. Adding dark mode 
Making the application responsive would help people using the application on different sizes of mobile devices and tablets.
- Including a side Drawer after a hospital logs in would help the user navigate to pages like profile and settings.
All the hospital cards have the same image. It would be good for hospitals to upload their image.
- It would be great for the hospital cards(in the hospitals list) to have flexible heights and responsive as well. This will prevent overflow error like the one seen below:

Image

- When a hospital doesn’t offer any service and there are no tags to display, There should be a notice like “**No services offered**” or “No Emergency services instead of leaving the cards as shown below”

Image

- The services and Facilities section should be left-aligned instead of leaving it as below.


- There is no pagination for the list of hospitals. Including a pagination would help users easily navigate and get a sense of how many hospitals are available. Also if the total number of hospitals could be displayed on the page, it would also help.

- When you create an account and fill the hospital information, you go to the hospital dashboard. If a user presses the back button they are taken back to the hospital signup form. Upon filling the form, another hospital is created. With this behaviour, it would seem that an account can create multiple hospitals and also, there is no way to edit any of the hospitals created. 

- It would be great if one account is limited to one hospital. I'm thinking this is a bug that can be fixed, if not then I propose that we do it as such, with one account having just one hospital. If that's not the case then a list of hospitals pataining to a particular account can be dispplayed.

# Chapter 4: Design

## 4.1 System Design
The application has two types of users, “Normal users or patients” and “Hospitals”. Normal users do not require an account but they can view a list of hospitals and the services. 
On the other hand, hospitals require an account before they can make their services know. When a new hospital account is created, the hospital is added to the list of hospitals.
## 4.2 Database design
The main entity in the application is the Hospital entity. 
## 4.3 Interface Design
The user interface is designed using Figma, a free design tool available for web and desktop.

Images

## 4.4 Design Recommendation
- I would suggest using the Model-View-Controller(MVC) pattern for the project structure. This pattern would make it easy to organise project folders and files. 

# Chapter 5: Implementation

The application uses a wide range of tools. The main ones are listed below.
1. **Flutter:** The application itself is built using Flutter which an apensource cross-platform development tool. Flutter uses Dart which is a strongly-typed null-safe language.

2. **Firebase:** Firebase is a service owned by Google which comprises of many tools. These tools include:
- **Firebase Auth:** Authentication on the application is done using Firebase Auth.
- **Cloud Firestore:** All hospital information and other information on the system is store using Cloud Firestore. Which is a real-time database offered by Google.
- **Git and GitHub** are used for version control and collaboration by the team.