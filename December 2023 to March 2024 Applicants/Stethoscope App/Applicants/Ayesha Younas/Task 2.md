Hello @ruqaiyasattar 

Finally, after a lot of research and hard work, I have completed this task and was able to complete this task with the help of the library/framework ```FFmpeg``` 

## what is FFmpeg?

FFmpeg is a free and open-source software project consisting of different libraries and programs for handling video, audio, and other multimedia files and streams
FFmpeg is the leading multimedia framework, able to decode, encode, transcode, mux, demux, stream, filter, and play pretty much anything that humans and machines have created. It supports the most obscure ancient formats up to the cutting edge. No matter if they were designed by some standards committee, the community, or a corporation. It is also highly portable: FFmpeg compiles runs, and passes our testing infrastructure [FATE](http://fate.ffmpeg.org/)

Many famous video editing apps are using this library too.

### I also tried other Flutter libraries like just_audio, flutter sound, record, and many more but I didn't get good output.  So, I did more research and read a lot of blogs about noise reduction techniques that's when I got to know that some people are using the FFmpeg library to reduce noise and I also started to do research on it and after a lot of research, I get to know that FFmpeg is a command line tool and there are a lot of commands and I just have to find the right command for it. and started working on the commands. The work itself wasn't difficult in fact it was very time consuming due to finding the right command with the right parameters. That's why it took me so much time to submit the PR.

## List of all FFmpeg commands
https://gist.github.com/tayvano/6e2d456a9897f55025e25035478a3a50

So after some research, I finally found the right command and tried it with our project and I did find out that the bg noise has been removed :) and the result was awesome. like 90 - 95% bg noise was removed. 

## Here is the command that finally works

```./ffmpeg -i temp/noisy_speech.wav -af "asplit[a][b],[a]adelay=32S|32S[a],[b][a]anlms=order=128:leakage=0.0005:mu=.5:out_mode=o" anlms.wav```

## Recordings of before and after

# Before Using the FFmpeg library
 https://user-images.githubusercontent.com/66265841/277624910-9a188830-3506-48af-9f81-96010bfac861.mp4     

# After Using the FFmpeg library
https://user-images.githubusercontent.com/66265841/277627545-4c99b910-61d8-4179-bc10-4839b6d9e423.mp4  


you will notice in the first recording there was some bg wind noise(fan wind noise) and after using FFmpeg it was gone. 
After listening to them you will notice Bg Noise has been removed up to 90 - 95% :)

It would be better if you use headphones or Airbuds to feel the difference :) or some good mobile devices will be fine too :)

Looking forward to a review. Feedback is appreciated. if you have any questions or doubts please do let me know. I will be more than happy to clear your doubts or answer any questions.


