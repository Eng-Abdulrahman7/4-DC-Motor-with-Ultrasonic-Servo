# 4-DC-Motor-with-Ultrasonic-Servo
This project is a simulation of a 4-DC motor robot using L293D motor driver, Ultrasonic sensor (HC-SR04), and Servo motor.

📌 Description

This project is a simulation of a 4-DC motor robot using L293D motor driver, Ultrasonic sensor (HC-SR04), and Servo motor. The robot moves in multiple directions and avoids obstacles intelligently by scanning surroundings using a servo-mounted distance sensor. It is built and tested using TinkerCAD.

⸻

🧠 Features
	•	🟢 Moves forward for 30 seconds
	•	🔴 Moves backward for 60 seconds
	•	🔁 Alternates between left and right turns for 60 seconds
	•	🚫 Stops and avoids obstacle if anything is detected within 10 cm
	•	🔄 Servo scans left and right to find an open path
	•	🔵 Visual feedback with LEDs indicating direction:
	•	Green = Forward
	•	Red = Backward
	•	Blue = Right turn
	•	Yellow = Left turn

⸻

🛠 Components Used
	•	Arduino Uno
	•	4x DC Motors
	•	L293D Motor Driver IC
	•	HC-SR04 Ultrasonic Distance Sensor
	•	1x Servo Motor (SG90 or equivalent)
	•	4x LEDs (Green, Red, Blue, Yellow)
	•	Breadboard & Jumper Wires
	•	TinkerCAD for simulation

 | Component              | Arduino Pin |
|------------------------|-------------|
| IN1 (Right Motor)      | 8           |
| IN2 (Right Motor)      | 7           |
| IN3 (Left Motor)       | 5           |
| IN4 (Left Motor)       | 4           |
| Trig (Ultrasonic)      | 12          |
| Echo (Ultrasonic)      | 11          |
| Servo Motor            | 6           |
| LED - Forward (Green)  | 2           |
| LED - Backward (Red)   | 3           |
| LED - Right (Blue)     | A2          |
| LED - Left (Yellow)    | A3          |

🧾 How It Works
	1.	Robot starts by moving forward for 30 seconds.
	2.	Then moves backward for 60 seconds.
	3.	Then alternates left and right turns for 60 seconds.
	4.	During all movements, it constantly checks the distance ahead.
	5.	If an obstacle is within 10 cm:
	•	It stops.

 🖼 Circuit Screenshot

 



 📋 Task Requirements (As per Presentation)
	•	✅ Program 4 DC motors using L293D.
	•	✅ Implement forward/backward/right-left alternation.
	•	✅ Control servo motor and stop motion if an object is detected at 10cm.
	•	✅ Use LEDs for direction indication.

⸻

🔗 Tools & Simulation Platforms
	•	TinkerCAD
	•	WOKWI (optional)
	•	PROTEUS (optional)
