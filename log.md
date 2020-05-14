# 100 Days Of Code - Log

### Day 0: April 12, 2020 
##### Learning how to work with TinyML

**Today's Progress**: Worked on Colab code for the helloworld TinyML project for Arduino

**Thoughts:**  

**Link to work:** [Cosine App](https://github.com/donwardpeng/tiny_ml_cosine)

### Day 1: April 13, 2020 
##### Learning how to work with TinyML

**Today's Progress**: Retrained the helloworld Colab to model a cosine function instead of a sine function. Next steps - dig through the C++ code to use this model instead of the sine function on an Arduino.

**Thoughts:** I learned more about quantization and how it impacts the size of a model. Additionally I learned the steps needed to use with the TensorFlow to convert it to a TensorFlow Lite model for use on microcontrollers. 

**Link to work:** [Cosine App](https://github.com/donwardpeng/tiny_ml_cosine)

### Day 2: April 14, 2020 
##### Learning how to work with TinyML

**Today's Progress**: Detour for the day - worked through the Arduino's Gesture TensorFlow lab to train a ML model to detect various gestures.

**Thoughts:** Playing around with the various IDE's for Arduino, I have yet to find a good solution with Intellisense. 

**Link to work:** [Cosine App](https://github.com/donwardpeng/tiny_ml_cosine)

### Day 3: April 16, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Working with CLion from Jetbrains to get through the Arduino C code to run my cosine model.

**Thoughts:** Since I am picky about my IDE, I am learning alot about the Arduino ecosystem as well as how the TensorFlow interpreter works on microcontrollers.

**Link to work:** [Cosine App](https://github.com/donwardpeng/tiny_ml_cosine)

### Day 4: April 17, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Spent part of my hour today getting CLion configured and orienting myself with the Arduino development workflow using it. Also contrasted how the TensorFlow project lays out project files to support multiple processors vs how the Arduino team does it.

**Link to work:** [Cosine App](https://github.com/donwardpeng/tiny_ml_cosine)

### Day 5: April 18, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Got CLion setup with PlatformIO so that I can work with all of the Arduino libraries and code in one C++ file. Also got the serial debugger running and started a new project with it all in place.

**Thoughts:** Finally in a place where I can dig into creating and modifying the codebases provided to train a ML model for my purposes. 

**Link to work:** [Cosine App](https://github.com/donwardpeng/tiny_ml_cosine)

### Day 6: April 20, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Got my cosine test model to run on the Arduino in CLion. Took a bit of selective copy and paste from the Arduino IDE in CLion as well as some modifications to get it to work with platform.io.

**Thoughts:** CLion and Platform.io seem to integrate well, and the overall workflow is fairly straightforward.

**Link to work:** [Cosine Test App](https://github.com/donwardpeng/cosine_test)

### Day 7: April 21, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Tried something more difficult - adapting the micro speech example for Arduino to be used in CLion and PlatformIO. Still need some work to figure out what is not working - as well as need to figure out how to debug this. 

**Thoughts:** CLion brings IntelliSense to the table as an IDE, something that the Arduino IDE does not support. Need to figure out what 'behind the scenes' magic is taking place with the Arduino TensorFlow Lite examples that they all work with the Arduino IDE and not CLion. 

**Link to work:** [Arduino_Microspeech](https://github.com/donwardpeng/arduino_microspeech)

### Day 8: April 23, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Moved over to VS Code with PlatformIO. It seems to work much better and Intellisense works. Still working on getting my micro speech model to run.
 
**Thoughts:** Interesting how much more useful the VS Code PlatformIO plugin over the Arduino plugin from Microsoft. 

**Link to work:** [Arduino_Microspeech](https://github.com/donwardpeng/arduino_microspeech)

### Day 9: April 26, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Took a quick refresher course on C++ and header files to try and debug issues with my Arduino dependencies. Fully moved over to VSCode now.  

**Thoughts:** Need to get back on course with daily work on this. 

**Link to work:** [Arduino_Microspeech](https://github.com/donwardpeng/arduino_microspeech)

### Day 10: April 27, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Properly setup all of my libraries in the project - not drawing from all of the my computer. Debugging why the Arduino sketch I am using seems to be becoming unresponsive soon after start (or at least it is acting like it).

**Thoughts:** First debugging opportunity for me using an Arduino - this is where real skills are built.  

**Link to work:** [Arduino_Microspeech](https://github.com/donwardpeng/arduino_microspeech)

### Day 11: April 29, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Made some progress with the TensorFlow Micro Speech example code. 

Switching back to the TensorFlow motion classification since I think it will be beneficial to understand the TensorFlow Lite code there before going back to a more difficult code base. 

**Thoughts:** Sometimes you have to take a step back to move forward. I think I totally messed up my project, and do not really know how to get it back to a working state. 

**Link to work:** [Arduino_Microspeech](https://github.com/donwardpeng/arduino_microspeech)

### Day 12: May 2, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Started a new project using PlatformIO with the Gesture Classification Tensorflow Lite example. Retrained the model and got it all working - now to start tinkering with the code.

**Thoughts:** This has been a hard week to move this forward - I wrote an AWS Cert and this project suffered for it - there are only so many hours in the day :) 

**Link to work:** [Arduino_Gesture_Classifier](https://github.com/donwardpeng/platformio_gesture_classifier)

### Day 13: May 3, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Read the entire codebase for the Gesture Classification example. Dug in and researched the accelerometer and gyroscope used - looked up their data sheet and understand how the values are scaled. The ability to marry an IMU with ML on such a small board has a ton of opportunities. 

**Thoughts:** As always, when working with microcontrollers - knowing the hardware and how it operates is super important. It is not just code - knowing the underlying hardware is all part of the equation. 

**Link to work:** [Arduino_Gesture_Classifier](https://github.com/donwardpeng/platformio_gesture_classifier)


### Day 13.5: May 5, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Life happens - only got 1/2 hour in today training new gestures for the Gesture Classifier codebase on Arduino. 

Trying to test out what the effect of training a bunch of simple gestures would be towards recognizing more complex gestures in sequence.

**Link to work:** [Arduino_Gesture_Classifier](https://github.com/donwardpeng/platformio_gesture_classifier)

### Day 14: May 6, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Playing with the different settings for the Gesture Recognition model. Becoming comfortable with the basics of loading a TensorFlow model into memory and inferring with it on an Arduino. 

**Thoughts:** Getting a feel for all of the hardware on the Arduino

**Link to work:** [Arduino_Gesture_Classifier](https://github.com/donwardpeng/platformio_gesture_classifier)

### Day 15: May 7, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Went back to my cosine wave classification and messed with the RGB led. Also continue to learn more complex TensorFlow examples light trigger word detection. 

**Thoughts:** Slowly putting together all of the pieces.

**Link to work:** [Arduino_Gesture_Classifier](https://github.com/donwardpeng/platformio_gesture_classifier)

### Day 16: May 9, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Recorded samples for movement in 2 directions (up/down motion, down/up motion, etc.) and worked on training a model to recognize the directions using a Google Colab built for Gesture Detection. Limited success, as the training error was in the 18% range and the validation error was in the 19% range. 

**Thoughts:** Working to modify the shape of the NN is an art.

**Link to work:** [Arduino_Gesture_Classifier](https://github.com/donwardpeng/platformio_gesture_classifier)

### Day 17: May 11, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Changed my neural network architecture and was able to get my training error down to 2% and validation error down to 3%. 

When running on the Arduino board, side to side motions are classified pretty accurately, but up/down motions are 50-50.   

**Thoughts:** Next steps - refine the sampling of motions - take out the dependence on having 2.5G's of motion to trigger - change it to start based on a digital input. 

**Link to work:** [Arduino_Gesture_Classifier](https://github.com/donwardpeng/platformio_gesture_classifier)

### Day 18: May 12, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Doing some research into how to wire up a button for gesture capture and soldiering the entire Arduino together for it.  

**Thoughts:** Mostly hardware today.

**Link to work:** [Arduino_Gesture_Classifier](https://github.com/donwardpeng/platformio_gesture_classifier)

### Day 19: May 13, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Coded up a gesture capture sketch to be triggered from a push button and to use an LED to display when recording. My plan is to use this to capture more gestures more accurately in the coming days. Also - dusted off the old soldiering iron - need to soldier my Arduino to some pins. 

**Thoughts:** A lot of the Arduino TensorFlow libraries are fairly pre-canned - not changing the code for them much yet.

**Link to work:** [Arduino Gesture Capture](https://github.com/donwardpeng/platformio_gesture_capture_with_button)
