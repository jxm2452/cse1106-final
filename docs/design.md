I used the original code as the foundation for my new system, keeping the same GPIO initialization, output pin (GPIO 17), and LED control commands (gpioWrite). 
I expanded the original design by changing the fixed ON/OFF commands into conditional controls, using temperature values as inputs to determine when the LED should turn on or off. 
I also introduced a continuous while loop and if-else statements, allowing the system to repeatedly monitor temperature readings and automatically control the warning LED rather than relying on manual input.
