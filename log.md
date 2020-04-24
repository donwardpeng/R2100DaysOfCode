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

### Day 8: April 22, 2020 
##### Learning how to work with TinyML

**Today's Progress:** Moved over to VS Code with PlatformIO. It seems to work much better and Intellisense works. Still working on getting my micro speech model to run.
 
**Thoughts:** Interesting how much more useful the VS Code PlatformIO plugin over the Arduino plugin from Microsoft. 

**Link to work:** [Arduino_Microspeech](https://github.com/donwardpeng/arduino_microspeech)
