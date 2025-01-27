# Deauthentication-Packet-Detector
This is the code for the Deauthentication Packet Detector. When the device is powered on  a green light turns on. Whenever a Deauthentication packet is detected the green light will turn off and then the red light turns on. This device was made as a DOS / DDOS detector. If a DOS / DDOS attack is happening then the red light will stay on.

In the video I am doing a targeted Deauthentication attack to my router with my M5Stick by M5Stack with the Bruce firmware installed. Bruce is a firmware for pentesting and red teaming. It sends out 1000's of Deauthentication packets in seconds. I am playing and pausing the attack so that you can see that the light turns red when the attack is in progress and turns back to green when paused. I censored the screen for privacy.

https://github.com/user-attachments/assets/9605f28d-32c0-4835-b36d-199336b3418f

Supplies Needed:

1x ESP32-WROOM-32

2x LEDs (One Green and the other Red)

2x Resistors

2x Mini breadboards or 1x Big breadboard (Either one will work. It's up to your preference)

Arduino IDE

![1](https://github.com/user-attachments/assets/0dab012f-671e-4efb-ba2f-e4e7537449a1)

![2](https://github.com/user-attachments/assets/169a3891-643f-4fca-9d8a-832b0425f5ec)

