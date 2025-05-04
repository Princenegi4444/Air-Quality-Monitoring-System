🌫️ Air Quality Monitoring System using Arduino & MQ135

This project monitors air quality using the MQ135 Gas Sensor and an Arduino Uno. It reads the concentration of gases in the air and displays the output in PPM (Parts Per Million) on the serial monitor, providing real-time air quality assessment.

🔧 Components Used

Arduino Uno
MQ135 Gas Sensor
Breadboard & Jumper Wires
USB Cable (for powering and programming Arduino)

💡 Features

Real-time air quality monitoring
Analog sensor reading and voltage-to-PPM conversion
Categorizes air quality based on standard PPM thresholds
Serial monitor output with readable air quality levels

📈 Output Categories

PPM Range	Air Quality Level
0 - 50	Good
51 - 100	Moderate
101 - 200	Unhealthy
201 - 300	Very Unhealthy
301 - 500	Hazardous
500+	Emergency

🛠️ Setup Instructions

Connect the MQ135 sensor to A0 pin of Arduino.
Upload the code using Arduino IDE.
Open the Serial Monitor (set to 9600 baud) to view the air quality readings.

📌 Notes

The PPM calculation is a rough estimate and can be fine-tuned with calibration.
MQ135 detects a range of gases (e.g., NH3, NOx, CO2, alcohol, benzene, smoke).
Make sure to run the sensor in a well-ventilated area during initial warm-up.
📷 Project Demo

(Include a photo or video of your working project here if possible)

📚 References

MQ135 Datasheet
Arduino documentation: https://www.arduino.cc
