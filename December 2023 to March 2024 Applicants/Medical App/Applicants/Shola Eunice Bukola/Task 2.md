Task 2
# Mboacare Application

## Record the running application
I ran the installed Mboacare application on my android device (Nokia G21 of android version 10) and also my emulator(Google pixel XL) here is the [link](https://drive.google.com/file/d/1HZBGF1GAgps4AdjUJR-wARlUCwh7PT3M/view?usp=drivesdk) to the recording.

# Documentation

## Observation 
I did my research on Mboalab and I discovered the aim of Mboalab is to catalyze sustainable local development and improve people's living conditions through open science and so putting two and two together, I was able to identify the issue that Mboacare is meant to address; searching for hospitals in your location, in other locations and also discovering what services they offer is what I believe is the problem being tackled. To add it as well the problem of a very loaded app being on in the english language is taken into consideration to make up for versatility.


Based on my observation, the goal of the app is to show people medical facilities, the services they offer and more primarily their locations and also help them connect with these medical facilities. 
This is clearly stated in the HomePage of the application and when I navigated to the Hospital dashboard and accessed all there is to access in this page the vision of Mboacare became clearer "Connecting Hospitals Globally" became clearer .



## Review of the Mboacare application
Let's delve into the review of the applications and my problem statement and suggestions for each page in the application 


### HomePage:

**Feedback**
1. It clearly states the reason or the statement of mission of the app and has a button for signup or login and also another to join the community.
2. I can also see that anyone that has any hospital details can sign up the hospital.


**Areas for revamp/Suggestions**

1. My Nokia G21 has a lengthy screen and so therefore when I opened the app everything about the homepage was just at the starting of the app and there was a lot of space at the bottom of it but my emulator seems to handle it just fine.

![image4](https://github.com/Mboalab/Outreachy-Applicants/assets/83653331/deb563d3-e475-4b4b-a78a-d8ad74a54e2d)


2. The Hospital signup is flawed because anyone can input details of a hospital but I don't know if the form checks if the hospital already exists before it submits. I think the input text field for the hospital name should check for that and validate it.

3. Upon registration of medical facilities all that displays is the Hospital dashboard, the bottom nav bar is not in sight and therefore the hospital cannot logout or perform other operations in the app.

![image5](https://github.com/Mboalab/Outreachy-Applicants/assets/83653331/35dcbacf-a343-41f2-84b9-e9d70506c6d5)


4. Again because of the length of my android device there seems to be a lot of space both ontop and under the login and signup pages.

5. The "forgot password" doesn't navigate to a new page but stays on the login page and asks to input email, meanwhile the password text field is still visible. I presume forgot password hasn't fully been implemented.

![image6](https://github.com/Mboalab/Outreachy-Applicants/assets/83653331/527e72b1-35f4-4cad-8568-4533bdc23919)


6. Let's say I decide to register and then remember I have an account there is no way to navigate except clicking the back button, i think there should be a "Have an account?. Login" text in the register page.

![image7](https://github.com/Mboalab/Outreachy-Applicants/assets/83653331/1a02da4c-66ea-4743-8620-bbc80c11fd01)


7. The UI of the snackbar or the pop up that returns feedback from firebase or generally in the app can be better.

![image8](https://github.com/Mboalab/Outreachy-Applicants/assets/83653331/90ad7b70-7563-4372-978b-a9af8e3b9791)



### Hospital Dashboard Page:

**Feedback**
1. The various operations of medical facilities actually filter according to each one e.g surgery when clicked displays hospitals that undergo surgery etc.
2. The implementation of the dropdown that houses different facilities also enhances more filtering.

**Areas for revamp/Suggestions**
1. The card/container housing the details of these facilities that also shows the medical services they offer overflows for certain devices like my emulator(Google Pixel Xl) and in bigger screens like my android device(Nokia G21) there seems to be more space.

![image9](https://github.com/Mboalab/Outreachy-Applicants/assets/83653331/2e01f46d-ce6a-487c-a717-27f2e63eb723)


2. The search bar isn't working i.e its not filtering according to the text inputted in it.

3. I think that instead of having a dropdown that helps filters for just facilities we should have a structure that can help users filter by location, facilities, hospital type, bed capacity and availability of emergency services.

4. I want to suggest that the email and phone number field should be clickable and navigate to both the email app or telephone app, same for the map.

### Settings Page: 

**General Feedback**
1. It houses just the field for changing language and it's not working.
2. I think there should be other settings that should be implemented like dark mode/light mode, changing of password, contact us, about us, sign out and delete account.

### Profile Page:

**General Feedback**
1. It just has the Mboacare logo and a button for signing out that doesn't work.
2. I think it should have the details of the user if the user is logged in and the user can edit these details and if the user is a first time user it should direct the user to sign up.
3. Finally I want to suggest that there should be a button to sign out if the user is logged in.


## General Feedback(UI/UX and functional)
1. The app isn't responsive but it needs to be.
2. The bottom navbar for the unselected is not visible.
3. I'm not sure if it's entirely necessary for users to have accounts since all they need is to just search and connect to hospitals globally but nevertheless login and registration for users should be implemented.
4. Looking at the code itself I think the MVC architecture should be used in this project and also I believe the state management "Provider" being used here is the best for it.
5. I think there should be a way for users to drop reviews for these medical facilities.

Overall the Mboacare app is still on track to achieving the mission of which it was created for.
Thank you.

