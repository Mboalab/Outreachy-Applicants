# Setup of my development environment and installation of the project

## Git setup

- I downloaded Git for Windows from [the official website](https://git-scm.com/downloads), and installed it. 

## Fork Mboacare repository

- I then logged into my GitHub account and visited the [Mboacare](https://github.com/AnishaSingh0118/Mboacare) repository and forked the Mboacare repository.

    ![Forking the Mboacare repository](images/Forking%20the%20repo.png "Forking the Mboacare repository")

## Clone the forked repository locally
- I copied the HTTPS URL of the forked repository from my GitHub account.

    ![Cloning the repo](images/cloning.png "Cloning the repo")

- I cloned the repository locally using Git Bash.

    ![Cloning the repo locally](images/Cloning%20the%20project%20locally.png "Cloning the repo locally")


## Install and setup Android Studio and Flutter

- I downloaded Android Studio from the [offial android website](https://developer.android.com/studio?gclid=CjwKCAjwvfmoBhAwEiwAG2tqzPSBGL2o50FfuvpKd7CuUvzMreZur3MLNVRO3zq8bn9FY-pM-cK_HxoC3QcQAvD_BwE&gclsrc=aw.ds)
- I then installed Android Studio.

- I Installed the Flutter and dart plugins from Android Studio plugins.

    ![Flutter and dart plugins installation](images/flutter%20and%20dart%20plugins.png "Flutter and dart plugins installation")

- I downloaded the Flutter SDK from the Flutter website and set it up.

    ![Flutter SDK setup](images/flutter%20sdk%20setup.png "Flutter SDK setup")

## Install dependencies and run the app

- I opened the project in Android Studio

    ![Mboacare Project in Android Studio](images/opened%20project.png "Mboacare Project in Android Studio")

- I installed the dependencies of the project using the code below

    $ `flutter pub get`

    ![Installing dependencies](images/flutter%20pub%20get.png "Installing dependencies")

    ![Installing dependencies](images/ran%20flutter%20pub%20get.png "Installing dependencies")

- To run the Application, I enabled Developer Mode on my physical Android device and enabled USB Debugging.

    ![Enable usb degugging](images/usb%20debugging.jpg "Enable usb degugging")

- With the Mboacare project open, I then connected the device to my computer and selected it from the devices dropdown as shown below.

![Select device to run](images/select%20device.png "Select device to run")

- Then I ran the application

    ![Run application](images/run%20app.png "Run application")
    ![Run application](images/running%20the%20code.png "Run application")

### Below are a few images of the application running

  ![Application running](images/home.jpg "Application running")
    
  ![Application running](images/settings.jpg "Application running")


