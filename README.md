# Color-Sequence-Trainer
An interactive color memory game using Arduino UNO with four LEDs, buttons, and a buzzer. Players replicate color sequences displayed by LEDs, testing and improving their memory and focus skills in a fun and engaging way.

# Materials Required
1. Aruino Uno - 1

2. Passive Buzzer - 1

3. Led - 4

4. Button Switch - 4

5. Resistor(220 ohm) - 4

6. Jumper wires

# Procedure

Step 1: Gather all required components including Arduino UNO, 4 LEDs, 4 push buttons, resistors, breadboard, and jumper wires.

Step 2: Connect the LEDs to the Arduino digital pins with current-limiting resistors, ensuring the cathodes are grounded.

Step 3: Connect the push buttons to separate Arduino digital pins with pull-down resistors, wiring the other side to ground.

Step 4: Power the breadboard with Arduino’s 5V and GND pins.

Step 5: Write or upload the memory game code to the Arduino using the Arduino IDE.

Step 6: Power the Arduino to start the game; the LEDs will display a random sequence.

Step 7: Press the buttons matching the LED sequence in the exact order shown.

Step 8: The Arduino compares button inputs to the sequence and confirms correctness.

Step 9: If the sequence is correct, the length increases and the next round begins.

Step 10: If incorrect, the game signals failure using LED flashes or buzzer sounds and resets.

Step 11: Repeat gameplay, aiming to remember longer sequences for a higher challenge.

Contributing:

We welcome contributions to this project! If you have suggestions, improvements, or bug fixes, please submit a pull request. You're also encouraged to open issues for discussions or to propose new features.
