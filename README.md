# Cengo
Cengo is a program that allows users to play any pc video game using their hand signs and movements instead of using mouse and keyboard. It uses OpenCV python script to access the user’s webcam, Mediapipe from Google to recognise hands, color detection for mouse movements and PyAutoGUI library of python to emulate keypresses. The combination of these allows users to play games using hand signs.

Instructions of use- The left hand index finger is used to press and release the W key. Raising it will press W and putting it down will release W. Red marker is used to move the mouse. The left hand thumb is used to emulate mouse left button press. Opening the thumb will click the mouse and closing it will release the mouse button. Clone the respository into your pc on any folder. Run CengoMain and open any game to play.

Big thanks to his tutorials for hand gesture recognition - https://www.youtube.com/c/MurtazasWorkshopRoboticsandAI

Bugs/Known Issues -
1. FPS during some games is very low 
2. Left hand must be shown on webcam first before the right hand, else it will take keyboard inputs from right hand.
