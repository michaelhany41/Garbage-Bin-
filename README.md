# Garbage-Bin-
This project showcases an automated garbage handling system using pneumatic cylinders, sensors, and relay-based control. The system detects garbage, pushes it into a crushing chamber, compresses it, and then disposes of it into a bin — all in a fully automated sequence.

⚙️ How It Works

Detection: Two photocell sensors detect incoming garbage.

Push to Crusher: Cylinder 1 pushes the garbage into the crushing chamber.

Crushing: Cylinder 2 compresses the garbage.

Disposal: Cylinder 3 ejects the compacted waste into a bin.

🛠️ Components

3 Pneumatic Cylinders

11 Relays

6 Reed Switches (2 per cylinder for position feedback)

2 Photocell Sensors

Solenoid Valves

Power Supply & Relay Logic

🧠 Control Logic

The system uses reed switches and relays to manage the sequence and ensure each cylinder operates only when safe. Relays control solenoids based on sensor input, enabling fully automated, reliable operation without a microcontroller.

📦 Applications

Ideal for educational automation demos, small-scale prototyping of waste management systems, or learning electropneumatics and sensor integration.
