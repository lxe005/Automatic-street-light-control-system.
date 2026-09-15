Automatic Street Light Control System
Overview:

This project features the design and simulation of an energy-efficient smart street lighting system, developed for a Digital Design & Computer Architecture Lab. By using basic combinational digital logic, the system automates street lights to significantly reduce power consumption while keeping roads safe for drivers and pedestrians.

How It Works:
The system relies on a fast, low-cost logic gate circuit that processes real-time environmental data to control the street lights automatically:

Light Detection (LDR Sensor): Senses whether it is day or night. During daylight hours, the lights remain completely off to prevent wasted energy.

Motion Detection (PIR Sensor): Senses approaching vehicles or pedestrians. At night, when the road is empty, the lights stay in a 30% dim energy-saving standby mode. The moment motion is detected, they instantly switch to 100% full brightness.

Manual Override: A dedicated switch allows maintenance crews to force the lights to full power at any time, bypassing the sensors.

Performance & Impact:
Successfully simulated and verified in Logisim, this system demonstrates how basic digital logic can drive real-world sustainability. Key benefits include:

Massive Energy Savings: Achieves 0% energy consumption during the day and approximately 70% energy savings at night compared to traditional lighting.

Instantaneous Response: Reacts to motion in under 10 milliseconds.

Eco-Friendly Automation: Operates with zero manual intervention, extends the lifespan of LED fixtures, and actively reduces the city's carbon footprint.
