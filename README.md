# Servo Motor Angle Sweep using Arduino

This project demonstrates basic control of a servo motor using an Arduino board. The servo is programmed to rotate sequentially between 0°, 90°, and 180°, pausing for 1 second at each position.

## 🛠️ Hardware Required

- Arduino Uno (or compatible board)
- Servo Motor (e.g., SG90 or MG90S)
- Jumper Wires
- Power Source (USB or battery)

## 🔌 Circuit Connections

| Servo Wire | Connects To       |
|------------|-------------------|
| Red        | 5V (Arduino)      |
| Brown/Black| GND (Arduino)     |
| Orange/Yellow | Pin 9 (Arduino) |

Make sure your servo's power source can provide enough current. For high-power servos, consider using an external power supply.

## 🧠 Code Explanation

The servo motor is controlled using the built-in `Servo` library. It rotates to:

- **0°**, then waits for 1 second
- **90°**, then waits for 1 second
- **180°**, then waits for 1 second

This sequence repeats indefinitely.


