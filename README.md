# Professor Puddles
1st place winners for Hack the 6ix 2023.

Professor Puddles is a duck-shaped desk buddy that is equipped with a camera, water gun, and speaker. To use Professor Puddles, the user simply has to run our provided code, which will launch our posture-detecting program. Using both the front camera of the laptop and the side camera angle provided by Professor Puddles, our program keeps track of the user’s posture from various angles. If either camera detects bad posture the user receives an initial warning in the form of a notification on their laptop. If the bad posture continues, the consequences intensify. After 15 minutes of bad posture, Professor Puddles will verbally abuse notify the user that their posture is poor. 15 minutes after that if you ignore his final warning, he loses it and spits at you. Surely when you are getting wet you will fix your posture, right?

The Python program uses OpenCV to track various points on the user's body and detects when these points exceed standard sitting proportions and sends desktop notifications. The user can view the tracking live and create custom profiles for better accuracy with one click in our Tkinter user interface. In the case you ignore the messages, Professor Puddles is running a server on a Raspberry Pi that the computer connects to wirelessly via socket connection. When it sends the message over this connection saying that you have been a naughty boy or girl and haven't been taking your posture seriously, Puddles gets mad and uses his Python codebase to play sounds and control the servo motor that has been integrated with the parts of a dissected water gun.


Demo video: https://www.youtube.com/watch?v=pyZHgDcofTw
