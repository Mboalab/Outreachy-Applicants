
# Task 3

## Recording of Mboacare App on android device
This is the link to the [video recording ](https://drive.google.com/file/d/11OgUl7K-AjFb4TxhJqjqW5UzvMF_VNEe/view?usp=sharing) of the installed app on my device.



## Mboacare App Documentation Guide 

### 1. Introduction

- Mboacare is an open source mobile app built and maintained by Mboalab, a biology lab and makerspace found in Yaounde, Cameroon. Operating as a research and applied Center for Open Science and Citizen Science, Mboalab was officially opened in December 2017. 

- The aim of MboaLab is to catalyse sustainable local development and improve people’s living conditions through open science.

- The aim of the app Mboacare is to connect various medical facilities globally, enabling them to collaborat effortlesly and improve healthcare outcomes.

### 2. Problem statement

#### * Lack of Connectivity and Collaboration: 

The healthcare industry faces challenges in connecting and collaborating across various medical facilities globally, resulting in inefficiencies and suboptimal patient care. There is a lack of an effective platform that enables seamless collaboration among healthcare professionals and institutions.

### * Fragmented Communication and Missed Opportunities: 
The current disjointed approach to global medical facility connectivity leads to fragmented communication, delays in accessing critical information, and missed opportunities for collaboration. This hinders the ability of healthcare providers to share knowledge, expertise, and resources, ultimately impacting patient outcomes.

#### * Need for Improved Healthcare Outcomes
The absence of a reliable platform for global medical facility connectivity prevents healthcare professionals from efficiently sharing patient data, consulting peers, and coordinating care plans across borders. To address this, there is a need for a solution like the Mboacare app, which aims to connect medical facilities worldwide and facilitate effortless collaboration. By leveraging technology, Mboacare strives to improve healthcare outcomes by enabling healthcare professionals to make informed decisions, access specialized consultations, share best practices, and collectively work towards advancing medical research and innovation.



### 3. Project Understanding
To provide a comprehensive understanding of the Mboacare app, let's explore its key functionalities:

- Main Dashboard: A user-friendly dashboard with easy navigation through bottom app bar icons for search, notifications, and filter tabs.

- Hospital Profiles: Detailed profiles for hospitals with contact details, services, specialties, and user reviews, aiding informed decision-making.

- User Authentication: Secure login using Google accounts for seamless access while protecting user data.

- Hospital Registration: Streamlined registration process designed specifically for hospitals, ensuring accurate profile information.

- Splash Screen: Engaging screen for a positive app launch experience.

- Social Media Integration: Links to follow Mboalab on LinkedIn for updates and industry insights.

- Login Page: Additional fields like Name, Username, Email Address, Password, and Confirm Password for personalized registration.

Gmail Authentication: Secure email verification for account authenticity and enhanced security.

Through these functionalities, the Mboacare app aims to simplify healthcare access, empower users, and facilitate effective communication between users and hospitals.



### 4. Methodology
The development of the Mboacare app follows an agile approach, allowing for iterative development and continuous improvement based on user feedback. The following frameworks and technologies were employed:

- Design: The app's user interface (UI) design was created using Figma, a collaborative design tool that facilitates efficient collaboration between designers and developers.

- Framework: The Mboacare app is built using the Flutter framework, enabling cross-platform development for both iOS and Android platforms, ensuring a consistent user experience.

- Authentication: Google authentication is implemented within the app, leveraging the Google Sign-In API to provide secure and seamless user authentication.

- Database Management: Firebase Cloud Firestore is chosen as the database management system for the app. It allows for efficient data storage, retrieval, and management, enabling seamless creation, reading, updating, and deletion of data.

- File Storage: Firebase Storage, a cloud-based service, is utilized to store and retrieve user-uploaded content, such as pictures, videos, and files. This ensures safe and reliable storage of user-generated data.

- Email Communication: To facilitate personalized email communication, the third-party API service SendGrid is integrated into the app. It enables the sending of welcome emails for successful user registrations and validation emails for hospitals, enhancing the user experience and ensuring effective communication.



### 5. Functional Section


#### 1. User Interface and Navigation

- Main Dashboard
- Hospital Profiles
- Splash Screen
- User Management

#### 2. User Authentication
- Hospital Registration
- Enhanced Login Page
- Information and Communication

#### 3. Information and Communication
- Comprehensive Hospital Profiles
- Social Media Integration

### 6. Non-functional section

#### 1. Security
- User Authentication
- Gmail Authentication

#### 2. Performance
- Splash Screen
- User Interface Responsiveness

  

# Section 2 (UI/UX Suggestions)

#### 1. Authentication UX Issue
- I noticed that upon opening the app, The first screen I'm being presented with is the signup screen but when I click on signup it leads to login.

https://github.com/Ihimbru-K/Outreachy-Applicants/assets/87714194/eb8eb783-f223-41aa-bf12-a17dfffcc5b9


##### Proposed solution
- Login and signup modules should can be set apart on the concerned UI.

#### 2. No dashboard for a hospital account created
- I should be able to get to my dashboard as a hospital owner signed up in the system

https://github.com/Ihimbru-K/Outreachy-Applicants/assets/87714194/1e6f9012-47bf-47c1-b1f0-ca5cb28b76f6


##### Proposed solution
- The UI can be modified to contain a dashboard module wherein I can find information on my profile

#### 3. Impossibility to edit profile
https://github.com/Ihimbru-K/Outreachy-Applicants/assets/87714194/0d79d98b-13c7-4a86-a5d7-77baf5d2008a
##### Proposed solution 
- A modification can be done in the dashboard or settings page that will enable the owner of a hospital account modify his/her profile.
















