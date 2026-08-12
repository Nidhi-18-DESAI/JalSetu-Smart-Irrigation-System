 JalSetu – Smart Irrigation System

An IoT-based smart irrigation system that automatically monitors soil moisture and controls a water pump using an ESP32 microcontroller. The project is simulated using Wokwi and aims to reduce water wastage while improving irrigation efficiency.

 Features

- 🌿 Real-time soil moisture monitoring
- 🌡️ Temperature and humidity sensing
- 💧 Automatic water pump control using a relay
- ⚡ ESP32-based embedded system
- 🖥️ Simulated and tested using Wokwi
- 🌍 Promotes water conservation and smart farming

Tech Stack

- ESP32
- Arduino IDE
- Embedded C/C++
- Soil Moisture Sensor
- DHT22 Sensor
- Relay Module
- Wokwi Simulator

Project Structure


JALSETU
├── Arduino_Code
├── circuit
├── docs
├── images
└── README.md


 How It Works

1. ESP32 reads soil moisture, temperature, and humidity.
2. If the soil moisture falls below a threshold, the relay turns the water pump ON.
3. Once the soil reaches the desired moisture level, the pump turns OFF.
4. The process repeats continuously.

 Screenshots

Add these images after uploading them to GitHub:

- Simulation
- Pump ON
- Pump OFF

🔮 Future Enhancements

- Weather API integration
- Mobile app for remote monitoring
- Cloud-based data logging
- AI-based irrigation prediction

👨‍💻 Author

NIDHI N DESAI