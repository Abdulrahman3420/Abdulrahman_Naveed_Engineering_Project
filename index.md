# Phone Application Controlled Robotic Arm
This project is the Phone Controlled Robotic Arm which is controlled through an android application made on the MIT App Inventor.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Abdulrahman Naveed | Lynbrook High School |  Engineering | Incoming Junior |


![51ZKrvpOYPL _AC_](https://user-images.githubusercontent.com/86128712/125549916-4b7ece2d-1b52-4384-a593-e61b0abe1878.jpg)
  
# Final Milestone

[![Milestone3](https://res.cloudinary.com/marcomontalbano/image/upload/v1626241574/video_to_markdown/images/youtube--H8Z_oucKwi8-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/H8Z_oucKwi8 "Milestone3")

My final milestone was adding finishing touches to my android application, adding the HC-SR04 sensor as a modification, and fixing any bugs that I encountered as I was finishing my project. For my application, I made sure that all of the slides were working correctly and were corresponiding to their respective servo motors. In addition, I made sure the bluetooth connection consistently worked correctly between my application and the ESP32 by fixing the circuit wiring as well as bugs on the code itself. Although I added the HC-SR04 sensor before, I made modifictions where it would work seamlesslely with the application and control the robotic arm using the code. One challenge that I faced while completing my project was that my ultrasonic sensor was not working correctly when I connected it to the ESP32 but it was working when I connected it to the Arduino Uno board. When I connected it to the ESP32 it was not printing the correct distance values. In order to fix this, I went to the code and realized that I had to change some parts and libraries of the code because it was not exactly the same for both the ESP32 and the Arduino Uno board. After I tried this I was able to solve the problem.


# Second Milestone

My second milestone was creating the code and the design of my android app as well as getting the bluetooth to work with the ESP32. For the application, I worked on the MIT App Developer and designed the outline for the app. The app contains four slides to control the four servo motors on the robotic arm. It also contains a connect and disconnect button to link the bluetooth from the ESP32 to the application. In addition, it also contains a RUN and RESET button. THe RUN buttons starts the process of moving the servo motors, and the RESET button moves the servos back to their origional poistion. In order to connect the ESP32, the first thing I had to do was to download an external VCP Driver so that my ESP32 would connect to the Andriod IDE. After I got it to work, I then downloaded the ESP32 servo library onto the Arduino IDE which I can now use to send the signals from the ESP32 to the Robotic Arm.

[![Milestone2](https://res.cloudinary.com/marcomontalbano/image/upload/v1626241940/video_to_markdown/images/youtube--dsRG7XeRAvc-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/dsRG7XeRAvc "Milestone2")

![MIT App Developer Design]<img width="1280" alt="Screen Shot 2021-06-27 at 12 02 17 PM" src="https://user-images.githubusercontent.com/86128712/125555403-42919ea2-8cc8-4965-a0a4-f29955a83c1b.png">


# First Milestone

My first milestone was learning the basics about the Arduino, the Arduino IDE, as well as the connecting the servo motors. After I got the basics done, I finished duiilding the physical components for the Robotic Arm and connected the servos to the Arduino Uno board. During the process of building the robotic arm, I did not run into a lot of difficulties, however, when I was wiring the servos onto the breadboard, I short-circuited the Arduino. After a lot of trial and error, I was finally able to wire and connect them correctly to the arduino. In addition, I also added an HC-SR04 sensor onto the robotic arm such that it can detects objects that are a certian distance away from it and then pick it up.   

[![Milestone1](https://res.cloudinary.com/marcomontalbano/image/upload/v1626242209/video_to_markdown/images/youtube--PHHgylYHB78-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/PHHgylYHB78 "Milestone1")
