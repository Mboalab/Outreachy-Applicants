# 1-Set Up 
This Task Focuses on setting up the tools and environments required for the successful contribution to the Mboalab medical project. 
I will outline below my journey towards achieving this task.
### Github account
GitHub, is a platform and cloud-based service for software development and version control using Git, allowing developers to store and 
manage their code
* The first thing I needed was to create a GitHub account.
* To create an account on Git Hub, the first step needed is to go to their official signup page (Github)[https://github.com] and sign up. 
* The images below outline the steps taken to a successful signup.
  
![github1](https://github.com/falyne/Outreachy-Applicants/assets/19360782/25dc4bd7-0bec-4eda-aaca-0e399b6fab6c)

Enter Signup Credentials( Email and Password)
![github3](https://github.com/falyne/Outreachy-Applicants/assets/19360782/8039c2ac-e654-4c72-90e0-4088aee7cf6e)

Signed in successfully and setup page.
![github4](https://github.com/falyne/Outreachy-Applicants/assets/19360782/52708412-2dcc-4929-8da5-dbdaa9ef207c)


## Installing Git
Git is a distributed version control system that tracks changes in any set of computer files, usually used for coordinating work among
programmers who are collaboratively developing source code during software development.
* To install Git, I visited their official site [Git](https://git-scm.com) and downloaded the latest version of Git.
* After successfully downloading git I proceeded to install using the Windows installer.
* The following images outline the steps.
  
![git1](https://github.com/falyne/Outreachy-Applicants/assets/19360782/631118c1-4317-4c73-8aa6-883805a2ddb1)

Accepting License

![git2](https://github.com/falyne/Outreachy-Applicants/assets/19360782/005db8c6-34e9-46b2-9282-7f58f7c98036)


Selecting components (Ideally I let all the components already ticked to install)
![git3](https://github.com/falyne/Outreachy-Applicants/assets/19360782/56d53cf4-49cc-4160-b865-02b301db1060)


Click next until the final button shows install

![git4](https://github.com/falyne/Outreachy-Applicants/assets/19360782/b3b22ff6-60c9-4df1-ab00-d2db152e618e)


![git5](https://github.com/falyne/Outreachy-Applicants/assets/19360782/efef23c7-740c-4e2a-a2ef-3276e55c508e)

Then I installed it.

![git6](https://github.com/falyne/Outreachy-Applicants/assets/19360782/9e6c1e1c-f641-44f6-8e04-80917455a518)

**Checking if git was installed.**
* The first way I get to check this is just by searching for git bash on the start menu. If it exists then it was installed successfully
* Another way is I type the command *** git --version *** on the command prompt and the version of git installed will be shown

![git-check](https://github.com/falyne/Outreachy-Applicants/assets/19360782/313346fa-e6ca-4486-9a49-13757b680512)

### Flutter 
To install Flutter I followed a number of steps including;
**Step 1** - Navigating to the official [Flutte](https://docs.flutter.dev/get-started/install) site, and choosing Windows operating system (This is my working system) and check if my system meets the
 requirement listed on the site.
 
   
![flutter1](https://github.com/falyne/Outreachy-Applicants/assets/19360782/80564a17-e5b8-40c0-918d-f26fb964812d)

**Step 2**- **Getting the Flutter SDK**
  Still on the official [Flutter](https://docs.flutter.dev/get-started/install/windows) site, I downloaded the installation bundle to get the latest stable release of the Flutter SDK:
   After this, I extracted  the zip file and placed the contained flutter in the desired installation location (C:\Flutter\flutter) for the Flutter.
     
**Step 3**-Update path Variable
In order to run Flutter commands in the regular Windows console, I added Flutter to the PATH environment variable:
From the Start search bar, I entered ‘env’ and selected Edit environment variables for your account. Under User variables, I check if there is an entry called Path:
the entry existed, so  I appended  the full path to flutter\bin using ; as a separator from existing values.


![varia](https://github.com/falyne/Outreachy-Applicants/assets/19360782/3d051c65-324e-4050-a391-62ce7dda57c6)

**Step 4**-Run flutter doctor
From a console window that has the Flutter directory in the path (above), I Ran the following command to see if there were any platform dependencies I needed  to complete the setup:

![Flutter-doctor](https://github.com/falyne/Outreachy-Applicants/assets/19360782/31a42c5f-b06c-4a6b-af60-8d6ad2302497)

### Android setup
**Step 1-Install Android Studio**
From the official [Android Studio](https://developer.android.com/studio) site I downloaded and installed Android Studio.
I started the  Android Studio, and went through the ‘Android Studio Setup Wizard’.
This installs the latest ***Android SDK,*** ***Android SDK Command-line Tools***, and ***Android SDK Build-Tools***, which are required by Flutter when developing for Android.
I still ran flutter doctor to confirm that Flutter has located my installation of Android Studio.

**Step 2-Setting up my Android device**
-To prepare to run and test any Flutter app on an Android device, I needed an Android device running Android 5.0 (API level 21) or higher.
On the device, I Enabled **Developer options** and **USB debugging**.
-Using a USB cable, I plugged my phone into my computer. And authorized the computer to access my device.
In the terminal, I  ran the Flutter devices command to verify that Flutter recognizes my connected Android device.

**Step 3-Set up the Android emulator**
To prepare to run and test my Flutter app on the Android emulator, I enabled virtual machine acceleration on my machine.
I Launched Android Studio, clicked the Device Manager icon, and selected Create Device under the Virtual tab… where I Chose Nexus 5 and X 86_64 images to be emulated
I also selected Hardware - GLES 2.0 to enable hardware acceleration Under Emulated Performance,

After installing all these Flutter tools above I ran the ***flutter doctor --android-licenses*** command which permitted me to use Flutter.

**Additional Windows requirements**

For Windows desktop development, from research, I needed to install Visual Studio 2022 or Visual Studio Build Tools 2022. Which has the “Desktop development with C++” workload installed for building Windows, 
including all of its default components.
On the official [Visual Studio 2022](https://visualstudio.microsoft.com/downloads/) site I downloaded and installed Visual Studio with all its dependencies.

### IDE
The IDE I choose to install is Visual Studio Code. VS Code has support for debugging, syntax highlighting, intelligent code completion, snippets, code refactoring, and embedded Git.
* I first downloaded from the official [Visual Studio Code](https://code.visualstudio.com) site.
* After which I ran the installation file. 
* The following images show the steps for the successful installation of Vs code.
  
![Capture](https://github.com/falyne/Outreachy-Applicants/assets/19360782/e3168c29-c463-4a52-952b-92271ee0feac)

![Capture1](https://github.com/falyne/Outreachy-Applicants/assets/19360782/24c1a950-09da-439b-a816-b7cf0a6f923b)

![Capture4](https://github.com/falyne/Outreachy-Applicants/assets/19360782/225d4ee0-7e6d-4bb7-854e-3281fc42a0ea)

![Capture5](https://github.com/falyne/Outreachy-Applicants/assets/19360782/c00f0f90-9e33-4672-b0bd-c1bd2219bbbb)


# 2-Clone the "December 2023 to March 2024 Applicants" repository to your profile
* The first step I took to clone the Mboalab Repository was that i navigate to the Mboalab repository at [Mboalab](https://github.com/Mboalab/Outreachy-Applicants/tree/main/December%202023%20to%20March%202024%20Applicants)
* Then I forked the repository using the Fork icon and input a name(I maintained the name) and description of how I wish to store the forked repo
* When i navigate to my Repository  I find the Repo listed there

![forked-repo](https://github.com/falyne/Outreachy-Applicants/assets/19360782/637cd65d-7f83-4043-9f6a-86e9c82f475b)

*To clone to my local system, I copy the link to the forked repository in my account and use the ***git clone*** command

![github-vscopylink](https://github.com/falyne/Outreachy-Applicants/assets/19360782/254fb844-0057-43d5-bdc5-c4db8f905a2f)


![git-clone2](https://github.com/falyne/Outreachy-Applicants/assets/19360782/d898f33f-8c5b-46b2-8961-a9baf26ec7e9)

# 3-Install the project from the repository
* To install the project from the repository, I navigated to the [Mboacare](https://github.com/AnishaSingh0118/Mboacare) Repository and copied the link to the project
* I head over to git bash and use the ***git clone*** command to clone the project locally to my system.
 

![mboacareclone](https://github.com/falyne/Outreachy-Applicants/assets/19360782/cf095bbc-ff7f-48d7-808e-7e31ad642ab3)
  
* After cloning the project, I launch it on the Visual Studio Code IDE
* I run the command ***flutter pub get*** to download every dependency needed by the project,
* I run the command ***flutter run** after having connected the emulator to my physical system as described during setting up my device section of Flutter installation
* The projects run successfully and the app builds in my system.

![flutter run](https://github.com/falyne/Outreachy-Applicants/assets/19360782/617c9e7e-f588-463b-85d3-541330a3f74a)

![Screenshot_20231012-080817_One UI Home (1)](https://github.com/falyne/Outreachy-Applicants/assets/19360782/7f6bfdfb-6563-4bcb-a75b-b8d75e8068ac)

![Screenshot_20231012-153549](https://github.com/falyne/Outreachy-Applicants/assets/19360782/eeb1bba8-2a20-449c-92e6-9c40febd2613)

![Screenshot_20231012-153454](https://github.com/falyne/Outreachy-Applicants/assets/19360782/88201ca1-e5ee-429a-a6ae-ce73a949da2d)
