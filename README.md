# Door Lock System using 8051

This project utilizes an 8051 microcontroller to implement a simple door lock system. The system utilizes a LCD to display a prompt for the user to input a 4-digit password. The user inputs the password using a keypad connected to Port 1 of the microcontroller. After entering the password, the system compares it with a predefined password (set as "1234" in this code). If the entered password matches the predefined one, the LCD displays "Correct" and activates a mechanism to unlock the door (assuming digital outputs IN1 and IN2 control the locking mechanism). Otherwise, it displays "Incorrect" and keeps the door locked. The code implements a basic algorithm to handle keypad input and display output on the LCD while controlling the locking mechanism.
