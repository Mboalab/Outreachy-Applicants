# Mboathoscope Test 

After running the application as detailed in the previous task, I proceded to test Mboathoscope on two devices.

**Testing Device 1 Specifications**
- **Model:**  SM-A047F
- **OS** Android Version 13
- **Display:** Portrait Mode
- **Processor:** Octa-core 4x2.3 GHz Cortex-A53
- **RAM:** 4.0 GB
- **Resolution:** 720 x 1600



This is a [Video Demonstration](https://drive.google.com/file/d/1nPKImEQsPGJbRaXp7o00zXQPHfwTaagM/view?usp=sharing) of testing the Mboathoscope project using the device above.


## Feedback

### Positive Feedback

1. **Login page Design** The animation on top of the email and password fields is good and is relevant to the application. As I could not access other app features as detailed below, I was not able to explore more app features.



### Needs Improvement Feedback

1 - I tested the app on Dark mode on the Android Device and the app theme did not change. The splash screen was stil white and the app theme was still on light mode. 

2 - After launching the app and getting navigated to the Login page, I clicked on register in order to create an account. 
Here are some notes on the page.
- The register form has no validation as demonstrated in the video above. there is no limit to the number of characters one can put
 in a field, or validation of correct input on the fields for name and email address.

- The gender field requires text input which is not a good user experience as the user should be allower to choose the gender from i.e a drop down selection box.

- There is also no validation and authentication of the hone nmber and no details provided for the phone number format required.

- For the login button, the Login name is mispelled.

3 - Upon clicking the register button, no action happened and there was no details provided as to why the register action did not happen.

<table>
  <tr>
    <td><a href="https://postimg.cc/Jtm788NV"><img src="https://github.com/veekamunya/veekamunya/assets/114191508/921f2028-07a2-4dd0-82de-f746fe1cb9a6" alt="flutter-01.png"></a></td>
    <td><a href="https://postimg.cc/qhckKDd5"><img src="https://github.com/veekamunya/veekamunya/assets/114191508/d797be6f-1740-451e-a354-8eed19a129e8" alt="flutter-02.png"></a></td>
    <td><a href="https://postimg.cc/xkzjfTpY"><img src="https://github.com/veekamunya/veekamunya/assets/114191508/8cd891d0-2f9d-4356-bab8-6ed57c417f21" alt="flutter-03.png"></a></td>
  </tr>
</table>


## Second Test

I was therefore unable to test the rest of the application beyond the register and login page. 
I therefore looked at the codebase and switched the navigation route from the Login page to the Homepage to bypass the required user credentials.

I repeated the test on a simulator to verify the results above as shown below.

[Video Demonstration](https://drive.google.com/file/d/1LKjVjuRnOZZgNz3kg-qpX7VlYg1PUvav/view?usp=sharing)

I also switched the route from the login page to the role page so I could explore thr role page and here are the results.

[Video Demonstration](https://drive.google.com/file/d/1q4MIQo7bNL09yNh3hrBJwGLpAZ5v0O0l/view?usp=sharing)



**Testing Device 1 Specifications**
-Emulated device
- **Model:**  sdk_gphone64_arm64
- **OS** Android Version 12
- **Display:** Portrait Mode
- **RAM:** 4.0 GB

### Second test results

Upon switching the routes I was able to explore the app in depth by navigating to various pages and testing the recording function.



### Feedback

- On the bottom navigation tab, the second and third tabs were empty and I made the assumption that they shold be populated by user information that was not available after bypassing registration.

- The design elements are cohesive with the app function and theme.

### Final Notes
 I am looking forward to further explore the full functions with the registration function in place.







