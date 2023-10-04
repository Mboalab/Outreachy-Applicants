# Setting up environment

### Create Github account and Install Git

Git is a free and open source software created by Linus Torvalds in 2005. This tool is a version control system that was initially developed to work with several developers on the Linux kernel.

Version control is a management system that takes into consideration modifications you’ve made on a file or a set of files (example: a code project). With this system, developers can collaborate and work together on the same project.

### Account Creation in GitHub

- Go to the github main page [Main Page](https://github.com/) and create an account there by filling the required information in form.

### Installing Git

Different Operating system have their different ways in installing Git. Here i used Windows for installing and setting git in my system. Note we have but the Graphical (GUI) and command line Interface for Git installation.

#### Installing Git on Windows (GUI)

- Go to [Git Main site](https://gitforwindows.org/), download and install the executable file.
- Follow the instructions on the main site.

Checkout my medium content on full guides to Git and Github, creating your first repository, and first commit. [A beginner’s guide to Git](https://nyonggodwill11.medium.com/a-beginners-guide-to-git-how-to-start-and-create-your-first-repository-19fb630728eb)

### Installing IDE

There are many Code IDE online that we can used for Mobile app development such as:

- Visual Studio [Download and get started here!](https://code.visualstudio.com/)
- Android studio [Download and get started here!](https://developer.android.com/studio?gclid=Cj0KCQjw1OmoBhDXARIsAAAYGSGaI1RIDR6XyVrQSS2QGWzNjipcB-IxBnGPiOjMomorkOYbhUSjgksaAsCgEALw_wcB&gclsrc=aw.ds)
- Codemagic [Download and get started here!](https://codemagic.io/start/)
- IntelliJ Idea [Download and get started here!](https://www.jetbrains.com/idea/)
- Atom [Download and get started here!](https://github.com/atom)

Check out my medium content on the top flutter IDE use today to make flutter development faster and easy [Top Flutter IDEs](https://medium.com/@nyonggodwill11/top-5-ides-to-develop-a-flutter-app-c0110a98b948).

#### Choice of IDE and why

Below are the step by step guide to install Visual studio code. I choose visual studio over others because first it is light weight, it is popular, and Flutter extension can be installed from the Extension section, along with the Dart plugin.

- Open any browser of your choice download and install IDE [here!](https://code.visualstudio.com/).  
- open IDE and look for extension tap, ensure your online.
- Search for flutter, dart and install the extension.

### Installing Flutter and dart

The Flutter and dart documentation helped me a lot to get started both in setting up and installing. You can also get started here [Flutter](https://docs.flutter.dev/get-started/install) and [Dart](https://dart.dev/get-dart).  

- Go to [Flutter main site](https://docs.flutter.dev/get-started/install), select your OS and download the Zip file for the SDK.  

- When completed, Unzip  the file.
- Go to drive C, create a folder and give it any name.
- Copy the unzip folder in to the newly created folder.
- open the folder and look for the bin folder, copy the file path.

![Alt Text](../Task%201/bin.png)

- Go to search bar on you pc, search for environmental variables.

![Alt Text](../Task%201/search.png)

![Alt Text](../Task%201/sys.png)

- click on it and select edit , once open go to path and click to open.

![Alt Text](../Task%201/path.png)

- once open click on add Path and paste the copied flutter bin file path.

![Alt Text](../Task%201/path pas.png)

Installing Dart SDK

- Go to [Dart main site](https://dart.dev/get-dartl), select your OS and download the Zip file for the SDK.
- Same steps as above.

This Youtube link also helped me in setting [Installing Flutter and dart](https://www.youtube.com/watch?v=nkOliNYv59Q).

### Set Up and Install Mboacare Application

- clone the repository using git clone [Mboacare](https://github.com/AnishaSingh0118/Mboacare).  

![Alt Text](../Task%201/clonning.png)

- Open project in IDE here i used VS code.

- Open the terminal of the IDE and run flutter pub get to install all the packages used.

 ![Alt Text](../Task%201/pub%20get.png)

- After getting all the dependencies run flutter run or F5 to install in a local device
  
   ![Alt Text](../Task%201/output.png)
