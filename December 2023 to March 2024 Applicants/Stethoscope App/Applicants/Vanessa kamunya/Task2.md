## Noise Reduction Techniques for Noise reduction in Audio Recordings

Noise reduction is a specialized field that often involves complex signal processsing algorithms that are not readily available in standard Flutter packages.

## Research

I researched different techniques and libraries for audio processing to be able to cancel out background noise to preserve heart and lung sounds and here are some libraries that I came across:


+ [RNNoise](https://github.com/xiph/rnnoise)
+ [Web RTC](https://pub.dev/packages/flutter_webrtc)
+ [flutter_ffmpeg](https://pub.dev/documentation/flutter_ffmpeg/latest/)
+ [Record](https://pub.dev/packages/record)
+ [Dolbyio_comms_sdk_flutter](https://pub.dev/packages/dolbyio_comms_sdk_flutter)
+ [flutter_sound](https://pub.dev/packages/flutter_sound) 

Libraries like RNNoise which is a Recurrent neural network, do not have Flutter implementations and to use them in the app I would need to compile the C library and then bridge it to flutter using platform channels which was a complex understaking give the time constraints. I was also unable to use web rtc as it was incompatible with the Mboathoscope project due to its dependencies.

I decided to use the [Record](https://pub.dev/packages/record) library since it provided built-in noide reduction capabilities for audio recordings. This means that the audio is processed for noise reduction during the recording. 


Below is the implementation of the Record library.

I added the record library dependency and ran flutter pub get.

<img width="263" alt="Screenshot 2023-10-29 at 17 53 56" src="https://github.com/veekamunya/veekamunya/assets/114191508/741da09f-9314-493b-ac78-8050f88772eb">

I created the folder noise_recoding with files that contain the implementation noise and echo reduction from the Record library 

<img width="387" alt="Screenshot 2023-10-29 at 17 55 51" src="https://github.com/veekamunya/veekamunya/assets/114191508/6a916873-cdaa-49a8-9d09-9ddbc66dd177">

New audio player implementation

<img width="1109" alt="Screenshot 2023-10-29 at 17 56 38" src="https://github.com/veekamunya/veekamunya/assets/114191508/06fa2822-4d7c-4ced-98ef-a43c009676b4">

### Current audio recording quality

![Alt text](images/image-50.png)


https://github.com/veekamunya/veekamunya/assets/114191508/6e4ac15b-e156-4b7c-8231-0c575d8c4402


### Audio recording with the Record library

![Alt text](images/image-40.png)


https://github.com/veekamunya/veekamunya/assets/114191508/bd9f6284-ec8f-4331-afd6-afcbdf042d9c

There was no need for the implementation of a storage mechanism to save the recorded heart to lung sounds since the project currently saves the audio files to a local application directory.












