# HardwareFinalExam

Components: The first component I created was the base of the controller. I wanted it to look like one of the ghosts in Pac-man to give more immersion to the player. The inside is shelled out in order to fit the components inside. Inside is a breadboard, arduino, IMU, and a vibration motor all on the bottom of the base. On the edges of the base there are holes that are there so that the lid can fit on and be able to stay put on the controller. This also simulates where screws would be put into the base to fully close the lid onto the base. The lid itself was created based on the shape of the base, it has pegs that go out from the bottom that stick into the holes of the base. There are also holes cut into the lid where the ghosts eyes would normally be. This is where the buttons are located on the controller. 


Assembly: The controller is assembled in a simple but effective way. The necessary components to make the controller work are all inside of the controller. The buttons are placed on columns in the base of the controller to allow for them to be sticking out through the lid in order for the user to push the buttons and have them remain in the same place. The arduino and the IMU are both connected directly to the breadboard which is stuck to the base of the controller. The vibration motor is also stuck to the base of the controller so that the user can feel the vibrations properly. This is wired into the breadboard as well inside the controller along with the buttons.


TinkerCAD: The way that the controller works is, in order to move the ghost and change its direction, you must tilt the controller either horizontally or vertically. For example if you tilt the controller to the left, the ghost will begin to move to the left. Next is the buttons, one of the buttons allows the ghost to perform a jump. This means that they can go over a wall that they are facing towards. The other button is to allow the ghost to dash. This will increase the ghosts speed for the duration of the button being held down. Finally, the vibration motor is there to provide haptic feedback to the user when they press a button. When jumping or dashing the controller will begin to vibrate to indicate that the button was successfully pushed. There is no feedback for the IMU sensor as the only feedback necessary is to be able to see the ghost moving and changing direction in the game, which will happen when they play. The other parts of the circuit are there in order to make the circuit function properly. The transistor allows the vibration motor to be able to be turned on and off. The resistors allow for the buttons to be pushed without breaking the circuit. Finally, the breadboard and arduino are there to connect all the components together and actually have it function as it is supposed to function. In the serial monitor it shows what would be happening in game. For example, the potentiometers represent the IMU tilt and the monitor displays which direction the ghost is moving at any given time based on the potentiometer input. Along with the vibration motor vibrating, the serial monitor also displays a message whenever you press the jump or dash buttons.


LINKS:

TinkerCAD: https://www.tinkercad.com/things/e412a72cV22-mighty-gaaris/editel?sharecode=lepCeveym4-xBSwixISHO4HRdNIFLXgGD_ASI_dB9sU

