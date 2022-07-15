# Esp32-Cam-Module-For-Door-Safety-With-Notification-

In this ESP32CAM project, we will make a DIY Home surveillance system with ESP32 CAM, PIR motion sensor by using telegram app. If any motion detected by PIR sensor, the ESP32-CAM Motion Sensor Security Camera will send a notification to smartphone with the photo.
Need of this project - Security has been a very significant concern in human society. Ensuring safety of people and their valuable things is very important for the prevention of illegal handling. Providing a security system for houses has become a vital research in which the latest technologies are being adopted to serve this purpose. Wireless network is one of the technologies that have been used to provide remote monitor and control for the home doors or gates, wireless security based applications have rapidly increased due to the dramatic improvement of modern technologies. Many access control systems were designed and implemented based on different types of wireless communication technologies by different people.  
 
Working of the project - We will mainly do this project with the help of Telegram app. After the Telegram app setup we have tested the circuit. Supply 5V DC to this security camera circuit and connect your smartphone with the same Wi-Fi network. Now if the PIR sensor detects any motion, you should get a notification on the mobile phone. After any motion gets detected by motion sensor the security camera module which is ESP32 will capture the photo and send it to the telegram using developed bot.

Programming of ESP32 - To program the ESP32CAM, we have used FTDI232 USB to Serial interface board. We have connected the FTDI232 with ESP32CAM as per the above circuit.
While uploading the code we have to connect GPIO 0 with the GND pin of ESP32CAM.

Creating a bot on telegram - 
Necessity of bot : The bot is useful for getting an image over a telegram app. Due to use of telegram we can get the picture of person over a wide range.
Creation of bot : over a telegram there are few bots are available which are useful for creation of a bot. After getting the ID’s of a bot we have to paste that ID in the Arduino code so that we can get the image over a telegram via bot.

Conclusion - Thus our project is used mainly for safety of ourselves. While opening the door it will click our photo. This project will improve your home security using the ESP32 camera module and PIR motion detector. 
