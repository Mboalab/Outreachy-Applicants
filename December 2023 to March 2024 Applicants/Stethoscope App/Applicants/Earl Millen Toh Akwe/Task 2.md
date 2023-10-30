Task 2 completion

So far this has been one of the most challenging task i have encounter so far hence my late contribution to it, but here is the final reasearch and implementation results

## My Approach and summary

So i started off by implementing a local database using sqflite. This is to ensure quick retrival of recordings from phone storage 
no matter if the user is online or offline. I started by creating the model and database functions, folllowed by disconnecting firebase storage from 
the front end and direct uploads and connected it to the local data base only.
My general idea was to connect firebase to the sqflite database and then connect the sqflite database to the front end

Next part involve researching on a suitable library to clear noise from the recordings, and after a lot of research, i implemented
the following: i added a noise meter library, reason being i wanted to track the amount of noise in the audio file before cleaning it,
because the app is going to be use by many users and the intensity of noise is going vary alot with different devices and users, 
so i wanted to vary the intensity to which the noise is filter as to main important data. Next i wrote simple noise cancellation
 algorithm(which is still going to be enhance) to clear the noise in the records, this algorithm is implement with the help of the 
 ffmpeg kit flutter library .

## Research

Here are the variouse recent updated flutter libraries i found that can help with noise cancelation

 - Dolby.io Comms SDK for Flutter: which is relatively the newest update. Dolby.io offers a Flutter SDK that allows you 
to create high-quality applications like for video conferencing. The SDK provides functionalities 
for noise reduction and other audio enhancements. Their documentation contains resources 
to learn more about the latest noise reduction techniques available in 
Flutter .

 - FFmpeg: FFmpeg is a powerful multimedia framework that includes various audio and video
processing capabilities. It provides a wide range of filters and effects, including 
noise reduction. The FFmpeg library can be better explore and intergrated with this Stethoscope
app to leverage advanced noise reduction techniques for audio recordings. Unfortunately i 
didnt have time to fully implement this.

 - Flutter noise_meter package: The noise_meter package is a Flutter plugin that allows 
you to measure noise levels in real-time. While it doesn't directly provide noise 
reduction techniques, it can be used as a tool to analyze and monitor noise levels
in our audio recordings. We can consider using this package in combination with other
noise reduction techniques or librairies like ffmepg to enhance the audio quality.
Here i implented this package in the app hoping to use it results greatly with the ffmpeg library.


## Implementation

So i started by adding the necessary plugins and running pub get 
 ![](https://github.com/akwe-afriitech/Earl-Millen/blob/main/assets/img/LIBRARIES.png)

the plugins were:

sqflite which is use for my local storage inorder to retrive data fast and efficiently.
Noise meter which i used to measure the amount of noise in the recordings
ffmpeg kit flutter which i use to clear the noise in the recordings

Next i created a model for the storage of the recordings to the local database, and also 
wrote the funtions to create, read, write, delete, readall, update and close for the database
![](https://github.com/akwe-afriitech/Earl-Millen/blob/main/assets/img/records%20model.png)
![](https://github.com/akwe-afriitech/Earl-Millen/blob/main/assets/img/database.png)

After these was done i created the display widgets for it, firstly i had to make sure that 
the design stayed consistend as from the UI designs, so i modify the of the 2 sections in 
the home page. I use media queries to ensure the design can suit all devices and fixed 
most hard coded dimension values. I also updated the listview builder for the recordings 
to make it more responsive.


Next i began with the implementations of the noise meter library to measure the amount of noise
 from the audio recordings followed by the implementation of the ffmpeg library to reduce
 the amount of noise in the recordings 
 ![](https://github.com/akwe-afriitech/Earl-Millen/blob/main/assets/img/noise%20cancelation%20algo.png)

At the end, i had made changes to the files:
 - appDirectorySingleton.dart
 - recordingProvidders.dart
 - HomePage.dart
 - RolePage.dart
 - pubspec.yaml

I also created the new following files:
 - homeRecordBtn.dart
 - dbRecordingList.dart
 - records.dart
 - records_database.dart
 ## Results

 After all these, i committed my code to the branch: [link](https://github.com/akwe-afriitech/Outreachy-23-MboaLab/tree/Task-2-done) so you too can also run the app and 
 see the improvements and implementations. 
 Also visible results can be gotten from the video recording below 



https://github.com/akwe-afriitech/Outreachy-Applicants/assets/69284908/1a8da16c-a710-49e0-8280-534e33ea5d40



 Thank you for your time, its was amazing being part of this community, i have learnt alot 
 with regards to working with flutter sound libraries and also with regards to heart and lungs.
 I did a lot of research on the best spots for a stethoscope to get heart beats, the implementation
  methods and so much more. it was all so amazing.
  Looking forward for your feed back and what you think about to approach to solving this problem
![]()
