# MODERN HYDROPONIC FARMING

This project demonstrates a **hydroponic farming setup** that grows plants without soil by providing nutrients directly to the roots. The system uses **Arduino (ATmega328P)**, a **moisture sensor**, **LED grow lights**, and a **relay-controlled compressor** to automate watering and lighting for efficient indoor farming.

---

##  Features
- Automated watering using a **moisture sensor** and relay-controlled compressor.  
- **LED grow lights** to ensure consistent photosynthesis.  
- Compact **hydroponic design** for growing vegetables without soil.  
- Power regulation using **7805 and 7812 ICs** for stable operation.  

---

##  Components
- Arduino Uno (ATmega328P)  
- Soil/Moisture Sensor  
- Relay Module  
- LED Grow Lights  
- Compressor (for water supply)  
- Power Regulators (7805, 7812)  
- PCB & Wiring  

---

##  How It Works
1. The **moisture sensor** monitors soil-less medium conditions.  
2. If dry, the **Arduino** activates the **relay**, turning on the compressor to supply water.  
3. **LED lights** provide necessary artificial light to plants.  
4. The cycle ensures plants receive the right amount of water and light automatically.  

---

##  How to Run
1. Connect the hardware as per the circuit diagram.  
2. Open the Arduino IDE and load the project code (`hydroponic_controller.ino`).  
3. Select the correct board (**Arduino Uno**) and port.  
4. Upload the code to the Arduino.  
5. Open the **Serial Monitor** to check sensor readings.  
6. The system will now automatically control watering and lights based on sensor data.  

---

##  Results
- Plants can grow efficiently **without soil**.  
- Automated watering reduces human effort.  
- Compact design makes it suitable for **indoor and urban farming**.  

---

##  Future Improvements
- Add pH/EC sensors for nutrient monitoring.  
- Cloud-based data logging.  
- More efficient power supply (DC converters instead of linear regulators).  

---

##  Project Info
This project was developed as my **Diploma Final Year Project (2019)** at *St. John College of Engineering and Management*.  
